<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This lab demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/S33TPEZ.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/7HyoONM.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
After installing osTicket, it's time to configure it as a ticketing system. Note that I switch between the Admin and Agent panels, indicated at the top right of the screen; if it says "Agent Panel," then the Admin panel is in use, and vice versa.

First, create a new role called Supreme Admin, which will have all permissions. To do this, open the Admin panel, navigate to the Agents Menu, click on Roles, and create the new role.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQnl5rh.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Next, a new Department will be created for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/d7WuRn8.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
A Level II Support Team needs to be created to complement the existing Level I Support Team. In the Admin panel, go to the Agents menu, click on Teams, and add the new team.
</p>
<br />

<p>
<img src="https://i.imgur.com/UnYyh3B.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/k0lElHH.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
New agents must be created to handle incoming tickets. In the Admin panel, open the Agents menu, click on Add New Agent, and create accounts for each agent (e.g., Jane and John Doe).
</p>
<br />

<p>
<img src="https://i.imgur.com/gHvbfS3.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
New users should be created to submit tickets for agents to triage. In the Agents panel, open the Users menu, click on Add User, and set up accounts for new users (e.g., Karen and Ken).
</p>
<br />

<p>
<img src="https://i.imgur.com/pI1Cf3Q.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Service Level Agreements (SLAs) need to be established to categorize tickets by impact. In the Admin panel, open the Manage menu, click on SLA, and create the necessary SLAs (e.g., SEV-A, B, and C for 1, 4, and 8 hours, respectively).
</p>
<br />

<p>
<img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
Finally, create Help Topics to help users select the right category for their issues. In the Admin panel, open the Manage menu, click on Help Topics, and add new topics (e.g., Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request).
</p>
<br />
