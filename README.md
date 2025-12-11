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

- Windows 11</b> 

<h2>Post-Install Configuration Objectives</h2>

- Understand the difference between the Agent panel and Admin panel 
- Create Agents
- Create Roles
- Create Departments and Teams 
- Create Help Topics and SLA's 

<h2>Admin Panel vs Agent Panel</h2>

<p>
<img width="1913" height="1005" alt="admin login screen" src="https://github.com/user-attachments/assets/ef6f08b9-a81c-4f03-80d7-e995b66ef4eb" /> 
</p>
<p>
The first thing that we will do is Login in with the username and password we created when we installed OsTicket. This will take us to the admin panel.
</p>
<br />

<p>
<img width="999" height="953" alt="admin panel" src="https://github.com/user-attachments/assets/f29c47ca-8d8e-4f0f-b45f-54e73e248823" />
</p>
<p>
The admin panel is were we will configure settings for OsTicket, such as creating agents, editing SLA's, making departments, etc.
</p>
<br />  

<p>
<img width="1919" height="1040" alt="agent panel" src="https://github.com/user-attachments/assets/2869bfc9-dba4-4620-b25c-c86fc385857f" />
</p>
<p>
The Agent panel is for agents to work on the actual tickets, like a sysadmin wokring on a ticket for the network being down.
</p>
<br />  


<h2>Creating Agents</h2>

<p>
<img width="982" height="539" alt="agents " src="https://github.com/user-attachments/assets/13c6967e-338e-4d09-a4c3-494b595352d7" />
</p>
<p>
To create a new agent, go to admin panel > agents > create > "Add New Agent".
</p> 
<br /> 

<p>
<img width="1084" height="743" alt="creating a user" src="https://github.com/user-attachments/assets/d4287a64-1949-452d-bc37-8a00f9108265" />
</p>
<p>
From there, we can fill in an agent's info. We can also assign them a role, department and  a team. We can also assign them a password or send them an email to create their own password/
</p>
<br /> 

<p>
<img width="1025" height="508" alt="agents created " src="https://github.com/user-attachments/assets/d9b0fa7e-38f9-4f0c-9c9a-9387be39cf02" />
</p>
<p>
We can go back to admin panel > agents to see that our agent was created. 
</p>
<br /> 

<h2>Roles</h2>  

<p>
<img width="983" height="688" alt="roles" src="https://github.com/user-attachments/assets/9752f90b-9ce8-4e58-8acd-875e431bf24c" />
</p>
<p>
Roles are grouped permissions you can give to agents. You can see the roles that you currently have by going to admin panel > agents > roles. You can create a new role by clicking "Add New Role" role.
</p>
<br />  

<h2>Departments</h2>  

<p>
<img width="997" height="529" alt="departments " src="https://github.com/user-attachments/assets/472d0b8b-2abf-4728-9698-cd46507d60bf" />
</p>
<p>
A department is a grouping of agents that determines what tickets they will receive. For example, sysadmins will receive sysadmin tickets while people in Help Desk will receive help desk tickets. You can veiw what departments you have by going to admin panel > agents > departments.
</p>
<br />  

<p>
<img width="1035" height="916" alt="creating a department " src="https://github.com/user-attachments/assets/adfeee12-db69-4ed2-89e5-40a2175aba7a" />
</p>
<p>
You can create a new department by clicking "Add New Department".
</p>
<br />  

<p>
<img width="1016" height="615" alt="department created " src="https://github.com/user-attachments/assets/7cfde6db-9879-4ac7-bc33-957b03beb94b" />
</p>
<p>
Once you created a department you can see it on admin panel > agents> departments.
</p>
<br />  

<h2>Teams</h2>  

<p>
<img width="991" height="480" alt="teams" src="https://github.com/user-attachments/assets/1832b659-46b2-476c-a4d3-1b968fde620d" />
</p>
<p>
A team is made up of agents from different departments. This is helpful, beaucse you can make a team made up of people with different skills that is focused on one thing, like an online banking app the company uses. You can see what teams you have by going to admin panel > agents > teams.
</p>
<br />  

<p>
<img width="986" height="758" alt="creating a team" src="https://github.com/user-attachments/assets/2942d424-6f00-421f-986d-50328274dc64" />
</p>
<p>
You can create a new team by clicking " Add New Team"
</p>
<br />  

<p>
<img width="993" height="789" alt="team created" src="https://github.com/user-attachments/assets/9e233c49-8bc9-44eb-bff2-5fd85270f14a" />
</p>
<p>
Once you created a team you can see it on admin panel > agents > teams.
</p>
<br />  

<h2>Help Topics</h2>  

<p>
<img width="1042" height="591" alt="help topics " src="https://github.com/user-attachments/assets/9b11b177-5c76-4f68-8e21-92a01d93ef7c" />
</p>
<p>
When users make a ticket, they can select a help topic to classify their ticket. You can have a help topic called "forgot password" for example. You can veiw what help topics you have by going to admin panel > manage > help topics.
</p>
<br />  

<p>
<img width="1044" height="759" alt="help topic " src="https://github.com/user-attachments/assets/32055f48-3c64-43cf-b2b6-8b27a25b4417" />
</p>
<p>
You can create a new help topic by clicking " Add New Help Topic".
</p>
<br />  

<p>
<img width="1068" height="676" alt="help topic added" src="https://github.com/user-attachments/assets/5bd97014-3d79-4951-8ddb-50627a222ece" />
</p>
<p>
Once you created a help topic you can see it on admin panel > manage > help topics.
</p>
<br />  

<h2>SLA</h2>  

<p>
<img width="1075" height="531" alt="SLA" src="https://github.com/user-attachments/assets/168d479a-5d2c-4034-949c-81e64b7ceef0" />
</p>
<p>
An SLA is a service level agreement. It is a set of rules for how a ticket should be done, like how long it should take to be completed. You can view what SLA's you have by going to admin panel > manage > SLA's.
</p>
<br />  

<p>
<img width="997" height="833" alt="creating SLA" src="https://github.com/user-attachments/assets/d1cdeb0f-5f58-472b-b3da-94d87375ff25" />
</p>
<p>
You can create a new SLA by clicking "Add New SLA". You can set things like how long the ticket should take to be completed and when people are available to work on it. SLA's differ based on how serious a ticket is. 
</p>
<br />  

<p>
<img width="994" height="540" alt="SLA created" src="https://github.com/user-attachments/assets/f81e34cb-f866-4168-aa22-ff93225d33e8" />
</p>
<p>
Once you created a SLA you can see it on admin panel > manage > SLA's.
</p>
<br /> 



