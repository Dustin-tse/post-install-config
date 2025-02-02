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

<h2>Configuration Steps</h2>
<h2>1. Configuring Roles and Departments</h2>
<p>
<img src="https://i.imgur.com/EFEQkvl.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/LUCp2pW.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
I started off by logining into the agent portal using an admin account that gave access to the admin panel I can use to configure my help desk system. Afterwards I started by adding new roles, in this case I created a "supreme admin" role which allows the user with the role all permissions. I then configured and created a new "SysAdmins" department which will be a top level department and a tier above the other departments.
</p>
<br />

<h2>2. Configuring Agnets(workers) and Users(customers)</h2>
<p>
<img src="https://i.imgur.com/bPzy41K.png" height="40%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/hjYd6FM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
I moved onto the Agents and Users next. Starting with the agents I created two new agents, with basic names like Jane and John and added them to different departments, Jane got system admin and John was placed into Support. I then created two users named "Ken" and "Karen" who will act as real customers creating tickets for agents like John and Jane to work through.
</p>
<br />

<h2>3. Configuring SLAs and Help Topics</h2>
<p>
<img src="https://i.imgur.com/iCxuCrq.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/2LQ7Rtj.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
For this last part I configured SLAs (service level agreements). I created three new SLAs starting with one urgent at sev-A and one more relaxed at sev-C for example. I also implimented new "Help topics" which are just different types of issues a user like Ken and Karen can report using the ticket creation website.
</p>
<br />
