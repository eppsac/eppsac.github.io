How To Setup The Ricoh Network Printers on macOS 10-12
===============================================

There are several Ricoh network printers which EPPS faculty, staff, lecturers, and teaching assistants (who are teaching a course) may use. To use them, you must have a valid copy code. To install them on your computer, follow this guide.

## WiFi Note

If your computer uses wireless networking, printing does *not* work if using the **UTDGuest** network. You must be connected to **CometNet** (or **CometNet_Legacy**):

[https://atlas.utdallas.edu/TDClient/30/Portal/Requests/ServiceDet?ID=170](https://atlas.utdallas.edu/TDClient/30/Portal/Requests/ServiceDet?ID=170)

## Identify Printer

Identify which printer you want to install. Here is a list of the available printers:

**Note:** Only copy/paste the IP address (numbers) in **bold**

*   **10.152.42.25** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865) on the right)
*   **10.152.42.34** (in [GR 3.706](https://map.concept3d.com/?id=1772#!m/550865) straight ahead)
*   **10.152.40.29** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the right)
*   **10.152.40.30** (in [GR 2.818](https://map.concept3d.com/?id=1772#!m/550792) on the left)

## <a name="#driver"></a>Download and Install the Drivers

Determine your operating system version by going to the Apple menu and selecting **About This Mac**:

![](/images/faq/netprinters-mac/driver-install/1.png)

Note the version name and number, "**Monterey 12.5**" in this example:

![](/images/faq/netprinters-mac/driver-install/2.png)

Open the following URL in a web browser:

[IM 7000/IM 8000/IM9000 Downloads - Ricoh Global](http://support.ricoh.com/bb/html/dr_ut_e/re1/model/im7000/im7000.htm)

Scroll down the page and expand the "Mac OS X" section and select your version:

![](/images/faq/netprinters-mac/driver-install/3.png)

Click the "Download" button to save the file to your computer:

![](/images/faq/netprinters-mac/driver-install/4.png)

Find the installation file in Finder, which should be in your Downloads folder with a file extension of ".dmg", for example:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.36.20 AM.png)

Click to open that file and a new window will open. Double-click the ".pkg" file inside to start the installation:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.37.44 AM.png)

Follow the prompts to install the drivers, enter your local MacOS computer password when prmopted (or use your fingerprint if you have TouchID), finish the installation, and then you can select the "Move to Trash" option at the end:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.37.57 AM.png)

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.38.15 AM.png)

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.38.36 AM.png)

![](/images/faq/netprinters-macim7000/Screenshot 2023-10-03 at 8.38.48 AM.png)

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.39.07 AM.png)

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.39.28 AM.png)

![](/images/faq/netprinters-mac/driver-install/13.png)

## <a name="#setup"></a>Setup Printer

Once you’ve installed that, go to the Apple menu at the top left of the screen and choose **System Preferences…**:

![](/images/faq/netprinters-mac/1.png)

Then go to **Printers & Scanners**:

![](/images/faq/netprinters-mac/2.png)

Then click the plus (“+”) button at the bottom left of the list of printers (you may not have any listed yet):

![](/images/faq/netprinters-mac/3.png)

Next click the "globe" icon or **IP** button at the top:

![](/images/faq/netprinters-mac/4.png)

Next enter the **Address** of the printer you want to connect to, and choose the **LPD** protocol:

![](/images/faq/netprinters-mac/5.png)

> Note: use the IP address at the top of this page for the printer you want to install.

Change the name to something you will recognize (otherwise it will default to the IP address). You can also choose to enter a room number/location:

![](/images/faq/netprinters-mac/6.png)

In the "Use" drop-down box, see if the correct driver is automatically detected and selected:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.41.16 AM.png)

If it is not already selected, click **Select Software…**:

![](/images/faq/netprinters-mac/8.png)

Type "7000" in the search box and then select **RICOH IM 7000 PS** and press **OK**:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.41.44 AM.png)

That will install the printer. When it's done, click **Options & Supplies**:

![](/images/faq/netprinters-mac/10.png)

Then in the **Options** tab, set the following options in the drop-down menus and click **OK**:

![](/images/faq/netprinters-mac/im7000/Screenshot 2023-10-03 at 8.42.36 AM.png)

## <a name="#code-and-preset"></a>Copy Code and Presets

On a Mac, you have to enter your copy code when you print – you can’t specify it in the System Preferences. The steps to do that can vary by application, but it will commonly look like the below screenshots.

In **Preview**, for example, go to the **File** menu and choose **Print…** and you will see the print dialog box. Click **Show Details**:

![](/images/faq/netprinters-mac/12.png)

Now find the drop-down menu that doesn't have a label next to it, in this case it says **Preview**. Click that and then select **Job Log**:

![](/images/faq/netprinters-mac/13.png)

Check the box next to **Enable User Code** and then enter your **Copy Code** in the box provided:

![](/images/faq/netprinters-mac/14.png)

> Do not click Print yet! If you skip this next step, you'll need to enter your copy code **every** time you print to that printer.

Next, at the top of window in the **Presets** drop-down box, choose **Save Current Settings as Preset...**:

![](/images/faq/netprinters-mac/15.png)

Give the preset a name, and click **OK**:

![](/images/faq/netprinters-mac/16.png)

That will take you back to the print dialog box. Make sure other options like number of copies and 2-sided are set as needed, and then click **Print** to send the job to the printer:

![](/images/faq/netprinters-mac/17.png)

## <a name="#other-apps"></a>Other Applications

Finding the **Job Log** section can depend on which application you are printing from.

In MS Word, for example, when you go to the **File** menu and choose **Print…**, you will see the print dialog box. Find the drop-down menu, in this case it says **Copies & Pages**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%201.png)

Select **Job Log**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%202.png)

Then set the **User Code** and **Preset** as in the previous section.

Some applications may present a "print dialog" box, if you see this when you try to print, click **Show Details**:

![](/images/faq/Mac%20Ricoh%20Printing%20Step%204.png)

Then find the drop-down menu to access the **Job Log** options as before.

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
