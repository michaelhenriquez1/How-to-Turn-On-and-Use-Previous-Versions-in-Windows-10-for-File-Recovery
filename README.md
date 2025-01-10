
<h1>Step-by-Step Guide: Turn On and Use Previous Versions in Windows 10</h1>



<h2>Description</h2>
Windows 10 offers a useful feature known as Previous Versions, which allows you to restore files and folders to earlier states, even if they were deleted, modified, or corrupted. This feature is based on System Protection and Shadow Copies, which automatically create backups of your system files and folders. Enabling this feature can help protect your important data and allow easy recovery of previous versions of files. This project provides a step-by-step guide on how to turn on Previous Versions in Windows 10, ensuring that your files are backed up and can be restored if necessary.
<br />



<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Step 1: Open the System Properties Window
Right-click the Start button and select System from the context menu.
In the System window, click on System Protection from the left-hand menu. This will open the System Properties dialog box.
Alternatively, you can press Windows + R to open the Run dialog, type sysdm.cpl, and press Enter.
</h2>

<p align="center">
Select system : <br/>
<img src="https://i.imgur.com/BsalUWG.png" height="80%" width="80%" alt=""/>
<br />
<br />
Click on system protection from the left-hand menu:  <br/>
<img src="https://i.imgur.com/IcYOFVI.png" height="80%" width="80%" alt=""/>
<br />
<br />
<h2>Step 2: Enable System Protection
In the System Properties window, you’ll see a tab labeled System Protection. Click on this tab.
Under the Protection Settings section, you’ll see a list of drives on your computer (usually, only the system drive, C:, is listed).
Select the drive for which you want to enable System Protection. Typically, this will be the C: drive (your main system drive).
Click the Configure button to adjust protection settings for the selected drive.
<h2>
Click on tab labeled system protection : <br/>
<img src="https://i.imgur.com/C82IX9x.png" height="80%" width="80%" alt=""/>
<br />
<br />
  Click the configure button to adjust protection settings for the selected drive <br/>
<img src="https://i.imgur.com/CdBmcAZ.png" height="80%" width="80%" alt=""/>
<br />
<br />
  Step 3: Turn On System Protection
In the Configure window, select the Turn on system protection option.
Adjust the Max Usage slider to allocate the amount of disk space that will be used to store restore points and shadow copies. The recommended setting is usually around 10-15% of the drive’s total space.
Click Apply, then click OK to save the changes.
<br/>
<br/>

 Select the turn on system protection option and click ok to save the changes:  <br/>
<img src="https://i.imgur.com/amdgAvS.png" height="80%" width="80%" alt=""/>
<br />
<br />
Step 4: Create a System Restore Point
To ensure that the Previous Versions feature can work, it's important to create a system restore point after enabling System Protection. A restore point is essentially a snapshot of your system files and settings.

Back in the System Properties window, click the Create button under the System Protection tab.
Enter a descriptive name for the restore point (e.g., "Before enabling Previous Versions").
Click Create and wait for Windows to create the restore point. Once complete, you'll see a message confirming the restore point has been created.


Enter a descriptive name for the restore point and click create :  <br/>
<img src="https://i.imgur.com/QN6QRtq.png" height="80%" width="80%" alt=""/>

<br />
<br />

Observe creating restore point :  <br/>
<img src="https://i.imgur.com/iqZwOkb.png" height="80%" width="80%" alt=""/>
<br/>
<br/>
<img src="https://i.imgur.com/iXtCyom.png" height="80%" width="80%" alt=""/>
</p>

<!--
 ```diffEnter a descriptive name for the restore point 
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
