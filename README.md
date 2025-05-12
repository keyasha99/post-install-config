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

- Configure roles for grouping permissions
- Set up departments for ticket visibilities
- Create teams using agents from different departments
- Ensure that anyone can create tickets
- Create both agents (workers) and users (customers)
- Configure SLA plans for tickets
- Create help topics for when users create a ticket

<h2>Configuration Steps</h2>

<h3>Roles</h3>

<p>
<img src="https://i.imgur.com/Tnzw365.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Right where it says Welcome (your name), click on Admin Panel to switch over to the Administration Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/53Sn3bA.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Navigate to the Agents tab and then Roles underneath.
</p>
<br />

<p>
<img src="https://i.imgur.com/JRJnVHW.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Go to Add New Role.
</p>
<br />

<p>
<img src="https://i.imgur.com/CcRyWQ8.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Here, I named the role Sumpreme Admin. You can name it anything you want.
</p>
<br />

<p>
<img src="https://i.imgur.com/AThYJv3.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Go over to the Permissions tab to ensure that all of the permissions are checked off. Then click Add Role.
</p>
<br />

<h3>Departments</h3>

<p>
<img src="https://i.imgur.com/pCo53zI.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
To create a new department, go back to the Agents tab and then Departments. Go to Add New Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/CBXg50O.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
For the Parent field, select Top Level Department. For Name, enter any name that you want. You can also change the other things to your liking. If you're just following along with this tutorial, leave everything else how it is. Scroll down and click Create Dept.
</p>
<br />

<h3>Teams</h3>
<p>
<img src="https://i.imgur.com/19Lfr1Z.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Navigate to the Teams underneath the Agents tab to create a new team. Go to Add New Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/9EHVHKW.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Name your team and create it.
</p>
<br />

<h3>Allowance to Create Tickets</h3>

<p>
<img src="https://i.imgur.com/h1870m3.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
This step is to ensure that anyone is allowed to make tickets. Go to Settings and then Users. Make sure that the box next to "Require registration and login to create tickets" is unchecked.
</p>
<br />

<h3>Agents</h3>

<p>
<img src="https://i.imgur.com/yCUdiq5.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
To create agents, go to Agents underneath Agents and go to Add New Agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/2sPxRDM.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Fill out the name, email address, and username for your agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/I3nn5Z4.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
You can send your agent a password reset email if you like. For this tutorial, I unchecked the box and created a password for my agent.
</p>
<br />

<p>
<img src="https://i.imgur.com/GbN4WML.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
In the Access tab, I assigned Jane to the SysAdmin department with the role of Supreme Admin. 
</p>
<br />

<p>
<img src="https://i.imgur.com/dhdHyRU.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
For Teams, I assigned Jane to the Online Banking team. Once you're done, click Create.
</p>
<br />

<p>
<img src="https://i.imgur.com/pSw86Sh.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Here, I created another agent named John.
</p>
<br />

<p>
<img src="https://i.imgur.com/axBKi7c.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
For access, I assigned John to the Support department with the role of View Only.
</p>
<br />

<h3>Users</h3>

<p>
<img src="https://i.imgur.com/kYpvgD6.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Now to create users, you need to switch over to the Agent Panel. You will find it up at the top where Welcome (your name) is located.
</p>
<br />

<p>
<img src="https://i.imgur.com/IEloeb3.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Go to Users and click on Add User.
</p>
<br />

<p>
<img src="https://i.imgur.com/QP2c5aX.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Fill out the email address and full name and create your user. 
</p>
<br />

<h3>SLA</h3>

<p>
<img src="https://i.imgur.com/GiYYNYw.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
To create SLAs for your tickets, switch back to the Admin Panel. Go to Manage and then SLA. Click on Add New SLA Plan.
</p>
<br />

<p>
<img src="https://i.imgur.com/iZk8phe.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
Here I created a SLA Plan for high priority tickets. I set the grace period to 1 hour and the schedule to 24/7. I've created two more SLA plans. Sev-B (Grace Period: 4 hours, Schedule: 24/7) and Sev-C (Grace Period: 8 hours, Business Hours).
</p>
<br />

<h3>Help Topics</h3>

<p>
<img src="https://i.imgur.com/CtSWCXG.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
To create help topics of your own, go to Help Topics underneath the Manage tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/F4Aj7P0.png" height="80%" width="80%" alt="osTicket Post"/>
</p>
<p>
I created a Help Topic for Business Critical Outage and set the Parent Topic to Report a Problem. I've also created Personal Computer Issues (Parent Topic: Report a Problem), Equipment Request (Parent Topic: General Inquiry), Password Reset (Parent Topic: Report a Problem), and Other (Parent Topic: General Inquiry).
</p>
<br />
