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

- Configure Departments
- Configure Roles
- Configure Agents
- Configure Service Level Agreements(SLA)
- Configure Users (Clients)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/eP9fO1L.png" height="80%" width="80%" alt="Homepage"/>
</p>
<p>
This is the page you will see after initially logging onto the OSTicket. It will start off in the adminstration panel. As an Admin you have the options of creating departments, agents, roles, service level agreements, and user. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Zgke1qZ.png" height="80%" width="80%" alt="Creating Dept"/>
<img src="https://i.imgur.com/VELlS24.png" height="80%" width="80%" alt="Added Dept"/>
</p>
<p>
First we configured a Department called "System Adminstrations". They will be critical in managing agents and overseeing more difficult tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/RzEUEP9.png" height="80%" width="80%" alt="Agents"/>
</p>
<p>
Next we created two agents.Their names are Jane and John Doe. They will be responsible for solving any tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/N8fxdTw.png" height="80%" width="80%" alt=Users"/>
</p>
<p>
The users are the clients. They have the option of creating an account, to submit a ticket. However, they can also submit them just by adding their name and selecting an help topic.
</p>
<br />

<p>
<img src="https://i.imgur.com/OeeVug7.png" height="80%" width="80%" alt="SLA"/>
</p>
<p>
The SLA is a system that lets the agents know how much time the have to solve a ticket. In this portion we set up three types of service level agreements. The are named "Sev-A", "Sev-B", and "Sev-C". They have different grace periods and are used to classify the severity of a ticket. Each SLA is set up and maintained through the admin panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/7B7617l.png" height="80%" width="80%" alt=Help Topics"/>
</p>
<p>
In this section, I created five new help topics. They are "Password Reset", "Equipment Request", "Business Critical Outage"
and "Personal Computer Issues". These options give agents a sense of how urgent a ticket may be. Also, it allows for better orginaztion and communication amongst team members.
</p>
<br />
