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

- Configure all sections of the Agent and Admin Panels in osTicket

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/robertgetino/post-install-config/blob/0992bd95d93a983519443504ee8fbbe0a6d72e59/osTicket%20Roles%20%232.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/6eb7cec257d011ef37d4fe95c90bace67842c6a9/osTicket%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/74a31a1f8fc23553ffb6d14be6270713a32bef49/osTicket%20Department%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/83cfb08f883823c9a600e2916c5cfb5f050a4abf/osTicket%20Department%20%232.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/14f3b7148ddc67e299448b3217023e359555575d/osTicket%20Teams%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://i.imgur.com/DJmEXEB.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
Above, in this project, I configure the "Roles", "Departments" and "Teams" sections in the Admin Panel of osTicket. In order to do this, I begin in the "Roles" section, which is to allow grouping permissions, by going to "Admin Panel", choosing "Agents", then "Roles". I use the Main Admin as the role.
Next, I go back to the Admin Panel and to the "Departments" tab. I fill out all the necessary fields and use "SysAdmins" in this project for the department. Lastly, in the "Teams" tab, I fill out the necessary fields and use "Refund Requests" in the project and create the team.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://i.imgur.com/DJmEXEB.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the final step, I go to the Admin Panel. I then begin configuring each section in their appropriate location. I then go to Admin Panel, choose Agents then go to the following: Roles, Departments, Teams, User Settings then allow all users to create tickets, Agents (workers), SLA and then Help Topics.
</p>
<br />
