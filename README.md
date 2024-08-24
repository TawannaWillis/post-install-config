<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This lab walks through the essential steps I took to configure osTicket into a fully functional ticketing system, ready for real-world use.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicketing System

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installing osTicket, it’s time to configure it for use as a ticketing system. You’ll be switching between the Admin and Agent panels, each with its own settings. To know which panel you’re in, just check the top right of the screen—if it says "Agent Panel," you’re in the Admin panel, and vice versa.

The first task is to create a new role called "Supreme Admin." For this lab, I’m setting up a role with full permissions, the highest level of access you can grant. Head to the Admin panel, go to the Agents menu, and click on Roles to create your new "Supreme Admin" role.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next up, we’ll create a new department specifically for System Administrators. In the Admin panel, go to the Agents menu, then click on Departments to set up this new department within osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, it's time to create a Level II Support Team to back up the existing Level I Support Team in osTicket. Head to the Admin panel, navigate to the Agents menu, and click on Teams. From there, you can easily set up the new Level II Support Team and any other teams you might need.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We need to bring in some new agents to handle the incoming tickets. To do this, go to the Admin panel, open the Agents menu, and click on "Add New Agent." Here, you’ll set up the account credentials for each agent. For this example, we’re adding Jane and John Doe to the team, ready to tackle those tickets as they come in.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We need to set up new users so they can start creating tickets for our agents to handle. To add these users, go to the Agents panel and open the Users menu. Click on "Add User" and enter the account details for each new user. In this case, we’re adding Karen and Ken, who will now be able to submit tickets into the system.
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To effectively manage tickets based on their urgency, we need to set up Service Level Agreements (SLAs). Head to the Admin panel, open the Manage menu, and click on SLA to create the necessary agreements. For this setup, we’ve defined SEV-A, SEV-B, and SEV-C to categorize tickets that need resolution within 1 hour, 4 hours, and 8 hours, respectively. This helps ensure that we address issues according to their level of impact.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, we need to set up Help Topics to guide users in choosing the right category for their issues, so agents have a clear understanding of each ticket's nature. To add new Help Topics, go to the Admin panel, open the Manage menu, and select Help Topics. Click on "Add New Help Topic" and enter the relevant topics. For this setup, I’ve added categories like Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request, which will help when creating and managing new tickets.
