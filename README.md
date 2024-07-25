<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Part 1 (Create Virtual Machine in Azure)
  1. Create a Resource Group
  2. Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs
- Part 2 (Installation)
  1. Create an Azure Virtual Machine Windows 10, 4 vCPUs
  2. Install / Enable IIS in Windows:
      a. CGI and Common HTTP Features
      b. IIS Management Console
  3. Download and install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
  4. Download and install the Rewrite Module (rewrite_amd64_en-US.msi)
  5. Create the directory C:\PHP
  6. Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) 
  7. Unzip the contents into C:\PHP
Download and install VC_redist.x86.exe.
Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
Open IIS as an Admin
Register PHP from within IIS
Reload IIS (Open IIS, Stop and Start the server)
Install osTicket v1.15.8
Reload IIS (Open IIS, Stop and Start the server)
Go to sites -> Default -> osTicket
Note that some extensions are not enabled, enable the extension.
Rename: ost-config.php
Assign Permissions: ost-config.php
Continue Setting up osTicket in the browser 
Download and install HeidiSQL.
Continue Setting up osticket in the browser
End Users osTicket URL:
http://localhost/osTicket/ 
Clean up
Delete: C:\inetpub\wwwroot\osTicket\setup
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
Notes:
Browse to your help desk login page: http://localhost/osTicket/scp/login.php  
End Users osTicket URL: http://localhost/osTicket/ 


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
