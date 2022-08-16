How To Setup A Personal Webpage
===============================

These instructions may be outdated, please also refer to UTD's OIT Knowledge base article as well: [How to Setup Your Home Page (Personal Webpage)](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=11).

This document gives general instructions on creating a webpage on the UTD web server. It requires the following:

1.  Current UTD NetID
2.  Microsoft Word
3.  WinSCP

Software package 2 and 3 are available to UTD EPPS students at the computer labs. You can use the [Microsoft Office 365](https://oit.utdallas.edu/o365/) suite. You may download [WinSCP](https://winscp.net/eng/download.php) for free.

I. Creating web page using MS Word

The user may design the webpage using Word. Open Word and click File→New and choose Web page. Alternatively, one may save the file as webpage to create the HTML file (Save as type \*.html, \*.htm)

For design layout, one may use the Format→Theme to start with some predesigned themes featuring a variety of color and font set schemes. For HTML basics, visit [http://www.w3schools.com/](http://www.w3schools.com/).

II. Uploading the HTML file to web server using WinSCP

Once the HTML file(s) are ready, it is recommended using WinSCP to upload and manage webpage files. Previous methods using Putty and SSH involve UNIX command line operations. WinSCP allows users to perform all task at one Windows interface. For instructions installing the software, consult the [SFTP on Windows](https://www.utdallas.edu/oit/howto/use-sftp/) page from the Office of Information Technology.

Use the following procedures for using WinSCP to upload and manage your webpages:

a. Open WinSCP (shortcut available at EPPS lab computer desktop)

b. Type in the web server address **giant.utdallas.edu** at the host name box. Fill in your NetID and password at appropriate boxes and click Login:

![](/images/faq/winscp-login.png)

c. If prompted to add host locally, click Yes

![](/images/faq/personal-webpage03.jpg)

d. Click Continue at the UTD Authentication Banner

![](/images/faq/personal-webpage04.jpg)

e. Next will display a screen with two big boxes, local drives on the left and your server account folders on the right. At the right box, check if the public\_html folder exists. If not, hit Function key F7 to create that directory. Note that on UNIX, it is case-sensitive. Make sure you create a folder/directory exactly named public\_html and set the permissions as indicated below:

![](/images/faq/winscp-new-directory.png)

![](/images/faq/winscp-create-folder-set-perms.png)

f. Now, for the left box, use the pull down menu above the folder box to navigate to where your html files are. Alternatively, you may use the to go to parent directories and then locate your html file folder. One recommendation is to use the public drive H: to store your html files. Another option is to use USB drive.

g. Uploading – On server side (right), open the public\_html folder and on local side (left), highlight the files you are to upload. You may drag the highlighted files to the RHS box or hit function key F5 to perform the copying/uploading

![](/images/faq/personal-webpage06.jpg)

h. A Copy box appears to confirm your copying/uploading action. At this point, check the set permission box at the Attributes section on right hand side. Important: make sure you select (rw-r- -r- – (+x)) allowing the files to be readable by the public. The octal flag is 755. You may also click on the button next to the flags to specify different combinations of permissions (R is readable, W is writable and X is executable). Be sure you check on the box “Use same settings next time”.

![](/images/faq/personal-webpage07.jpg)

i. Double check if the files are copied with permissions correctly set up:

![](/images/faq/personal-webpage08.jpg)

j. Open a browser and confirm the webpages are uploaded and permissions are set correctly. Your webpage is http://www.utdallas.edu/~NetID, alternatively if you have a PEA (personalized email address) set, you can use http://www.utdallas.edu/~PEA.

III. A few notes:

a. Each student should have a quota of 1gb on web server account. Use the space prudently.

b. For more information and advanced options like CGI or other executables, you may consult with the following OIT Knowledgebase articles:

*   [CGI Under Your Own Home Page (Personal Webpage)](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=336)
*   [Fixing Permissions Issues (Personal Webpage)](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=10)
*   [How to Setup Your Home Page (Personal Webpage)](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=11)
*   [Password Protect a Folder/Page (Personal Webpage)](https://atlas.utdallas.edu/TDClient/30/Portal/KB/ArticleDet?ID=337)