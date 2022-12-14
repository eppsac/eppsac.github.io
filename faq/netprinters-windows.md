How To Setup The Ricoh Network Printers on Windows
=================================================

There are several Ricoh network printers which EPPS faculty, staff, lecturers, and teaching assistants (who are teaching a course) may use. To use them, you must have a valid copy code. To install them on your computer, follow this guide.

## Identify Printer

Identify which printer you want to install. Here is a list of the available printers:

**Note:** Only copy/paste the IP address (numbers) in **bold**

*   **10.152.42.25** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865))
*   **10.152.40.29** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the right)
*   **10.152.40.30** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the left)

## Download the Drivers

Next, download the driver for your operating system from Ricoh:

[MP 6503SP/7503SP/9003SP Downloads - Ricoh Global](https://support.ricoh.com/bb/html/dr_ut_e/rc3/model/mp6503/mp6503.htm)

On **Windows**, you can choose the **PCL6** driver.

## <a name="#drivers"></a>Extract the Drivers

Now we need to extract the drivers. First open the **File Explorer**:

![](/images/faq/Manual-Win10/1.png)

Then go to where you downloaded the file (this assumes your **Downloads** folder):

![](/images/faq/Manual-Win10/Drivers/downloads.png)

Double-click on the **.exe** file (it should start with ‘**z**‘ with some numbers and letters after it) and in the window that opens, change the end of the path to match below so that it says **c:\\temp\\ricoh** and press **Unzip**:

![](/images/faq/Manual-Win10/z91790L16_d1g4D7Gy3L.png)

You should get a confirmation that it’s successful; click **OK**, and then click **Close**:

![](/images/faq/Manual-Win10/z91790L16_8TbDsinbpx.png)

![](/images/faq/Manual-Win10/z91790L16_Zx9xAycvZR.png)

Note: If you didn’t change the path, take note of where the files are extracted to, it will be in the same temporary folder, but with ‘z’ and numbers and letters, like the example below:

**c:\\temp\\z79059L16**

If you are installing more than one printer, you only need to download and extract the drivers once. Just repeat the steps for each from this point forward.

## <a name="add-printer"></a>Add the Printer

Open the Control Panel by clicking on the Start menu (Windows icon/logo menu in lower left corner) and type “**control panel**” to search (no need to click on anything, just start typing and then click on the match it finds at the top):

![](/images/faq/Manual-Win10/0.png)

Depending on which Control Panel view you are in, click **View devices and printers** under **Hardware and Sound**, or just go straight to **Devices and Printers**:

![](/images/faq/Manual-Win10/3a.png)

![](/images/faq/Manual-Win10/3c.png)

Once you are at **Devices and Printers**, click on **Add a printer**:

![](/images/faq/Manual-Win10/4.png)

Next click **The printer that I want isn’t listed:**

![](/images/faq/Manual-Win10/5.png)

Next choose **Add a local printer or network printer with manual settings:**

![](/images/faq/Manual-Win10/rundll32_qlwJRO89yV.png)

Choose **Create a new port** and for **Type of port** choose: **Standard TCP/IP Port**:

![](/images/faq/Manual-Win10/rundll32_ctBGY9bjE1.png)

Type in the **Hostname or IP address**, the **Port name** will be automatically filled in. _Uncheck_ the box that says **Query the printer and automatically select the driver to use** and then click **Next**:

![](/images/faq/Manual-Win10/8.png)

**NOTE –** Use the IP address below that corresponds with the printer that you want to install (only copy the numbers in bold at the top of this page, see the example in the screenshot above).

On the next screen choose **Have Disk…**:

![](/images/faq/Manual-Win10/9.png)

Now you need to browse to where you extracted the drivers:

![](/images/faq/Manual-Win10/10.png)

If you used the default location, simply copy/paste the following in to the box at the bottom and press **OK**:

**c:\\temp\\ricoh\\disk1\\**

![](/images/faq/Manual-Win10/explorer_rkK45UstTP.png)

If you extracted the drivers somewhere else, you’ll need to click **Browse** and find the **oemsetup** file, for example: “c:\\temp\\z79059L16\\disk1\\oemsetup”

![](/images/faq/Manual-Win10/11.png)

Next choose **Ricoh** from the list on the left, and **RICOH MP 7503 PCL 6** from the list on the right, and click **Next**:

![](/images/faq/Manual-Win10/12.png)

Give the printer a description/name:

![](/images/faq/Manual-Win10/13.png)

Choose **Do not share this printer** and click **Next**:

![](/images/faq/Manual-Win10/14.png)

Do not try to print a test page yet (it won’t work); click **Finish**:

![](/images/faq/Manual-Win10/15.png)

## <a name="printing-prefs"></a>Set Printing Preferences

Right-click on the printer you just installed and choose **Printing Preferences**:

![](/images/faq/Manual-Win10/Preferences/1.png)

For the **GR3.706** and **GR2.818 (right)** printers, set your User Code by going to the **Detailed Settings** tab, choose **Job Setup** from the menu, and enter your **User Code** (should be 4 or 6 digits) and then press **Apply/OK**:

![](/images/faq/Manual-Win10/Preferences/user-code.png)

For the **GR2.818 (left)** printer, do not set a User Code, instead you must select the **Locked Print** function from the **Job Type** menu and then click **Details**:

![](/images/faq/Manual-Win10/Preferences/locked-print-1.png)

Now enter your **User ID** (6-digits) and **Password** (4-digits) and then press **OK**:

![](/images/faq/Manual-Win10/Preferences/locked-print-2.png)

Then press **Apply/OK** to exit the Printing Preferences.

Visit the following page to learn more about the Locked Print function and how to retrieve print jobs:

[How To Setup “Locked Print” On The EPPS Network Printers | EPPS Academic Computing](setup-locked-print.html)
