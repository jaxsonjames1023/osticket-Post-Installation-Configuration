<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Department
- Teams
- Agents
- Users

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/MGTUwK1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First,  log into osTicket as an administrator.  Next, click on the agent tab and go to roles.  Then, create a supreme admin role with every permission box selected.  Once supreme admin account is setup, create a new department called Sysadmins.  The final step is setting up the teams section. 
</p>
<br />

<p>
<img src="https://i.imgur.com/rzpl0wV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, create two new agents Jane Doe and John Doe.  Jane will have sysadmin privileges, and John will have view only privileges. Next, create a user named Karen.  Finally, congfigure a SLA or service level agreement.
</p>
<br />

<p>
<img src="https://i.imgur.com/CZkzK1i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, create three separate service level agreements.  1) Sev-A will be set as one hour and schedule 24/7 2) Sev-B will be set at 4 hours and schedule 24/7  3) Sev-C will be set at 8 hours and schedule normal business hours of 8am to 5pm.
</p>
<br />
