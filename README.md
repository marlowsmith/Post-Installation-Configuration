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

- Added New Departments
- Added new teams
- Configured Agents
- Service Level Agreements
- Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/870cd086-25ce-46e0-b919-97c2c72cb1fe)

<p>
</p>
<p>
I configured department roles. For example, help desk and system administration. I did this so if a ticket gets assigned to a particular department, only they can see their tickets. System Administration, I enabled them to have higher access.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/fcc8dacb-7d1d-47c2-b0cd-d471f6594367)

</p>
<p>
Created and configured teams. In this example, I created a banking team and allowed them access to their department when it comes to seeing help desk tickets. I also allowed users to create their own tickets. 
</p>
<br />

![image](https://github.com/user-attachments/assets/54ad4f40-caf1-4089-8ce3-02ffc91d71f6)

<p>
</p>
<p>
Organized agents: I created an agent account for new employees. I assigned departments, usernames, and passwords (temporarily). I allowed them permission to change the password once they are in their new account.
</p>
<br />

![image](https://github.com/user-attachments/assets/4977d685-7383-4918-a81c-048e362f7730)

<p>
</p>
<p>
Created Service Level Agreements (SLAs). Setting up how much time you have to do a certain task. For example, responding to a ticket or completing a ticket. I created three different SLAs: Sev A, Sev B, and Sev C. I set up a grace period and a schedule. 
</p>
<br />

![image](https://github.com/user-attachments/assets/4f9956c0-34d5-4aa2-9aed-d4085f860e3b)

<p>
</p>
<p>
Set up help topics for when users create a ticket, they can choose the category of the problem. Some of the example help topics I created were business critical outage, personal computer issues, equipment request, and password reset.
</p>
<br />
