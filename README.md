<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for business use
- Configure Departments 
- Configure Teams
- Configure Agents (workers)
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
<h2>Step</h2>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles, Departments, and Teams
Roles: Define permissions for agents.

Navigate to Admin Panel -> Agents -> Roles.
Example Role: Supreme Admin (highest permissions).
Departments: Control ticket visibility based on teams (e.g., SysAdmins, Networking).

Navigate to Admin Panel -> Agents -> Departments.
Example Department: SysAdmins.
Teams: Group agents from different departments.

Navigate to Admin Panel -> Agents -> Teams.
Example Team: Online Banking (includes agents from multiple departments).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Add Agents and Users
Configure staff responsible for resolving tickets.

Go to Admin Panel -> Agents -> Add New.
Example:
Jane (Dept: SysAdmins).
John (Dept: Support).
Users: Add customers or end-users.

Go to Agent Panel -> Users -> Add New.
Example:
Karen (customer).
Ken (customer).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA Policies and Help Topics
SLA (Service Level Agreement):

Define ticket response time commitments.
Navigate to Admin Panel -> Manage -> SLA.
Examples:
Sev-A: Grace Period: 1 hour (24/7 support).
Sev-B: Grace Period: 4 hours (24/7 support).
Sev-C: Grace Period: 8 hours (business hours).
Help Topics: Simplify ticket categorization for users.

Navigate to Admin Panel -> Manage -> Help Topics.
Examples:
Business Critical Outage.
Personal Computer Issues.
Equipment Request.
Password Reset.
Other.

</p>
<br />

<p>
  <img src="" height="80" width="80" alt="Disk Sanitization Steps"/>
<p>
Ticket Configuration
Allow Ticket Creation:
Go to Admin Panel -> Settings -> User Settings.
Options:
Allow unregistered users to create tickets (Default: Checked).
Require registration and login to create tickets (Uncheck this for public ticket submissions).
</p>

</p>
