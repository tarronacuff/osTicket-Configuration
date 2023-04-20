<p align="center">
<img src="https://imgur.com/GtGHaCx.png alt="Traffic Examination"/>
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
<img src="https://imgur.com/hnfzWmF.png alt="Traffic Examination"/>
</p>
<br />
<br />

1b.
<p align="center">
<img src="https://imgur.com/M8DSsWJ.png alt="Traffic Examination"/>
</p>
<br />
<br />

1c.
<p align="center">
<img src="https://imgur.com/sydITFU.png alt="Traffic Examination"/>
</p>
<br />
<br />

1d.
<p align="center">
<img src="https://imgur.com/gm2uVdv.png alt="Traffic Examination"/>
</p>
<br />
<br />

1e.
<p align="center">
<img src="https://imgur.com/OxLVQTM.png alt="Traffic Examination"/>
</p>
<br />
<br />

Step 2. Configure the Departments
- Admin Panel -> Agents -> Departments
- For testing purposes create the department: System Administrators  

<p align="center">
<img src="https://imgur.com/e00qPRv.png alt="Traffic Examination"/>
</p>
<br />
<br />

2b. 
<p align="center">
<img src="https://imgur.com/fYAKYR6.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 3. Configure Teams
- Admin Panel -> Agents -> Teams
- For the purposes of testing create two teams (Level I Support, Level II Support)

<p align="center">
<img src="https://imgur.com/4wIG9A3.png alt="Traffic Examination"/>
</p>
<br />
<br />

3b.
<p align="center">
<img src="https://imgur.com/0Sh96O5.png alt="Traffic Examination"/>
</p>
<br />
<br />

3c. Add a member to the team
<p align="center">
<img src="https://imgur.com/AYgslAg.png alt="Traffic Examination"/>
</p>
<br />
<br />

3d. Teams Created
<p align="center">
<img src="https://imgur.com/TYkpbfd.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 4. Allow anyone to create tickets. Go to:
- Admin Panel -> Settings -> User Settings
- Registration Required: Require registration and login to create tickets

<p align="center">
<img src="https://imgur.com/bNo1uVb.png alt="Traffic Examination"/>
</p>
<br />
<br />


Step 5. Configure Agents (Workers who will work the tickets). Go to:
- Admin Panel -> Agents -> Add New
- (Whatever names you choose)          

<p align="center">
<img src="https://imgur.com/AaGOZ0Z.png alt="Traffic Examination"/>
</p>
<br />
<br />


5b. Set the agent password

<p align="center">
<img src="https://imgur.com/7150koE.png alt="Traffic Examination"/>
</p>
<br />
<br />

5c. Set the department for the agent

<p align="center">
<img src="https://imgur.com/sgkD1Zk.png alt="Traffic Examination"/>
</p>
<br />
<br />

5d. Set the permissions for the new agent 

<p align="center">
<img src="https://imgur.com/3TnpvPY.png alt="Traffic Examination"/>
</p>
<br />
<br />

5e. Set the team for the new agent 

<p align="center">
<img src="https://imgur.com/3TdA9R5.png alt="Traffic Examination"/>
</p>
<br />
<br />

5f. New agent has been created

<p align="center">
<img src="https://imgur.com/bo7hKZh.png alt="Traffic Examination"/>
</p>
<br />
<br />

Step 6. Go the the agent panel and create new user (Customers who can create a service ticket request). Go to:
- Agent Panel -> Users -> Add New
- For the purposes of testing create two users (whatever names you choose)

<p align="center">
<img src="https://imgur.com/Ynqb3m2.png alt="Traffic Examination"/>
</p>
<br />
<br />

6b. Enter the details of the new user

<p align="center">
<img src="https://imgur.com/1ERcVlZ.png alt="Traffic Examination"/>
</p>
<br />
<br />


6c. New user has been created

<p align="center">
<img src="https://imgur.com/QKrY0CC.png alt="Traffic Examination"/>
</p>
<br />
<br />


6d. Register the new user

<p align="center">
<img src="https://imgur.com/Vdb3Xfy.png alt="Traffic Examination"/>
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
<img src="https://imgur.com/a43lnfj.png alt="Traffic Examination"/>
</p>
<br />
<br />

7b. Give the plan a name and set the schedule

<p align="center">
<img src="https://imgur.com/ecSFUfw.png alt="Traffic Examination"/>
</p>
<br />
<br />

7c. SLA Plans Created 

<p align="center">
<img src="https://imgur.com/zOlS1Ei.png alt="Traffic Examination"/>
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
<img src="https://imgur.com/GNiIDIo.png alt="Traffic Examination"/>
</p>
<br />
<br />

8b. Set the help topic details (Name, Status, Parent Topic)

<p align="center">
<img src="https://imgur.com/28lVqxI.png alt="Traffic Examination"/>
</p>
<br />
<br />

8c. Next, set the ticket options for the created help topic (department, status, priority, SLA plan, team assignment)

<p align="center">
<img src="https://imgur.com/BqHduZy.png alt="Traffic Examination"/>
</p>
<br />
<br />


8d. Help Topics Have Been Created

<p align="center">
<img src="https://imgur.com/g6PS3Tz.png alt="Traffic Examination"/>
</p>
<br />
<br />


For the the next tutorial in this series go <a href=https://github.com/presicion25/osTicket-Ticket-Lifecycle-Examples>here</a></h2>
<br />
Thank Your for reading!
