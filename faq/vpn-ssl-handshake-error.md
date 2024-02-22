# NOTICE

The information below should no longer be necessary if you are using Ubuntu 23.10 or higher and GlobalProtect 6.1+. To install the GlobalProtect VPN client on Linux for UTD, follow the instructions here:

> [https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=235](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=235https:/)

# SSL Handshake Error using GlobalProtect VPN on Linux

```
SSL handshake failed
Failed to load URL https://utdvpn.utdallas.edu/SAML20/SP/ACS.
QtNetwork Error 6
```

## Issue: Error Connecting to GlobalProtect VPN on Linux

On newer Linux distributions that use OpenSSL 3.x, such as Ubuntu 22.04 LTS, Fedora 36, Rocky/Alma 9, etc., you will get the above "SSL Handshake failed" error message when trying to connect to the VPN server using the official UTD GlobalProtect client from PaloAlto Networks.

## Cause: Vendor Software Incompatibility

As of September 2022, these newer distributions are not officially supported by PaloAlto Networks:

[https://docs.paloaltonetworks.com/compatibility-matrix/globalprotect/where-can-i-install-the-globalprotect-app#id7a3c3401-b233-43b0-8d78-dfceab88798f_idbcd7ccf7-eceb-462c-8678-1a5fa51cbc18](https://docs.paloaltonetworks.com/compatibility-matrix/globalprotect/where-can-i-install-the-globalprotect-app#id7a3c3401-b233-43b0-8d78-dfceab88798f_idbcd7ccf7-eceb-462c-8678-1a5fa51cbc18)

## Workarounds

The following two workarounds have been tested on both Fedora 36 and Ubuntu 22.04 LTS.

### Workaround: Enable UnsafeLegacyRenegotiation in openssl.cnf

The first workaround is to disable secure renegotiation in **/etc/ssl/openssl.cnf**. The example below uses the **nano** text editor in a terminal. Backup this file before proceeding:

```console
$ sudo cp /etc/ssl/openssl.cnf /etc/ssl/openssl.cnf.bak
$ sudo nano /etc/ssl/openssl.cnf
```

Now scroll down to the **openssl_init** section and add the lines between the comments (\#):

```console
[openssl_init]
providers = provider_sect

# Added to enable unsafe legacy renegotiation
ssl_conf = ssl_sect

[ssl_sect]
system_default = system_default_sect

[system_default_sect]
Options = UnsafeLegacyRenegotiation
# End added to unasfe legacy renegotiation
```

When you are finished editing, press **Ctrl+X** to exit the nano text editor. Press **Y** when prompted to save the file.

Now you can run the VPN client and it should connect. Note that you do still have to install Google Chrome and set it as your default web browser.

### Workaround: Install and Use GlobalProtect-openconnect

Rather than degrading OpenSSL system-wide, an alternative solution is to use a different VPN client. The **GlobalProtect-openconnect** package has been tested on Fedora 36 and Ubuntu 22.04:

[https://github.com/yuezk/GlobalProtect-openconnect](https://github.com/yuezk/GlobalProtect-openconnect)

Note: You do not have to install Google Chrome and set it as your default web browser for this to work.

If you are using Fedora 36, and possibly other distributions, installing the package may be enough. If you are using Ubuntu 22.04, and possibly other related/derived distributions, proceed with the further instructions below.

#### Ubuntu 22.04 LTS

If the VPN client appears to "hang" after authenticating with Duo, you will need to edit the gpclient config file:

To do that, first close any open instances of the client. Then open a terminal and run **gpclient**. After Duo authentication, you should see a message in the terminal output about the server not being trusted. Copy the line that is shown that says **"--servercert pin-sha256:[longStringOfCharacters]"** and then press **Ctrl+C** to stop that client. In most GUI terminals, you can copy by highlighting the text and pressing **Ctrl+Shift+C**.

Now open **/etc/gpservice/gp.conf** in a text editor. The example below uses the **nano** text editor in a terminal. Backup this file before proceeding:

```console
$ sudo cp /etc/gpservice/gp.conf /etc/gpservice/gp.conf.bak
$ sudo nano /etc/gpservice/gp.conf
```

Add the following section to that file. When you need to paste the line you copied before, most GUI terminals will let you right-click to paste or press **Ctrl+Shift+V**:

```console
[utdvpn.utdallas.edu]
openconnect-args=--servercert pin-sha256:[longStringOfCharacters]
```

When you are finished editing, press **Ctrl+X** to exit the nano text editor. Press **Y** when prompted to save the file.

After that, you shouldn’t have to run gpclient from the command line anymore, you can open it from your applications menu/launcher.

References for this workaround:
 

- [https://github.com/yuezk/GlobalProtect-openconnect/issues/163#issuecomment-1165159733](https://github.com/yuezk/GlobalProtect-openconnect/issues/163#issuecomment-1165159733)
- [https://github.com/yuezk/GlobalProtect-openconnect/wiki/Configuration#example](https://github.com/yuezk/GlobalProtect-openconnect/wiki/Configuration#example)
