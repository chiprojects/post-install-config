<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<b>*Note*:</b> Continuation of <a href="https://github.com/chiprojects/osticket-prereqs">osTicket Installation Tutorial here</a>



<h2>Full Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/R-tf_cbDJZU?si=nkkDTfODoHuTOAJh&t=0)


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Confiugre Agents
- Configure Users

<h2>Configuration Steps</h2>

<h3>1.Enter account details for Helpdesk login page URL: http://localhost/osTicket/scp/login.php </h3> (Starts: 5:12)

[![Video Title](https://img.youtube.com/vi/R-tf_cbDJZU/0.jpg)](https://youtu.be/R-tf_cbDJZU?si=AWEroO60S1xjXcer&t=312)

<b>*Note*:</b> Notice the difference between the <b>Agent Panel</b> and <b>Admin Panel</b>. You'll know you're on the right panel view when you see the following: 

![image](https://github.com/user-attachments/assets/399aacc6-ea85-44f4-ae72-fa6f5315ca89)


<h3>2.Configure Roles</h3>
<ul>
  <li>Navigate to <b>Admin Panel</b> > <i>Agents</i> > <i>Roles</i> > <i>Add New Role</i> </li>
  <li>Name the New Role (Ex.<b>Supreme Admin</b>)</li>
  <li>Define permissions for the new agent based on the role they will have</li>
    - <b>Note:</b> For this lab, we will assign all permissions under the following tabs: <b>Tickets</b>, <b>Tasks</b>, and <b>Knowledgebase</b>
</ul>

![image](https://github.com/user-attachments/assets/0945e559-a8b1-4bed-8cf5-6ffd76ac3fc9)

![image](https://github.com/user-attachments/assets/34ee95bc-ec8b-4866-8c87-6d4c0a00fa99)

<h3>3.Configure Departments</h3>
<ul>
  <li>Navigate to <b>Admin Panel</b> > <i>Agents</i> > <i>Departments</i> > <i>Add New Department</i> </li>
  <li>Name the Department (Ex. <b>SysAdmin</b>)</li>
    - <b>Note:</b> For this lab, we will create one department, but feel free to create other departments which are used to control ticket visibility and assign responsibility.
</ul>

![image](https://github.com/user-attachments/assets/0efc9b37-308f-481d-ae6b-753a72f2ab7d)

![image](https://github.com/user-attachments/assets/e3465a64-6df7-4bba-a7cc-4f3d438d8ab8)


<h3>4.Configure Teams</h3>
<ul>
  <li>Navigate to <b>Admin Panel</b> > <i>Agents</i> > <i>Teams</i> > <i>Add New Role</i></li>
  <li>Name the Team (Ex.<b>Incident Response</b>)</li>
  <li>Define permissions for the new agent based on the role they will have</li>
    - <b>Note:</b> For this lab, we will assign all permissions under the following tabs: <b>Tickets</b>, <b>Tasks</b>, and <b>Knowledgebase</b>
</ul>

![image](https://github.com/user-attachments/assets/d29997ea-8cae-4ac6-b32f-28b0c4e1398c)

![image](https://github.com/user-attachments/assets/10688007-35ab-4b1c-8161-42a05c0f42c2)


<h3>5.Configure Settings that Allow Anyone to Create Tickets</h3>
<ul>
  <li>Navigate to <b>Admin Panel</b> > <i>Settings</i> > <i>User Settings</i></li>
  <li>Uncheck: <b>Require registration and login to create tickets</b></li>
  <li>For Registration Method: Select <b>Public - Anyone can register </b></li>
    - <b>Note:</b> When we go through the next lab: <b>Ticket Lifecycle</b>, these steps will make more sense. Essentially, we are configuring the settings so unregistered users can login and submit tickets through the help desk.
</ul>

![image](https://github.com/user-attachments/assets/22c721df-5338-43a5-b5de-05fb8a001683)








   
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
