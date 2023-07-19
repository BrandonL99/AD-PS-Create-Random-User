<h1>Active Directory PowerShell Random User Creation

</h2>
The project consists of a simple PowerShell script that walks the user through creating users in Active Directory with a randomly generated username.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtualbox</b>
- <b>Active Directory</b>

<h2>Environments Used </h2>

- <b>Windows server 2022</b>
- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Download the file from the code drop-down menu and click download ZIP. Go to your Domain Controller and open it. <br/>
<img src="https://i.imgur.com/hsPei0H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Were going to run Windows Powershell ISE as administrator.  <br/>
<img src="https://i.imgur.com/UVBBN1a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Were going to run Windows Powershell ISE as administrator. Now on the top left click Open script and open the script from the file. Now at the top where it shows 
Get-Content and then the C:\Users\a-blorenzo\Desktop\AD_PS_Create_Random_User-. Find where you saved the file and right click on the location and click Copy address as text.<br/>
<img src="https://i.imgur.com/nHqtOIK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Paste at that location and at the end put \names.txt Now at the bottom you will type Set-ExecutionPolicy Unrestricted and click Yes to All, Now click Run Script. <br/>
<img src="https://i.imgur.com/aDGYDd2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://i.imgur.com/xVn8Qxj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now you can see the name it generated so it is working. <br/>
<img src="https://i.imgur.com/x65aEMr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
So if you go to Tools and Active Directory Users and Computers on the server manager, click the drop-down menu on mydomain.com and click _USERS, you can see the profiles it has created.   <br/>
<img src="https://i.imgur.com/X6BsKRD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now if you go over to our client, click Other user and type in the user and Password1, showing the script and domain works.  <br/>
<img src="https://i.imgur.com/oA13NyE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
