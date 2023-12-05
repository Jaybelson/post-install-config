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

- Configure Roles
- Configure Departments 
- Configure Teams
- Configure Ticket Allowance 
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="1065" alt="Screen Shot 2023-12-05 at 12 20 10 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/71be8877-ed81-474d-99fd-bc871e555b94">
<img width="1039" alt="Screen Shot 2023-12-05 at 12 29 12 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/ad56d328-692a-43c3-a4d3-20f446f441ad">
<img width="978" alt="Screen Shot 2023-12-05 at 12 31 25 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/10c5972f-63a2-421c-817c-c4c361b3b69b">
<img width="1027" alt="Screen Shot 2023-12-05 at 12 37 08 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/da772dea-af4e-4838-a241-0400c1040dfb">


1. Configure Roles:
   
Admin Panel -> Agents -> Roles:

Create a New role: Ex: Supreme Admin

Select Permission of choice and then click "Add Role"
</p>
<br />

<p>
<img width="1021" alt="Screen Shot 2023-12-05 at 12 48 00 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/f090ed23-e544-4d09-9797-5f4de43a35f4">
<img width="1067" alt="Screen Shot 2023-12-05 at 12 53 42 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/707305da-387e-42c5-9817-35fdf395bd43">
<img width="1080" alt="Screen Shot 2023-12-05 at 12 53 51 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/240873a0-e23e-4ab6-87ef-dedda2c9dcf4">

2. Configure Departments:
   
Admin Panel -> Agents -> Departments

Name New Department. Ex: System Administrators

Scroll down and select Create Dept.


</p>
<br />

<p>
<img width="1043" alt="Screen Shot 2023-12-05 at 12 59 53 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/f53748b6-49b4-4188-9e72-dbe91ae13a9a">
<img width="941" alt="Screen Shot 2023-12-05 at 1 00 43 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/a08c624f-6924-41b5-bf58-26da0589cc70">
<img width="1024" alt="Screen Shot 2023-12-05 at 1 00 53 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/7d9a6477-6ea9-49b8-9544-a214f97ad969">

3. Configure Teams:

Admin Panel -> Agents -> Teams

Create a new Team. Ex: Level II Support

Click on Members and add members to the team. Then select "Create Team"

</p>
<br />
<img width="1036" alt="Screen Shot 2023-12-05 at 1 13 35 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/195d06dd-34f1-46bd-aa4e-9cfddff1cedb">

4. Allow anyone to create tickets:

Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets 

Note: This is only used to give anonymous users access to osTicket.

<img width="1014" alt="Screen Shot 2023-12-05 at 1 27 21 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/a874e118-b954-463a-a41f-6bdefeb277ee">
<img width="967" alt="Screen Shot 2023-12-05 at 1 30 02 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/6901dc37-bb46-4677-8b0e-8984ba2d173a">
<img width="1061" alt="Screen Shot 2023-12-05 at 1 29 38 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/3550417d-ce40-40b8-9fc6-29c4c94e30d4">
<img width="1027" alt="Screen Shot 2023-12-05 at 1 32 06 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/36b3f5be-368e-46e3-a831-f1aaf4243e52">
<img width="1043" alt="Screen Shot 2023-12-05 at 1 32 24 AM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/36b07fbf-72a9-48f9-b1b4-d93fcdbefad3">

5. Configure Agents (workers):
   
Admin Panel -> Agents -> Add New

Fill out New Agents credentials Ex: Jane Doe

To set Password for Agent: Set Password -> uncheck " Send agent a reset email." Create a Password for the Agent and click "Set"

Then provide any access to New agent 

Next, under the Permissions tab assign permissions to agent.

Lastly, under the Teams tab assign a Dedicated team for the agent. Then click "Create" 

<img width="1007" alt="Screen Shot 2023-12-05 at 1 28 34 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/a8a3cbbc-cab7-4248-8e70-aaf39b6d728f">
<img width="1139" alt="Screen Shot 2023-12-05 at 1 31 33 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/79ac5171-28a8-4fb0-9d4c-f4e73f806844">

6. Configure Users (customers):
   
Agent Panel -> Users -> Add New

Create a new user with their credentials. Ex: Karen

Then click "Add User"

<img width="1066" alt="Screen Shot 2023-12-05 at 1 39 36 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/3cc51b33-e898-485a-b862-ce9b6e4b9099">
<img width="881" alt="Screen Shot 2023-12-05 at 1 42 21 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/6975642f-7722-4084-bd56-2dfaafc69a58">
<img width="861" alt="Screen Shot 2023-12-05 at 1 45 35 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/cac4427e-a632-46c0-934d-bbb1c6dcfdf3">
<img width="868" alt="Screen Shot 2023-12-05 at 1 46 49 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/47cefe8b-318d-46c3-9893-110744eb2d58">

7.Configure SLA:

Admin Panel -> Manage -> SLA

Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

<img width="916" alt="Screen Shot 2023-12-05 at 1 53 02 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/c9a18873-34f4-46a4-9a83-f7a47110c9e6">
<img width="876" alt="Screen Shot 2023-12-05 at 1 54 11 PM" src="https://github.com/Jaybelson/post-install-config/assets/146674787/49b45032-c90c-4641-af6a-6bab5992819e">

8. Configure Help Topics:
   
Admin Panel -> Manage -> Help Topics

Create Help Topics.

Examples:
Business Critical Outage,
Personal Computer Issues,
Equipment Request,
Password Reset.

Note: Notes could be added for better Clarification.

When complete  Click "Add Topic"
