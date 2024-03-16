<p align="center">
<img src="https://i.imgur.com/1ufljaP.png"/>
</p>

This project showcases the installation and utilization of PDQ Inventory in an existing Active Directory domain controller with one added computer. The purpose is to demonstrate the capabilities of PDQ Inventory in managing and monitoring hardware and software assets within a networked environment.

## Use Case
- PDQ Inventory is used for centralized management and monitoring of hardware and software assets in a networked environment, primarily within organizations. It automates the task of inventory tracking, making it easier for IT administrators to gather detailed information about every computer within a network. Key features include.

## Challenges
- Users need to configure it to accurately discover and communicate with all networked devices, which can be challenging, especially when dealing with different operating systems, network segments, or firewall configurations..
- PDQ Inventory's effectiveness is heavily reliant on stable network connectivity and proper network configuration.

<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to configure and use PDQ INVENTORY to monitor servers(https://youtu.be/LGjsXd10vxc)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines: Windows server 2022 and Windows 11 Pro)
- Active Directory Domain Controller
- Remote Desktop
- PDQ Inventory software

<h2>Operating Systems Used </h2>

- Windows 11 pro</b> (21H2)
- Windows server 2022

<h2>Steps</h2>

- Configure Active Directory; create a domain controller and add a user server
- Download PDQ Inventory: Download the latest version of PDQ Inventory from the official website.
- Install PDQ Inventory: Run the installer on the domain controller and follow the installation prompts.
- Configure Initial Settings: After installation, open PDQ Inventory and configure initial settings such as network discovery to recognize the domain-joined computer
  - Discover Domain Computers: Use PDQ Inventory's network discovery feature to find and add the domain-joined computer
  - Access Computer Details: Click on the added computer's name to view detailed inventory information.
- Running Tools and Commands
  - Open Tools Menu: Right-click on the computer and navigate to 'Tools'.
  - Running 'ipconfig':
      - Select 'Run Command'.
      - In the command line field, type ipconfig /all and press 'Run'
      - Review the output for both the domain controller and the added computer   



<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Active Directory; create a domain controller and add a user server.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install PDQ DEPLOY on the domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure PDQ DEPLOY: Check the PDQ Deploy Package Library for a prebuilt package.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure PDQ DEPLOY: Deploy the package to the targeted computers.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a custom deployment package: Download required software onto the DC server.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a custom deployment package: Check the PDQ Deploy Package Library to select the package and targeted computers, deploy package.
</p>
<br />

