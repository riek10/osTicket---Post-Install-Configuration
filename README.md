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
- Departments
- Teams
- Agents,Users
- SLA/Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/e1a7e145-af1b-4079-b135-ebabe2181f6c" height="80%" width="80%"/>
</p>
<p>
After completing the installtion and base configuration of OsTicket i decided to document a brief tutorial setting up ticketing agents/users/and departments. First i configured the roles of my admin users and set them to Supreme Admin basically allowing all permissions to create,delete,edit, and resolve all tickets and issues among employees and end users.  
</p>
<br />

<p>
<img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/bdd08e29-3235-4bb3-a5f1-173b161c101b" height="80%" width="80%"/>
</p>
<p>
Next i created the System Administration department for the agents with elevated privelages. Agents in this department are responsible for maintaining superb client experiences and resolving support tickets in a timely manner.
</p>
<br />

<p>
<img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/a780d3a4-f92a-4113-a88d-cf1eb754428b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then added a Level 2 support team to handle the more difficult tickets that come through.Any issues Level 1 support cant handle will be upgraded and passed along to Level 2.  
</p>

<p>
  <img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/c0a37c44-d820-4576-84d1-6fcdacfd028b" height="50%" width="50%"/>
</p>
<p>
  <img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/44acafdd-0aed-481a-933c-4aa6fa7a3c89" height="50%" width="50%"/>
</p>
<P>
  In order to create tickets and have those tickets reviewed and taken care of i created a few agents and users to thoroughly test the ticketing system.
</P>
<br />

<p>
  <img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/e86052a3-9d8d-480a-89f1-a20b16fb904a" height="50%" width="50%"/>
</p>
<P>
  <img src="https://github.com/riek10/osTicket---Post-Install-Configuration/assets/113129662/1761c5c1-094d-4b06-a53a-1743f5818c5b" heght="50%" width="50%">
</P>
<p>
  The last step in setting up the functionality portion of the ticketing system was creating the SLA which is the timetable each ticket is expected to be viewed,resolved, and closed. I also created a few different help topics that endusers and employees can select to assure their tickets are sent to the correct department and taken care of in a timely manner with no confusion.
</p>
