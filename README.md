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

Configure:

- roles
- teams
- departments
- users
- SLA (service-level agreements)
- and ticket categorizations

<h2>Configuration Steps</h2>

<p>
<img width="701" height="387" alt="image" src="https://github.com/user-attachments/assets/7b5f3b20-df9f-4c3d-ba93-86b070efead7" />

</p>
<p>
First, I created a new role called Supreme Admin to organize and manage permissions. This was done by navigating to Admin Panel → Agents → Roles and adding a new role. The role is used to group administrative permissions for agents.
</p>
<br />

<p>
<img width="892" height="103" alt="image" src="https://github.com/user-attachments/assets/9b7b1db3-c956-4487-a343-3683c1303f1b" /> 
</p>
<p>
2. I configured Departments (Ticket Visibility) → Navigated to Admin Panel → Agents → Departments → Create department: SysAdmins.
  <p> This setup allows tickets to be routed efficiently to the right personnel.
</p>
<br />

<p>
<img width="721" height="293" alt="image" src="https://github.com/user-attachments/assets/f1516ac0-d3b0-4c09-b02f-b6dfd36ceb44" />
</p>
<p>
I configured Teams → Navigated to Admin Panel → Agents → Teams → Created team: Online Banking → Pulled agents from different departments as needed.
<p> This is to ensure tickets are accessible only to the appropriate team.
</p>
<br />
<p>
<img width="727" height="487" alt="image" src="https://github.com/user-attachments/assets/9ba9a697-9041-4ea8-9c3e-d2cb557025e0" />
</p>
<p>
Then I configured User Registration Settings (Ticket Access Control) → Navigated to Admin Panel → Settings → User Settings → Unchecked "Unregistered users can create tickets" → Require registration/login to create tickets. <p> This is so that anyone visiting the end user URL can create a ticket.
</p>
<br />

<p>
<img width="886" height="291" alt="image" src="https://github.com/user-attachments/assets/d978bb2f-a0e9-4f92-aa12-91b25e8169eb" />
</p>
<p>
I added agent accounts to handle tickets by navigating to Admin Panel → Agents and creating new agents. For example, Jane was assigned to the SysAdmins department, while John was placed in Support. Each agent was given the appropriate roles and permissions to ensure tickets are handled efficiently by the correct team.
  
</p>
<br />

<p>
<img width="888" height="351" alt="image" src="https://github.com/user-attachments/assets/40091777-fbb9-44de-9f0b-85304ea7fea7" />

</p>
<p>
I configured Users (customers) → Navigated to Agent Panel → Users → Add New.  
  <p> This allows us to create new end-users to allow them to submit tickets.
</p>
<br />

<p>
<img width="726" height="316" alt="image" src="https://github.com/user-attachments/assets/4b2317b8-e918-4502-a471-aab2db761b19" />

</p>
<p>
7. I configured SLA → Navigated to Admin Panel → Manage → SLA → Created policies: Sev-A (1 hr, 24/7), Sev-B (4 hrs, 24/7), Sev-C (8 hrs, Business Hours).
<p> This is to enforce ticket response from our agents to improve service accountability.
</p>
<br />

<p>
<img width="723" height="442" alt="image" src="https://github.com/user-attachments/assets/fc2e4a57-27e8-4e0e-86ca-cb7d8ca414b8" />

</p>
<p>
7. I configured help topics to guide users when submitting tickets by navigating to Admin Panel → Manage → Help Topics. Topics such as Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other were added. These categories help agents quickly classify tickets and improve the overall experience for end users.
</p>
<br />
