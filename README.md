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

- Install / Enable IIS in Windows
- Install Web Platefoam Installer
- Install osTicket v1.15.8
- Download and Install Heidi SQL


<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/76a01076-1603-4974-8c8d-7137f2c68fa0)

IIS is a flexible, secure web server software and is primarily used to host and serve web applications, websites as well as supports various protocols allowing deployment of ASP.NET applcations and static content. The picture above demonstrates me installing IIS on Windows Machine.

![image](https://github.com/user-attachments/assets/c2020d28-20f6-4e3e-b1d9-f146e3209bec)

A valuable tool for developers and administrators, the rewrite manager in IIS is used for URL rewriting, SEO optimization, rule configuration and managing redirects. Here is a demonstration of me downloading and installing manager on Windows Machine.

![image](https://github.com/user-attachments/assets/67864ce8-3949-4ca9-9132-616fc1011367)

Download and install MySQL 5.5.62 from the installation files. Launch the configuration wizard after the installation. Ensure that you select standard configuration and the then select install as window Service. Must ensure that launch the MySQL server is checked. Now we will put in our credenitals. 


![image](https://github.com/user-attachments/assets/2c42eab5-5751-446d-97da-22339d94b322)

We will need to download and install HeidiSQL from the installation files and create new session. Once connected we will go back to browser and finsh setting up. Under the database settings within the browser, we will utilize given username and password.

Now creating a new database in HeidiSQL. Right click where it says "unnamed", select "create new" then select "database". Name this database "osTicket." We will then go back to osTicket browser and type in osTicket under the MySQL database. 

![image](https://github.com/user-attachments/assets/351eef85-a384-474d-87eb-119c7a648c9d)

After installing and downloading all the appropriate applications, you should now be able to utilize osTicket System !!
