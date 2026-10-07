<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
Built and deployed an osTicket help desk environment on a Windows 11 Azure VM. Configured IIS, PHP, MySQL, required application dependencies, permissions, and database connectivity, then validated the completed ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Windows 11
- PHP
- MySQL
- HeidiSQL
- osTicket

<h2>Implementation</h2>

<p>
<img width="1384" height="566" alt="image" src="https://github.com/user-attachments/assets/e511c66d-3033-469b-a5be-b94febcf0f1a" />
</p>
<p>
<b>1. Azure Infrastructure:</b> Created a Windows 11 Azure VM. Configured the VM for RDP access. Connected to and administered the VM remotely using the public IP address shown and the username and password I configured.
</p>
<br />

<p>
<img width="843" height="505" alt="image" src="https://github.com/user-attachments/assets/863f112b-5352-44e1-836d-33cf8536e9c2" />
</p>
<p>
<b>2. Web Server & Application Stack:</b> Installed IIS with CGI. Installed PHP Manager for IIS. Enabled required PHP extensions. Then, installed the IIS URL Rewrite Module. Installed and registered PHP. Installed the required Visual C++ runtime.
</p>
<br />

<p>
<img width="794" height="490" alt="image" src="https://github.com/user-attachments/assets/d50372a8-9b49-4a27-a174-3a7edd48a397" />
</p>
<p>
<b>3. Database Configuration:</b> Installed and configured MySQL. Used HeidiSQL to manage the MySQL environment. Created the osTicket database. Then, configured osTicket to communicate with the MySQL database.
</p>
<br />

<p>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/efcbe896-d829-4840-bb1b-22a9eb3a1731" />
</p>
<p>
<b>4. osTicket Deployment:</b> Deployed osTicket to the IIS web root and configured the help desk name, email settings, and database connection after configuring the application within IIS.
</p>
<br />
