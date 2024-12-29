<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket -Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites</h2>

- Windows 10 Virtual Machine
- osTicket Installation Files

<h2>Installation Steps</h2>
<b>Step 1:</b> Download osTicket Installation Files and Unzip the Folder

![image](https://github.com/user-attachments/assets/ea509861-e3e5-4ae7-8cff-fd6ab5632f77)

<b>Step 2:</b> Install/Enable IIS In Windows with CGI

![image](https://github.com/user-attachments/assets/ff12c766-6ebd-4c0a-8be7-7b4c21a79b3d)

<b>Step 3:</b> Install PHP Manager for IIS

![image](https://github.com/user-attachments/assets/5c2f3ec6-56af-434b-9191-c83f3873014e)

<b>Step 4:</b> Install the Rewrite Module

![image](https://github.com/user-attachments/assets/5288603c-d49d-4a83-8ec1-df84683bc3e9)

<b>Step 5:</b> Create the directory C:\PHP

![image](https://github.com/user-attachments/assets/da9fbfa9-77a0-4b59-8373-f1096dd3dd78)

<b>Step 6:</b> Unzip php-7.3.8-nts-Win32-VC15-x86 into the PHP Folder Previously Created

![image](https://github.com/user-attachments/assets/388378d2-6769-4690-b306-8a602bc64767)

<b>Step 7:</b> Install VC_redist.x86.exe

![image](https://github.com/user-attachments/assets/f2220ac0-7905-4931-ba5a-53a315a01ac3)

<b>Step 8:</b> Install MySQL 5.5.62

![image](https://github.com/user-attachments/assets/04522821-8445-4565-a027-1a0cd6784e77)

<b>Step 9:</b> Open IIS as an Admin, Register PHP from within IIS

![image](https://github.com/user-attachments/assets/57dd907b-b05c-46b7-a15e-6943d3f72af7)

<b>Step 10:</b> Reload IIS (Stop and Start Server)

![image](https://github.com/user-attachments/assets/75e8a93e-44bf-415a-8e25-29e02cdd4910)

![image](https://github.com/user-attachments/assets/e6affc7b-8851-453b-aee6-f40069bf03b7)

<b>Step 11:</b> Install osTicket v1.15.8

![image](https://github.com/user-attachments/assets/60bfed21-2014-4828-ab55-f73d78a55849)

<i>Unzipping Folder</i>

![image](https://github.com/user-attachments/assets/da3c763b-beac-4472-8208-666de5940351)

<i>Copy "Upload" Folder into C:\inetpub\wwwroot</i>

![image](https://github.com/user-attachments/assets/6338f5a8-0dce-444e-a887-537c076da6e9)

<i>Within C:\inetpub\wwwroot, Rename "Upload" to osTicket</i>

<b>Step 12:</b> Enable Extensions within PHP Manager in IIS 

![image](https://github.com/user-attachments/assets/4d4375df-3507-4b0f-a445-07c7022ebbd2)

<b>Step 13:</b> Rename ost-sampleconfig.php to ost-config.php and Assign Permissions to ost-config.php

![image](https://github.com/user-attachments/assets/ff325ea2-fe09-4fac-b51f-9efd3cbddb96)

![image](https://github.com/user-attachments/assets/fcc06c5c-a83b-435e-bb5a-84e39a3ca123)

<b>Step 14:</b> Install HeidiSQL

![image](https://github.com/user-attachments/assets/0e8b1f3a-8615-474d-ac67-21e5bc6331aa)

<b>Step 15:</b> Create a New Session in HeidiSQL and Create a Database called osTicket

![image](https://github.com/user-attachments/assets/3f574b90-ab3a-4915-9fa2-bc33818c0ddf)

<b>Step 16:</b> Open osTicket

![image](https://github.com/user-attachments/assets/14c7b620-acc1-4e18-820b-98009a9c5c25)









