<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this tutorial, I follow a set list provided by the instructor, which outlines the post-install configuration of the open-source help desk ticketing system osTicket. He goes through the  tutorial showing us how to configure Agents, Roles, Departments and most importantly users. Additionally, we demonstrate how to set-up mock tickets, including handling, assigning, and resolving them effectively.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>Post-Install Configuration Objectives</h2>

- Create SLAs
- Create Users
- Create Agents
- Create Roles
- Create Department

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/H7CpjVT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, we sign into the Admin account we created and begin by configuring Service Level Agreements (SLAs). SLAs are predefined rules that outline the expected handling and resolution times for various types of tickets. During this step, we specify the name of each SLA and the timeframe within which the corresponding tickets should be addressed.
</p>
<br />

<p>
<img src="https://i.imgur.com/CgcgTJ1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we configure Agents, employees responsible for handling the tickets. In this step, we manage their permissions and access levels, including setting up their usernames and passwords. Additionally, we can assign agents to specific teams to streamline ticket management and ensure efficient handling.
</p>
<br />

<p>
<img src="https://i.imgur.com/25zMoEf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/aBKNnB1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up agents, we configure roles and departments. Roles define permissions and access levels for agents, allowing for customization based on specific needs. Departments help organize agents and determine the flow of tickets. Users can select the appropriate department when creating a ticket, ensuring it is directed to the correct team. During the setup, you can also assign an SLA to each department to manage response times effectively.
</p>
<br />

<p>
<img src="https://i.imgur.com/8dOaAeQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lastly, we configure the users and their contact information. This step primarily involves entering and verifying users' contact details to ensure they are accurately added to the database.
</p>
<br />
