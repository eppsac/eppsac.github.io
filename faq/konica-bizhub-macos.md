How To Setup The Konica bizhub 658e on macOS
===============================================

There is a Konica Minolta bizhub 658e network printer in **GR 3.706** which EPPS faculty, staff, lecturers, and teaching assistants who are teaching a course may use. To use it, you must have a valid copy code. To install them on your computer, follow these steps:

## Printer Address

During the setup, you will need the IP address of the printer, which is found below:

**Note:** Only copy/paste the IP address in **bold**

*   **10.152.42.35** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865))

## <a name="#driver"></a>Download and Install the Drivers

Determine your operating system version by going to the Apple menu and selecting **About This Mac**:

![](/images/faq/netprinters-mac/driver-install/1.png)

Note the version name and number, **Monterey 13.4.1** in this example:

![](/images/faq/netprinters-mac/ventura-about-this-mac.png)

If you are using an older version of macOS, some steps will look different. See this page for instructions for older versions:

[How to Setup the Konica bizhub 658e on macOS 11-12](konica-bizhub-macos-older-versions.html)

Open the following URL in a web browser:

[Konica Minolta Business Solutions - bizhub 658e Drivers](https://onyxweb.mykonicaminolta.com/OneStopProductSupport?appMode=public&productId=2090&categoryId=1&subCategoryId=ft0)

Scroll down the page and click the ">" to expand the section for your version of "Mac OS" - if your exact version isn't listed, try the closest version you can find:

![](/images/faq/netprinters-mac/konica-driver-os-selection.png)

Click the link for the ".zip" file to save it to your computer:

![](/images/faq/netprinters-mac/konica-driver-download.png)

Find the file in Finder, which should be in your Downloads folder with a file extension of ".zip", for example:

![](/images/faq/netprinters-mac/konica-driver-open.png)

Click to open that file and a new window will open. Open the new extracted files folder with the same name:

![](/images/faq/netprinters-mac/konica/driver-install/4.png)

Double-click the ".pkg" file in that folder to start the installation:

![](/images/faq/netprinters-mac/konica/driver-install/5.png)

Follow the prompts to install the drivers, enter your local MacOS computer password when prmopted (or use your fingerprint if you have TouchID), finish the installation, and then you can select to "Move to Trash" at the end:

![](/images/faq/netprinters-mac/konica/driver-install/6.png)

![](/images/faq/netprinters-mac/konica/driver-install/7.png)

![](/images/faq/netprinters-mac/konica/driver-install/8.png)

![](/images/faq/netprinters-mac/konica/driver-install/9.png)

![](/images/faq/netprinters-mac/konica/driver-install/10.png)

![](/images/faq/netprinters-mac/konica/driver-install/11.png)

![](/images/faq/netprinters-mac/konica/driver-install/12.png)

![](/images/faq/netprinters-mac/konica/driver-install/13.png)

![](/images/faq/netprinters-mac/konica/driver-install/14.png)

## <a name="#setup"></a>Setup Printer

Once you’ve installed that, go to the Apple menu at the top left of the screen and choose **System Settings…**:

![](/images/faq/netprinters-mac/ventura-system-settings.png)

Then go to **Printers & Scanners** in the left sidebar:

![](/images/faq/netprinters-mac/ventura-printers-and-scanners.png)

Then click the **Add Printer, Scanner or Fax** button below the list of installed printers (you may not have any listed yet):

![](/images/faq/netprinters-mac/ventura-add-printer.png)

Next click the "globe" icon/button at the top:

![](/images/faq/netprinters-mac/4.png)

Next enter the **Address** of the printer you want to connect to, and choose the **LPD** protocol:

![](/images/faq/netprinters-mac/konica/1.png)

> Note: use the IP address at the top of this page for the printer that you want to install.

Change the name to something you will recognize (otherwise it will default to the IP address). You can also choose to enter a room number/location:

![](/images/faq/netprinters-mac/konica/2.png)

In the "Use" drop-down box, click **Select Software…**:

![](/images/faq/netprinters-mac/konica/3.png)

Type "658e" in the search box and then select **KONICA MINOLTA 658e PS** and press **OK**:

![](/images/faq/netprinters-mac/konica/4.png)

Back at the Add Printer window, click **Add** at the bottom:

![](/images/faq/netprinters-mac/konica/5.png)

A window should open and ask for installed accessories, choose the following options and press **OK**:

![](/images/faq/netprinters-mac/konica/6.png)

## <a name="#code-and-preset"></a>Copy Code and Presets

On a Mac, you have to enter your copy code when you print – you can’t specify it in the System Preferences. The steps to do that can vary by application, but it will commonly look like the below screenshots. 

In **Preview**, for example, go to the **File** menu and choose **Print…** and you will see the print dialog box. If you see a **Show Details** button, click that:

![](/images/faq/netprinters-mac/12.png)

Scroll down and click **Printer Options**:

![](/images/faq/netprinters-mac/konica-printer-options-dialog.png)

Next click **Output Method**:

![](/images/faq/netprinters-mac/konica-printer-options-output-method.png)

Check the box next to **Account Track**:

![](/images/faq/netprinters-mac/konica/8.png)

In the window that opens enter "EPPS" for the **Department Name** and your Copy Code in the **Password** box. Check the box next to **Save Settings** and click **OK**:

![](/images/faq/netprinters-mac/konica/9.png)

> Do not click Print yet! If you skip this next step, you'll need to enter your copy code **every** time you print to that printer.

Next, at the top of window in the **Presets** drop-down box, choose **Save Current Settings as Preset...**:

![](/images/faq/netprinters-mac/konica/10.png)

Give the preset a name, and click **OK**:

![](/images/faq/netprinters-mac/konica/11.png)

That will take you back to the print dialog box. Make sure other options like number of copies and 2-sided are set as needed, and then click **Print** to send the job to the printer:

![](/images/faq/netprinters-mac/konica/12.png)

## <a name="other-apps"></a>Other Applications

Other applications may present their own print dialog windows. In those cases, you’ll need to find the option to print using the system dialog window.

In **Firefox**, click **Print using the system dialog:**

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.34.46-AM-2.png)

In **Adobe Acrobat** click **Printer:**

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.35.31-AM.png)

Then click **Yes** (you may optionally check the box to not show the message again):

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.35.51-AM.png)

Then click **Show Details**:

![](/images/faq/ricoh-mac/Screen-Shot-2022-04-21-at-8.36.04-AM-2.png)

## Preset Reminder

This is just a reminder to set a preset when you install a printer and try to print something for the first time. Then you don't have to deal with finding the right print dialog box or drop-down menu every time you print. As long as you select the correct printer and preset that has the code enabled, it should work.
