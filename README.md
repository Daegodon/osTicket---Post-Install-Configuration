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

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Understand the difference between Admin and Agent panels
- Create custom Roles, Departments, and Teams
- Configure user access settings
- Add and manage Agents and Users
- Set SLAs and Help Topics to organize ticket routing

<h2>Configuration Steps</h2>

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Admin vs Agent Panel View"/>
</p>
<p>
<strong>Step 1: Explore the Admin vs Agent Dashboard</strong><br />
The Admin panel offers full system control, while the Agent panel provides streamlined access to ticket queues and assignments.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Create Supreme Admin Role"/>
</p>
<p>
<strong>Step 2: Create a Custom Role - "Supreme Admin"</strong><br />
Navigate to Admin → Agents → Roles and create a role with all permissions enabled to grant full administrative access.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Add SIS Admin Department"/>
</p>
<p>
<strong>Step 3: Add New Department - "SIS Admin"</strong><br />
Create a top-level department under Admin → Agents → Departments to organize tickets and teams by function.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Create Online Banking Team"/>
</p>
<p>
<strong>Step 4: Create a Team - "Online Banking"</strong><br />
Under Admin → Agents → Teams, build a new team and assign members for specialized ticket routing.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="User Access Settings"/>
</p>
<p>
<strong>Step 5: Allow Unregistered Users to Submit Tickets</strong><br />
Uncheck “Registration Required” in Admin → Settings → User Settings to let anyone submit a support ticket.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Add Agent Jane"/>
</p>
<p>
<strong>Step 6: Add Agents with Specific Roles</strong><br />
Add users like "Jane" and "John" as agents with different permissions and role access to test workflow dynamics.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Add End Users"/>
</p>
<p>
<strong>Step 7: Add Customer Users</strong><br />
From the Agent panel, navigate to Users → Add New User to simulate real end-user ticket submissions.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Configure SLA Plans"/>
</p>
<p>
<strong>Step 8: Create SLA Plans (A, B, C)</strong><br />
Use Admin → Manage → SLA to define custom SLAs with different severity levels and response windows.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Create Business Hours"/>
</p>
<p>
<strong>Step 9: Define Business Hours</strong><br />
Specify operating hours for SLA enforcement Monday through Friday in the Business Hours section.
</p>
<br />

<p>
<img src="your_screenshot_link_here" height="80%" width="80%" alt="Add Help Topics"/>
</p>
<p>
<strong>Step 10: Configure Help Topics</strong><br />
Create categorized Help Topics like "Password Reset" and "Equipment Request" to streamline ticket routing.
</p>
<br />
