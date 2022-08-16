How To Setup The EPPS Network Printers on macOS
===============================================

There are several network printers which EPPS faculty, staff, lecturers and teaching assistants may use. To use them, you must have a valid copy code. To install them on your computer, follow these steps:

Identify which printer you want to install. Here is a list of the available printers:

**Note:** Only copy/paste the IP address in **bold**

*   **10.152.42.25** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865))
*   **10.152.40.29** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the right)
*   **10.152.40.30** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the left)

Next download the driver for your operating system from Ricoh:

[MP 6503SP/7503SP/9003SP Downloads - Ricoh Global](https://support.ricoh.com/bb/html/dr_ut_e/rc3/model/mp6503/mp6503.htm)

On **macOS**, there should only be one available option to download, which is a **PPD** installer.

macOS
-----

### Install the Drivers

Download the driver file for your version of macOS from the Ricoh website linked above. Find the instllation file in Finder, which should be in your Downloads folder with a file extension of ".dmg", for example: "Ricoh\_PS\_Printers\_Vol4\_EXP\_LIO\_4.0.0.0.dmg". Double-click that to run it, and enter your computer password when prompted.

Once you’ve installed that, go to the Apple menu at the top left of the screen and choose **System Preferences…**:

![](/images/faq/macos1.png)

Then go to **Printers & Scanners**:

![](/images/faq/macos2.png)

Then click the plus (“+”) button at the bottom of the list of printers (you may not have any listed yet), and choose **Add Printer or Scanner…”**:

![](/images/faq/macos3.png)

Next click the **IP** button at the top:

![](/images/faq/macos4.png)

Next enter the **Address** of the printer you want to connect to, and choose the **LPD** protocol:

![](/images/faq/macos5.png)

Note: use the IP address at the top of this page for the printer you want to install.

Next, if the correct driver is not automatically detected and selected, click **Select Software…**:

![](/images/faq/macos6.png)

Find and select **RICOH Aficio MP 7503 PS** and press **OK**:

![](/images/faq/macos7.png)

The next window asks for installed accessories, choose the following options and press **OK**.

**Note:** On newer versions of MacOS, you aren’t automatically presented with the window to select the installed accessories. After printer installation, select the printer in the **System Preferences > Printers & Scanners** window, click **Options & Supplies** and then go to the **Options** tab and set the installed accessories as the screenshot below:

![](/images/faq/macos8.png)

On a Mac, you have to enter your copy code when you print – you can’t specify it in the System Preferences. To do that can vary by application, but it will commonly look like the below screenshots. In MS Word, for example, go to the **File** menu and choose **Print…** and you will see the print dialog box. Find the drop-down menu, in this case it says **Copies & Pages**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%201.png)

Select **Job Log**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%202.png)

Then check **Enable User Code** and type your copy code in, and then press **Print**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%203.png)

Note that you have to do this every time your print, unless you save it as a preset under the **Presets** drop-down menu.

If you are using the printer to the left as you walk in **GR 2.818** (10.152.40.30), you need to use the **Locked Print** function instead of **Normal Print**:

[How To Setup “Locked Print” On The EPPS Network Printers | EPPS Academic Computing](setup-locked-print.html)

Application Specific Instructions for MacOS
-------------------------------------------

In MacOS, some applications present a compact/minimal print dialog box where the drop-down menu to get to the Job Log settings is not immediately visible. For instance, **TextEdit** and older versions of **Firefox** use this compact view, if you see this when you try to print, click **Show Details**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%204.png)

Then find the drop-down menu to access the **Job Log** options as before:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%205.png)

On newer versions of MacOS, some applications, including newer versions of **Firefox** and **Adobe Acrobat** have their own print dialog windows. In those cases, you’ll need to find the option to print using the system dialog window.

In **Firefox**, click **Print using the system dialog:**

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.34.46-AM.png)

In **Adobe Acrobat** click **Printer:**

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.35.31-AM.png)

Then click **Yes** (you may optionally check the box to not show the message again):

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.35.51-AM.png)

Then click **Show Details**:

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.36.04-AM.png)