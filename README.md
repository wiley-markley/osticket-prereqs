<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket using a manually constructed virtual machine hosted in Microsoft Azure. The project involved configuring a web server, PHP runtime, MySQL database, application dependencies, permissions, and validating the completed help desk environment.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Windows 11
- PHP
- MySQL
- HeidiSQL
- osTicket

<h2>Operating Systems Used </h2>

- Windows 11</b> (25H2)

<h2>Project Objectives</h2>

- Deploy a Windows 11 VM in Azure
- Configure IIS as a web server
- Configure PHP to run through IIS
- Deploy and configure osTicket
- Create and connect a MySQL database
- Configure required PHP extensions
- Configure application file permissions
- Validate the completed help desk environment
- Perform post-installation security cleanup

<h2>Implementation</h2>

<p>
<img width="1384" height="566" alt="image" src="https://github.com/user-attachments/assets/e511c66d-3033-469b-a5be-b94febcf0f1a" />
</p>
<p>
<b>1. Azure Infrastructure:</b> Created a Windows 11 Azure VM. Configured the VM for RDP access. Connected to and administered the VM remotely.
</p>
<br />

<p>
<img width="843" height="505" alt="image" src="https://github.com/user-attachments/assets/863f112b-5352-44e1-836d-33cf8536e9c2" />
</p>
<p>
<b>2. Web Server & Application Stack:</b> Installed IIS with CGI. Installed PHP Manager for IIS. Installed the IIS URL Rewrite Module. Installed and registered PHP. Installed the required Visual C++ runtime. Enabled required PHP extensions.
</p>
<br />

<p>
<img width="794" height="490" alt="image" src="https://github.com/user-attachments/assets/d50372a8-9b49-4a27-a174-3a7edd48a397" />
</p>
<p>
<b>3. Database Configuration:</b> Installed and configured MySQL. Used HeidiSQL to manage the MySQL environment. Created the osTicket database. Configured osTicket to communicate with the MySQL database.
</p>
<br />

<p>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efcbe896-d829-4840-bb1b-22a9eb3a1731" />
</p>
<p>
<b>4. osTicket Deployment:</b> Deployed osTicket to the IIS web root. Configured the application within IIS. Completed the osTicket web-based installation. Configured the help desk name, email settings, and database connection.
</p>
<br />
