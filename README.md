<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2>osTicket Main Configuration<h2/>
In this tutorial I go through the steps to configure and setup osTicket after installation in the previous tutorial
<br />
<br />

<h2>Technologies and Environments Used<h2/>

- PHP 
- osTicket (Help Desk Ticketing System)
<br />
<br />


<h2>Main Steps<h2/>

Step 1. Configure roles in the admin panel.
Go to:
- Admin Panel -> Agents -> Roles
- For testing purposes create the role: Supreme Admin and assign permissions

<p align="center">
<a href="https://imgur.com/RldeMgt"><img src="https://i.imgur.com/RldeMgt.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

1b.
<p align="center">
<a href="https://imgur.com/V83daYp"><img src="https://i.imgur.com/V83daYp.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

1c.
<p align="center">
<a href="https://imgur.com/wDqqop0"><img src="https://i.imgur.com/wDqqop0.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

1d.
<p align="center">
<a href="https://imgur.com/2tuHW92"><img src="https://i.imgur.com/2tuHW92.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

1e.
<p align="center">
<a href="https://imgur.com/JVLz8CO"><img src="https://i.imgur.com/JVLz8CO.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

Step 2. Configure the Departments
- Admin Panel -> Agents -> Departments
- For testing purposes create the department: System Administrators  

<p align="center">
<a href="https://imgur.com/x7I6dNh"><img src="https://i.imgur.com/x7I6dNh.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

2b. 
<p align="center">
<a href="https://imgur.com/kIPlURO"><img src="https://i.imgur.com/kIPlURO.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />


Step 3. Configure Teams
- Admin Panel -> Agents -> Teams
- For the purposes of testing create two teams (Level I Support, Level II Support)

<p align="center">
<a href="https://imgur.com/U8TlTzl"><img src="https://i.imgur.com/U8TlTzl.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

3b.
<p align="center">
<a href="https://imgur.com/RIJUFcy"><img src="https://i.imgur.com/RIJUFcy.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

3c. Add a member to the team
<p align="center">
<a href="https://imgur.com/qksv3ML"><img src="https://i.imgur.com/qksv3ML.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

3d. Teams Created
<p align="center">
<a href="https://imgur.com/sTX5ffw"><img src="https://i.imgur.com/sTX5ffw.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


Step 4. Allow anyone to create tickets. Go to:
- Admin Panel -> Settings -> User Settings
- Registration Required: Require registration and login to create tickets

<p align="center">
<a href="https://imgur.com/RgyYLqZ"><img src="https://i.imgur.com/RgyYLqZ.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />


Step 5. Configure Agents (Workers who will work the tickets). Go to:
- Admin Panel -> Agents -> Add New
- (Whatever names you choose)          

<p align="center">
<a href="https://imgur.com/xP0GuqT"><img src="https://i.imgur.com/xP0GuqT.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />


5b. Set the agent password

<p align="center">
<a href="https://imgur.com/3wXnWR1"><img src="https://i.imgur.com/3wXnWR1.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

5c. Set the department for the agent

<p align="center">
<a href="https://imgur.com/w7RUHd5"><img src="https://i.imgur.com/w7RUHd5.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

5d. Set the permissions for the new agent 

<p align="center">
<a href="https://imgur.com/a9MMvj8"><img src="https://i.imgur.com/a9MMvj8.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

5e. Set the team for the new agent 

<p align="center">
<a href="https://imgur.com/ZOk5w5V"><img src="https://i.imgur.com/ZOk5w5V.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

5f. New agent has been created

<p align="center">
<a href="https://imgur.com/WMrSFqH"><img src="https://i.imgur.com/WMrSFqH.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

Step 6. Go the the agent panel and create new user (Customers who can create a service ticket request). Go to:
- Agent Panel -> Users -> Add New
- For the purposes of testing create two users (whatever names you choose)

<p align="center">
<a href="https://imgur.com/GIB8Ok0"><img src="https://i.imgur.com/GIB8Ok0.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

6b. Enter the details of the new user

<p align="center">
<a href="https://imgur.com/qevnb3Q"><img src="https://i.imgur.com/qevnb3Q.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


6c. New user has been created

<p align="center">
<a href="https://imgur.com/hWuyJKD"><img src="https://i.imgur.com/hWuyJKD.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


6d. Register the new user

<p align="center">
<a href="https://imgur.com/q1yvGTL"><img src="https://i.imgur.com/q1yvGTL.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


Step 7. Configure SLA (Service Level Agreements)
- Admin Panel -> Manage -> SLA
- For the purposes of testing configure three
 - Sev-A (1 hour, 24/7)
 - Sev-B (4 hours, 24/7)
 - Sev-C (8 hours, business hours)

<p align="center">
<a href="https://imgur.com/RldeMgt"><img src="https://i.imgur.com/RldeMgt.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

7b. Give the plan a name and set the schedule

<p align="center">
<a href="https://imgur.com/EBgAa6T"><img src="https://i.imgur.com/EBgAa6T.jpg" title="source: imgur.com" /></a>
</p>
<br />
<br />

7c. SLA Plans Created 

<p align="center">
<a href="https://imgur.com/U89MrT3"><img src="https://i.imgur.com/U89MrT3.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


Step 8. Configure Help Topics
- Admin Panel -> Manage -> Help Topics
- For the purposes of testing create four topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset

<p align="center">
<a href="https://imgur.com/RhomVnS"><img src="https://i.imgur.com/RhomVnS.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

8b. Set the help topic details (Name, Status, Parent Topic)

<p align="center">
<a href="https://imgur.com/BRkDjLQ"><img src="https://i.imgur.com/BRkDjLQ.png" title="source: imgur.com" /></a>
</p>
<br />
<br />

8c. Next, set the ticket options for the created help topic (department, status, priority, SLA plan, team assignment)

<p align="center">
<a href="https://imgur.com/lgEWgJH"><img src="https://i.imgur.com/lgEWgJH.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


8d. Help Topics Have Been Created

<p align="center">
<a href="https://imgur.com/qL2zlG8"><img src="https://i.imgur.com/qL2zlG8.png" title="source: imgur.com" /></a>
</p>
<br />
<br />


For the the next tutorial in this series go <a href=https://github.com/tarronacuff/osTicket-Ticket-operations-Examples>here</a></h2>
<br />
Thank Your for reading!
