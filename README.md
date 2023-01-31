# osTicket-prereqs
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

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Microsoft Azure Virtual Machine
- Install IIS 
- Create PHP File in Directory and Download PHP 
- Download MySQL and create password
- Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/EhJxlZc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Assuming that you have created an Azure Virtual Machine we will download IIS (Internet Information Services) to our Azure Virtual Machine. To do this, we will first right click on the start button, click "Run", type control and hit enter. We will then go to "programs" and click "Turn Windows features on or off." A window will then open that will look like the image above. We will find and check the box for Internet Information Services, expand it, expand "World Wide Web Services," expand "Application Development Features," and finally, check off "CGI." Click ok and the installation will proceed.  
</p>
<br />

<p>
<img src="https://i.imgur.com/RQ9XTCS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We will then install PHP manager for IIS and Rewite Module. In the meantime, we will create a new folder in the directory for PHP. We will then download PHP files, and extract the files to the new PHP folder that we created. The image above shows the files extracted to the PHP folder. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will install MySQL. Through the setup click "typical setup," and be sure that launch configuration wizard after install is checked. When the wizard opens, we will choose a standard configuration, and we will then input our password. * Be sure to write down the password somewhere
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
