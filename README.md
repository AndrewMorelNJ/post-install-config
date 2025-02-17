<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- OsTicket
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- SLA Configuration
- Ticket Statuses
- Ticket Priorities
- Testing & Validation

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/8PSviRa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
</p>

<p>
<img src="https://i.imgur.com/CujKsHk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
End Users osTicket URL:
http://localhost/osTicket 
</p>

<p>
<img src="https://i.imgur.com/yngorgG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Acknowledge "Agent Panel" on the top right corner. (switches to "Admin" when clicked)
</p>

<p>
<img src="https://i.imgur.com/rtDwsDa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Acknowledge "Admin Panel" on the top right corner. (switches to "Agent" when clicked)
</p>

<p>
<img src="https://i.imgur.com/PL8vFAC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Configure Roles (for grouping permissions)
  
Click on Admin Panel, Agents, and then Roles.

Update to "Supreme Admin".
</p>

<p>
<img src="https://i.imgur.com/K6F74IY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
  
Click on Admin Panel, Agents, and then Departments.
</p>

<p>
<img src="https://i.imgur.com/378KNwN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Add new Department named "SysAdmins".
</p>

<p>
<img src="https://i.imgur.com/agwKc2h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To configure teams click on Admin Panel, Agents, and then Team. (Pull Agents from different Departments)

Change name to Online Banking.
</p>

<p>
<img src="https://i.imgur.com/Skw1NnR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Allow anyone to create tickets by clicking on Admin Panel, Settings, User Settings. 
  
(UNCHECK: unregistered users can create tickets, as highlighted above)

Registration Required: Require registration and login to create tickets. 
</p>

<p>
<img src="https://i.imgur.com/6iNokik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Configure Agents (workers)
  
Click on Admin Panel, Agents, and Add New.

<p>
<img src="https://i.imgur.com/q8j6T9x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

</p>
Add Agents: Jane (Dept: SysAdmins) & John (Dept: Support)
</p>

<p>
<img src="https://i.imgur.com/Vi37Otl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To Configure Users (customers) click on Agent Panel, Users, Add New.
</p>

<p>
<img src="https://i.imgur.com/HwEm6Tx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Add Users: Karen & Ken
</p>

<p>
<img src="https://i.imgur.com/PlMRAqJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To configure SLA click on Admin Panel, Manage, SLA
</p>

<p>
<img src="https://i.imgur.com/PlMRAqJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)

Sev-B (Grace Period: 4 hours, Schedule: 24/7)

Sev-C (Grace Period: 8 hours, Business Hours)
</p>

<p>
<img src="https://i.imgur.com/7DjgbaE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To configure Help Topics (For when users create a ticket) click on Admin Panel, Manage, and Help Topic.

Now Assign the Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
