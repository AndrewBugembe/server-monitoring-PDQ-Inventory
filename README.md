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
- Download PDQ Inventory.
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
<img src="https://i.imgur.com/VGhsyHW.png"/>
</p>
<p>
Configure Active Directory; create a domain controller and add a user server.
</p>
<br />

<p>
<img src="https://i.imgur.com/liZrZX1.png"/>
</p>
<p>
<img src="https://i.imgur.com/5Z9XD9s.png"/>
</p>
<p>
Download and install PDQ Inventory on the domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/hHBaWXD.png"/>
</p>
<p>
<img src="https://i.imgur.com/PU401Gy.png"/>
</p>
<p>
<img src="https://i.imgur.com/ANpYL1v.png"/>
</p>
<p>
<img src="https://i.imgur.com/I0ioLL3.png"/>
</p>
<p>
Configure Initial Settings: After installation, open PDQ Inventory and configure initial settings such as adding a domain admin user.
</p>
<br />

<p>
<img src="https://i.imgur.com/h08fDJq.png"/>
</p>
<p>
<img src="https://i.imgur.com/5YPpkoT.png"/>
</p>
<p>
<img src="https://i.imgur.com/dEgLZ2M.png"/>
</p>
<p>
Discover Domain Computers: Use PDQ Inventory's network discovery feature to find and add the domain-joined computer.
</p>
<br />

<p>
<img src="https://i.imgur.com/T3oet8i.png"/>
</p>
<p>
Access Computer Details: Click on the added computer's name to view detailed inventory information.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ik2Rlwp.png"/>
</p>
<p>
<img src="https://i.imgur.com/xFpafGx.png"/>
</p>
<p>
<img src="https://i.imgur.com/2CJWftm.png"/>
</p>
<p>
Running Tools and Commands: Open Tools Menu: Right-click on the computer and navigate to 'Tools',
Select 'Run Command', 
In the command line field, type ipconfig /all and press 'Run'
</p>
<br />

