<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. We will configure roles, departments, teams, agents, users, SLA's, and help topics. The configurations do not cover everything that can be done in osTicket but show a handful of things that model a typical ticketing system.<br />


<h2>Prerequisites</h2>

Install osTicket [https://github.com/BrianRivera22/osticket_prereqs/]

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/1.png"/>
</p>
<p>
First, begin by making sure you are in the Admin Panel. If the top right status says "Agent Panel" then we know we are in the Admin Panel. (If you want to be in the Agent Panel, then the top right will say Admin Panel.)

Configure a role by navigating to Agents -> Roles. We can name this role "Supreme Admin". In the permissions tab, select every permission for this role. Be sure to go through every permission tab for this role. Finish by "Add Role"
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/2.png"/>
</p>
<p>
Configure departments by navigating to Agents -> Departments. Select Top Level Department and name the department System Administrators.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/3.png"/>
</p>
<p>
Configure teams by navigating to Agents -> Teams. We can name this team "Mobile Banking". After we create some agents, they can be added to this team.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/4.png"/>
</p>
<p>
Configure a few agents by navigating to Agents -> Add New. We can create a new agent and set their login credentials by clicking "set password".

We can give this agent a department and assign this agent the Supreme Admin role we created earlier. In the Permissions and Teams tab, we can give our agent all permissions and assign her to the "Mobile Banking" team.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/5(corrected).png"/>
</p>
<p>
Configure another agent and assign this agent the Support role in the Access tab with All Access. Choose what permissions he can have in the Permissions tab. I recommend giving him permissions to at least work tickets for our Ticket Life Cycle Simulation project.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/6.png"/>
</p>
<p>
Configure a few users by navigating to Agent Panel -> Users -> Add New.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/7.png"/>
</p>
<p>
Configure SLA's by navigating to Manage -> SLA

Configure a few different SLAs with various schedules and grace periods. These will be used in our Ticket Life Cycle lab to determine the urgency of various tickets.  
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/8.png"/>
</p>
<p>
Configure Help Topics by navigating to Manage -> Help Topics. Their priorities and various other items can be configured in the New ticket options tab.

Several help topics can be created.
</p>
<br />

<p>
<img src="https://github.com/BrianRivera22/post_install_config/blob/main/osTicket%20Post-Installation%20Setup/9.png"/>
</p>
<p>
A sample of various help topics.

<b>This completes our configuration lab. See the Ticket Lifecycle Simulation lab next!</b>
</p>
<br />
