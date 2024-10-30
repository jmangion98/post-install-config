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
1. Switching Between Admin and Agent Panels:

- Navigate between the Admin and Agent panels to access specific configuration settings. Ensure the panel label at the top right reads Agent Panel when the Admin panel is in use, and vice versa.

2. Create Supreme Admin Roles:
- Open the Admin Panel.
- Go to Agents > Roles.
- Click to Create a New Role.
- Name the role Supreme Admin and assign it all available permissions for unrestricted access.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQnl5rh.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
3. Create a System Administrators Department:

- In the Admin Panel, navigate to Agents > Departments.
- Click to Add New Department.
- Name the new department System Administrators.
</p>
<br />

<p>
<img src="https://i.imgur.com/d7WuRn8.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
4. Add a Level II Support Team:

- In the Admin Panel, go to Agents > Teams.
- Click to Add New Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/UnYyh3B.png" height="80%" width="80%" alt="Configuration Steps"/>
<img src="https://i.imgur.com/k0lElHH.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
5. Create new agents:
 -  New agents must be created to handle incoming tickets. In the Admin panel, open the Agents menu, click on Add New Agent, and create accounts for each agent (e.g., Jane and John Doe).
</p>
<br />

<p>
<img src="https://i.imgur.com/gHvbfS3.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
- New users should be created to submit tickets for agents to triage. In the Agents panel, open the Users menu, click on Add User, and set up accounts for new users (e.g., Karen and Ken).
</p>
<br />

<p>
<img src="https://i.imgur.com/pI1Cf3Q.png" height="80%" width="80%" alt="Configuration Steps"/>
</p>
<p>
6. Set Up Service Level Agreements: 
Service Level Agreements (SLAs) need to be established to categorize tickets by impact. 

  - Open the Admin Panel and navigate to Manage > SLA.
  - Define SLAs with response times to categorize ticket priority:
  - SEV-A: 1-hour response time
  - SEV-B: 4-hour response time
  - SEV-C: 8-hour response time

</p>
<br />

<p>
<img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Configuration Steps"/>
</
<p>
7. Add Help Topics:

  - Finally, create Help Topics to help users select the right category for their issues.
  - In the Admin Panel, go to Manage > Help Topics.
  - Create categories for common ticket types to guide users in selecting the correct issue type. Examples include:
  - Business Critical Outage
  -  Personal Computer Issues
  -  Equipment Reset
  - Password Request
</p>
<br />
