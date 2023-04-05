# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket as an Administrator.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Osticket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure SLA's


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/Y65F5ah.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments. Some roles include 

Assign: Ability to assign tickets to agents or teams

Close: Ability to close tickets

Create: Ability to open tickets on behalf of users
</p>
<br />

<p>
<img src="https://i.imgur.com/86ND9li.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department. Some of the department settings include status, ticket assignment, and SLA's(Service Level Agreement).
</p>
<br />

<p>
<img src="https://i.imgur.com/n2WNb96.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>

SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.Once created, SLA Plans can be determined for Departments, Ticket Filters, and Help Topics. 
<p>
