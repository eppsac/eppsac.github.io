How to Export/Import Digital Certificates in Windows
====================================================

When you get a new computer, or have multiple computers, you can export your digital certificate from one computer to another if it was originally installed correctly.

If you follow the steps to export and you can not proceed, it likely means it was not **marked as exportable** and you’ll likely need to enroll for a new certificate:

*   [Enroll, Install, and Publish Digital Certificates on Windows](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=29)
*   [Enroll and Install Digital Certificates on Mac](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=560)

Export a Digital Certificate in Windows
---------------------------------------

Open **File Explorer** and go to the **Control Panel** (click the arrow to the left of **This PC** to get the drop down):

![](/images/faq/import-export-certs-windows/explorer_7AAZ5H0BbG.png)

Change **Category** to one of the other options and then choose **Internet Options**:

![](/images/faq/import-export-certs-windows/explorer_V9ridtdrOd.png)

![](/images/faq/import-export-certs-windows/explorer_Ado7Qb3qfJ.png)

Then go to the **Content** tab and select **Certificates**:

![](/images/faq/import-export-certs-windows/rundll32_lUoWDHvWT6.png)

Under the **Personal** tab, select the one that has your name and says that it’s issued by the University of Texas at Dallas and choose **Export**. If you have multiple, you’ll need to repeat this process from here for each one:

![](/images/faq/import-export-certs-windows/rundll32_a9SKfgxWTt.png)

As you go through the Certificate Export Wizard that comes up, the options you want to change are:

![](/images/faq/import-export-certs-windows/rundll32_OyCW5tKCx2.png)

Select “Yes, export the private key”

![](/images/faq/import-export-certs-windows/rundll32_d8FZLiEY44.png)

Select “Export all extended properties”

![](/images/faq/import-export-certs-windows/rundll32_rHkijew2eY.png)

Give it a password (you’ll need this later when you install it on the other computer)

Browse to where you want the file saved – I suggest Box Drive or OneDrive so you can pick it up on the other computer without manually transferring the file. Otherwise save it anywhere on the computer and email it to yourself or copy it with a flash drive:

![](/images/faq/import-export-certs-windows/rundll32_9ZxZ1ffttS-1.png)

Repeat the steps to export any other personal certificates, even if they are expired.

Import a Digital Certificate in Windows
---------------------------------------

Go to the new computer and download or copy the certificate file(s) you exported. Once the file is on the new computer just double-click on it to start the Certificate Import Wizard:

![](/images/faq/import-export-certs-windows/rundll32_keiEnW5rsK.png)

Click **Next** until you are asked to enter the password that you set during the export process. Also, **make sure to check the box that says _Mark this key as exportable_**:

![](/images/faq/import-export-certs-windows/rundll32_tuCggLrdDv.png)

Click **Next** until you are done. The certificate should now be usable on the new computer to perform tasks such as signing PDF documents in Adobe Acrobat:

[https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=298](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=298)