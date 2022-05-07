<h1>Raspberry Pi Home NAS Lab</h1>

<h2>Description</h2>
This lab details the setup process for my home NAS running on a Raspberry Pi 4 with Raspberry Pi OS Lite and OpenMediaVault.
<br />


<h2>Technologies Used</h2>

- <b>PuTTY - SSH</b> 
- <b>OpenMediaVault</b>

<h2>Environments</h2>

- <b>Windows 10</b>
- <b>Linux CLI</b>

<h2>Program walk-through:</h2>

<p align = "center">
Identify the Raspberry Pi's ip address and connect to it via SSH: <br/>
  <br/>
<img src="https://i.imgur.com/NgPSSkW.png" height="80%" width="80%" alt=""/>
<br />
<br />
Run this command to install OpenMediaVault:  <br/>
  <br/>
<img src="https://i.imgur.com/nKFkeTv.png" height="80%" width="80%" alt=""/>
<br />
  <br />
  OpenMediaVault Web Browser Interface
  <br />
<br />
Find the disk that will be used as storage: <br/>
  <br/>
<img src="https://i.imgur.com/mPypFcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Establish the File System:  <br/>
  <br/>
<img src="https://i.imgur.com/VsCHzl1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Establish the Shared Folder:  <br/>
Must enablle SMB/CIFS <br/>
  <br/>
<img src="https://i.imgur.com/Ia4H0iu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Access the Folder from Windows  10 (Other OS may be used):  <br/>
  <br/>
<img src="https://i.imgur.com/b73VKHg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
