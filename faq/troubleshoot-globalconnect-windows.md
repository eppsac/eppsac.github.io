How to Troubleshoot GlobalProtect VPN in Windows
================================================

If you are not connected to VPN, the steps to troubleshoot GlobalProtect are:

1.  [Connect to GlobalProtect](#connect)
2.  [Start the GlobalProtect client](#start-globalprotect)
3.  [Restart the PanGPS service](#restart-service)
4.  [Restart Windows](#restart-windows)
5.  [Uninstall and reinstall GlobalProtect](#uninstall-reinstall)

## <a name="connect"></a>
**Connect to GlobalProtect**

Check the Windows task tray to see if GlobalProtect is running. If so, you should see a gray globe icon like this:

![](/images/faq/troubleshoot-globalconnect-windows/LoZgtu0K4Q.png)

If you do not see the globe icon, skip to the troubleshooting step to [start the GlobalProtect client](#start-globalprotect).

If the globe icon is present, click it and you should get a window to connect:

![](/images/faq/troubleshoot-globalconnect-windows/euHTQu3oCR.png)

Click **Connect** and then you should see the UTD Single-Sign On login window:

![](/images/faq/troubleshoot-globalconnect-windows/PanGPA_Siny0xSeqE.png)

Log in there to connect to VPN.

If you do not see the previous **Connect** window, or if you click it and you don’t see the UTD login window, skip to the troubleshooting step to [restart the PanGPS service](#restart-service).

## <a name="start-globalprotect"></a>
**Start the GlobalProtect client**

Click on the Windows/Start menu in the bottom left corner of your screen and start typing “GlobalProtect” and it should search for and find the application – click on the **GlobalProtect** app that it finds:

![](/images/faq/troubleshoot-globalconnect-windows/HFc7WPfaep-1.png)

Now try to follow the steps to [Connect to GlobalProtect](#connect).

## <a name="restart-service"></a>
**Restart the PanGPS service**

Click on the Windows/Start menu in the bottom left corner of your screen and start typing “services” and it should search for and find the application – click on the **Services** app that it finds:

![](/images/faq/troubleshoot-globalconnect-windows/cTXBdoPOJ3.png)

In the window that opens, scroll down in the list and find the PanGPS service and click on it to select it and then click the green triangle icon at the top to start the service:

![](/images/faq/troubleshoot-globalconnect-windows/mmc_QkGjjA314Lx560.png)

If the triangle icon is grayed out, click on the square icon to stop the service, then click on the green triangle to start the service:

![](/images/faq/troubleshoot-globalconnect-windows/mmc_fZxMyYdRxkx560.png)

The UTD Single-Sign On login window should come up automatically in a few seconds. If it doesn’t, try following the steps to [Connect to GlobalProtect](#connect).

## <a name="restart-windows"></a>
**Restart Windows**

Restarting your computer should have the same effect as restarting the PanGPS service and opening GlobalProtect. It can take longer, but may be an easier “one step” option.

## <a name="uninstall-reinstall"></a>
**Uninstall and Reinstall GlobalProtect**

If all else fails, try uninstalling GlobalProtect and reinstalling it.

To uninstall it, click on the Windows/Start menu in the bottom left corner of your screen and start typing “control panel” and it should search for and find the application – click on the **Control Panel** app that it finds:

![](/images/faq/troubleshoot-globalconnect-windows/MKEsuQSQlv.png)

Select **Uninstall a program**:

![](/images/faq/troubleshoot-globalconnect-windows/explorer_tcGwRMaCHB.png)

Find **GlobalProtect** in the list of programs, click on it to select it, and then click **Uninstall** at the top of the window:

![](/images/faq/troubleshoot-globalconnect-windows/explorer_01Vwcmfwba.png)

Follow the prompts to uninstall GlobalProtect and then restart the computer. Then follow OIT’s instructions to download and install GlobalProtect for Windows again:

[https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=152](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=152)
