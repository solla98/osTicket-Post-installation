<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Installation Configuration

This project focuses on the post-installation configuration of the osTicket system, including setting up roles, departments, agents, SLA plans, end-users, and help topics to make the help desk fully functional.

---

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10

---

## Table of Contents

- [Configure Roles](#01-configure-roles)
- [Create Departments](#02-create-departments)
- [Add Agents](#03-add-agents)
- [Add Users](#04-add-users)
- [Set Up SLA Plans](#05-set-up-sla-plans)
- [Create Help Topics](#06-create-help-topics)

---

## 01. Configure Roles

<p align="center">
  <img width="1388" height="781" src="https://github.com/user-attachments/assets/84b39a51-98cb-45b5-a976-9030217e82b8" alt="image" />
  <img width="1391" height="782" src="https://github.com/user-attachments/assets/f3fae00f-b49e-492c-b626-23defbb6945a" alt="image" />
  <img width="1388" height="781" src="https://github.com/user-attachments/assets/76b1f786-45e6-4e7c-ab26-7b8c443b61da" alt="image" />
  <img width="1387" height="781" src="https://github.com/user-attachments/assets/c53018ea-cb4f-4211-aeae-2789642cfb4b" alt="image" />
</p>

Created a custom role named **“Supreme Admins”** and assigned full permissions for all tasks and ticket management operations to demonstrate role-based access control in osTicket.

---

## 02. Create Departments

<p align="center">
  <img width="1387" height="781" src="https://github.com/user-attachments/assets/d527a0d2-8fef-4ac5-8dc4-767383750ae0" alt="image" />
  <img width="1389" height="784" src="https://github.com/user-attachments/assets/52c738c5-00d7-4c3b-9f6b-55a32fc37dc6" alt="image" />
</p>

Added a new department named **“SysAdmins”** to organize and route support tickets to the appropriate technical team.

---

## 03. Add Agents

<p align="center">
  <img width="1387" height="783" src="https://github.com/user-attachments/assets/a4ba6ee2-789c-4448-bfee-ad8195a8b1c8" alt="image" />
  <img width="1388" height="754" src="https://github.com/user-attachments/assets/641b7600-f286-406f-a004-c7b125e3e4e1" alt="image" />
  <img width="1388" height="751" src="https://github.com/user-attachments/assets/a293183c-8b0c-4a18-bf49-022e3181919c" alt="image" />
  <img width="1388" height="753" src="https://github.com/user-attachments/assets/45192bd5-2036-44cc-b1f2-019c88f381f4" alt="image" />
</p>

- Created a sample agent named **Jane Doe**, assigned to the **SysAdmins** department with the **Supreme Admins** role. Also added to the **Online Banking Team** to handle tickets for that category.  
- Created an additional agent named **John Doe**, assigned to the **Support** department with limited read-only permissions. This demonstrates how osTicket supports multiple access levels for agents based on their roles.

---

## 04. Add Users

<p align="center">
  <img width="1387" height="751" src="https://github.com/user-attachments/assets/80156328-c833-45ad-93ae-a15faa7bbdf3" alt="image" />
  <img width="1389" height="752" src="https://github.com/user-attachments/assets/445b0952-a9f8-4b8f-84df-c81f1df29d36" alt="image" />
</p>

Set up a test end-user account (**Karen**) to simulate the user support experience and verify ticket creation functionality.

---

## 05. Set Up SLA Plans

<p align="center">
  <img width="1390" height="751" src="https://github.com/user-attachments/assets/d552c991-7a0c-4d5a-85ca-8aa2a29eff56" alt="image" />
  <img width="1390" height="750" src="https://github.com/user-attachments/assets/72d6c5fb-1c8a-4599-87b2-306d4a54099a" alt="image" />
  <img width="1389" height="753" src="https://github.com/user-attachments/assets/f2084bc3-f71f-4bbd-b875-abdb8fd2266f" alt="image" />
  <img width="1389" height="751" src="https://github.com/user-attachments/assets/905f464f-990b-4ad7-8cb2-85fce0a7199b" alt="image" />
  <img width="1387" height="753" src="https://github.com/user-attachments/assets/8fd74bf3-6402-4d4a-99ea-9753e1af536c" alt="image" />
</p>

Configured three SLA tiers (**Sev A, Sev B, Sev C**) to classify tickets by urgency.  
- **Sev A**: Critical incidents, 1-hour response time  
- **Sev B & C**: Lower-priority issues with longer resolution windows  

---

## 06. Create Help Topics

<p align="center">
  <img width="1390" height="753" src="https://github.com/user-attachments/assets/74dcda46-8ad6-4249-9f5c-827da62fb323" alt="image" />
  <img width="1389" height="752" src="https://github.com/user-attachments/assets/300b9997-de52-4463-8e8d-50ab333769c2" alt="image" />
  <img width="1388" height="753" src="https://github.com/user-attachments/assets/889a33d5-8b8f-4ed3-aadc-972f7f181a49" alt="image" />
  <img width="1387" height="751" src="https://github.com/user-attachments/assets/a513bf33-759d-4b3f-bcb2-5c85e70a3751" alt="image" />
  <img width="1390" height="752" src="https://github.com/user-attachments/assets/19b5a48d-c705-47bf-b8e0-00648e14d02c" alt="image" />
  <img width="1389" height="750" src="https://github.com/user-attachments/assets/d93f71bb-6b31-4b76-83ed-600a17961cba" alt="image" />
</p>

Added help topics including **Business Critical Outage**, **Personal Computer Issues**, and **Password Reset** to make it easier for end-users to categorize their requests when submitting tickets.

