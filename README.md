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
