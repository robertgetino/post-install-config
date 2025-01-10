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
<img src="https://github.com/robertgetino/post-install-config/blob/0992bd95d93a983519443504ee8fbbe0a6d72e59/osTicket%20Roles%20%232.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/6eb7cec257d011ef37d4fe95c90bace67842c6a9/osTicket%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/74a31a1f8fc23553ffb6d14be6270713a32bef49/osTicket%20Department%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/83cfb08f883823c9a600e2916c5cfb5f050a4abf/osTicket%20Department%20%232.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/14f3b7148ddc67e299448b3217023e359555575d/osTicket%20Teams%20%231.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/82f21859c46443c0acbca327e324b1bb9d27b4a4/osTicket%20Teams%20%232.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this project, I configure the "Roles", "Departments" and "Teams" sections in the Admin Panel of osTicket. In order to do this, I begin in the "Roles" section, which is to allow grouping permissions, by going to "Admin Panel", choosing "Agents", then "Roles". I use the Main Admin as the role.
Next, I go back to the Admin Panel and to the "Departments" tab. I fill out all the necessary fields and use "SysAdmins" in this project for the department. Lastly, in the "Teams" tab, I fill out the necessary fields and use "Refund Requests" in the project and create the team.
</p>
<br />

<p>
<img src="https://github.com/robertgetino/post-install-config/blob/7f1cef2e775d50b07f064e6e5b3e686758b36e70/osTicket%20Agents.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/e69ca36707ab1bb0263488a2f99231075ba70e0c/osTicket%20User.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/093df23a31f219a66acd67b45b626d4ec97c25a6/osTicket%20SLA.png" height="45%" width="45%" alt="Disk Sanitization Steps"> <img src="https://github.com/robertgetino/post-install-config/blob/5ae215b8e71b2dd5114b7ee8ec741e0ec0c4eedf/osTicket%20Help%20Topics.png" height="45%" width="45%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the next steps, I am still remaining on the "Admin" Panel in order to add workers (help desk/service desk agents) in the Agents tab. I navigate to there, add the names Jane Smith and John Smith, both who have different department roles and permissions. After that, I have to add customers in this project, therefore, I go to the "Agents" Panel and click on Users, then add a name, which in this case, is Karen.
  Thirdly, I go back to the "Admin" Panel and go to Manage then SLA, in order to write SLAs (Service Level Agreement). I add one SLA named Sev-A (for urgent tickets) which has a grace period of 1 hour and a schedule of 24/7. The next one is Sev-B (for medium urgent tickets) and its grace period is 4 hours and 24/7 schedule. The last SLA is Sev-C (for low urgent tickets) which has a grace period of 8 hours and is set to only the business hours of the help desk department.
  Lastly, I'll create Help Topics by remaining on the Admin Panel, then Manage and Help Topics. I'll then add Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset and Other.
</p>
<br />
