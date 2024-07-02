How To Setup The Ricoh Network Printers on Windows
=================================================

There are several Ricoh network printers which EPPS faculty, staff, lecturers, and teaching assistants (who are teaching a course) may use. To use them, you must have a valid copy code. To install them on your computer, follow this guide.

## WiFi Note

If your computer uses wireless networking, printing does *not* work if using the **UTDGuest** network. You must be connected to **CometNet** (or **CometNet_Legacy**):

[https://atlas.utdallas.edu/TDClient/30/Portal/Requests/ServiceDet?ID=170](https://atlas.utdallas.edu/TDClient/30/Portal/Requests/ServiceDet?ID=170)

## Identify Printer

Identify which printer you want to install. Here is a list of the available printers:

**Note:** Only copy/paste the IP address (numbers) in **bold**

*   **10.152.42.25** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865) on the right)
*   **10.152.42.34** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865) straight ahead)
*   **10.152.40.29** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the right)
*   **10.152.40.30** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the left)

## Download the Drivers

Next, download the driver for your operating system from Ricoh:

[IM 7000/IM 8000/IM 9000 Downloads - Ricoh Global](http://support.ricoh.com/bb/html/dr_ut_e/re1/model/im7000/im7000.htm)

On **Windows**, you can choose the **PCL6** driver:

![](/images/faq/ricoh-win/pcl6.png)

## <a name="#install"></a>Install the Printer

Now we need to run the file you just downloaded. First open the **File Explorer**:

![](/images/faq/Manual-Win10/1.png)

Then go to where you downloaded the file (this assumes your **Downloads** folder):

![](/images/faq/Manual-Win10/Drivers/downloads.png)

Double-click on the **.exe** file (it should start with ‘**z**‘ with some numbers and letters after it). When prompted, select **Yes** to allow it to make changes to your computer. Then in the installation window, click **Agree and Go to Next**:

![](/images/faq/ricoh-win/RV_SETUP_1.png)

Select **Network** and click **Next**:

![](/images/faq/ricoh-win/RV_SETUP_2.png)

Click **Stop** and then **Click if you cannot find the device**:

![](/images/faq/ricoh-win/RV_SETUP_3.png)
![](/images/faq/ricoh-win/RV_SETUP_4.png)

Choose **Specify device IP address**:

![](/images/faq/ricoh-win/RV_SETUP_5.png)

Enter the IP Address of the printer that you want to install (see the top of this page) and then click **Next**:

![](/images/faq/ricoh-win/RV_SETUP_6.png)

Click **Next** again:

![](/images/faq/ricoh-win/RV_SETUP_7.png)

Click **Finish** (do not print a test page, it won't work without your user code):

![](/images/faq/ricoh-win/RV_SETUP_8.png)


## <a name="printing-prefs"></a>Set Printing Preferences

### Windows 11

Right-click on the Windows/Start menu and choose **Settings**:

![](/images/faq/ricoh-win/win11-settings-1.png)

Then go to **Bluetooth & devices**:

![](/images/faq/ricoh-win/win11-settings.png)

Click on the printer you just installed and choose **Printing Properties**:

![](/images/faq/ricoh-win/win11-printers-and-scanners-list.png)

![](/images/faq/ricoh-win/win11-printer-properties.png)

### Windows 10

Click on the Start menu (Windows icon/logo menu in lower left corner) and type “**devices and printers**” to search (no need to click on anything, just start typing and then click on the match it finds):

![](/images/faq/win10-devices-and-printers.png)

Find and select the printer you want to use. Right-click on the printer and choose **Printer Properties**:

![](/images/faq/ricoh-win/win10-printer-properties.png)

## Printer Properties

In the window that opens, first change the name of the printer to something unique, for example, the Ricoh machine that is to the "right" side as you enter GR 2.818 can be named like this:

![](/images/faq/ricoh-win/change-printer-name.png)

## Printing Preferences

Then click on **Preferences**:

![](/images/faq/ricoh-win/printer-preferences.png)

In the **Basic** tab, click **User Code Setting...**:

![](/images/faq/ricoh-win/user-code-setting.png)

Enter your user code and click **OK**:

![](/images/faq/ricoh-win/user-code.png)

And then click **OK** to close Printing Preferences and **OK** again to close the Printer Properties window.

## Locked Print

If you would like to set the preferences so that your print job is held and locked until you go to the printer and release it, in the **Basic** tab in the previous step, set the **User code setting** if it's not already enterd and then click **Modify** next to **Job Type**. Then select **Locked Print**, enter your NetID next to **Enter User ID**. For the **Password**, you can set that to be the same as your copy code:

![](/images/faq/ricoh-win/locked-print.png)
