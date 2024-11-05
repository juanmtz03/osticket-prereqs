

<h1>osTicket - Prerequisites and Installation</h1>
Comprehensive Guide: Prerequisites and Installation of the Open-Source Help Desk System osTicket

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>List of Prerequisites</h2>

- Part 1 Create Virtual Machine in Azure
  1. Create a Resource Group
  2. Create a Windows 10 Virtual Machine with 2-4 Virtual CPUs
- Part 2 Installation
  1. Create an Azure Virtual Machine Windows 10, 4 vCPUs
  2. Install / Enable IIS in Windows:
      a. CGI and Common HTTP Features
      b. IIS Management Console
  3. Install PHP Manager for IIS 
  4. Install the Rewrite Module 
  5. Create the directory C:\PHP
  6. Download PHP 7.3.8 
  7. Unzip the contents into C:\PHP
  8. Install VC_redist.x86.exe
  9. Install MySQL 5.5.62 
  10. Open IIS as an Admin
  11. Register PHP from within IIS
  12. Reload IIS (Open IIS, Stop and Start the server)
  13. Install osTicket v1.15.8
  14. Reload IIS (Open IIS, Stop and Start the server)
  15. Go to sites -> Default -> osTicket
    Note: some extensions are not enabled, enable the extension.
  16. Rename: ost-config.php
  17. Assign Permissions: ost-config.php
  18. Continue Setting up osTicket in the browser 
  19. Download and install HeidiSQL.
  20. Continue Setting up osticket in the browser
  21. End Users osTicket URL: http ://localhost/osTicket/
  22. Clean up Delete: C:\inetpub\wwwroot\osTicket\setup
  23. Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php


Notes:

  -Browse to your help desk login page: http://localhost/osTicket/scp/login.php  
 
  -End Users osTicket URL: http://localhost/osTicket/ 


<h2>Installation Steps</h2>
Part 1 Create Virtual Machine in Azure
<p>


https://github.com/user-attachments/assets/0c017a7a-5bb0-41ec-bf47-1743c8a56554

</p>

<p>
Part 2 Installation
</p>

<br />

<p>
I will provide a Google Drive link for the next two videos to explain the upcoming steps.
https://drive.google.com/drive/folders/1VvWfzyqcGn-hb5io-XMe96ZIoksOjEDZ?usp=sharing
</p>

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
