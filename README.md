<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

This tutorial outlines the **post-install configuration** of the open-source help desk ticketing system **osTicket**.  

It focuses on configuring roles, departments, teams, agents, users, SLAs, and help topics to get a production-ready environment.

---

## Environments and Technologies

- **Microsoft Azure** (Virtual Machines / Compute)  
- **Remote Desktop**  
- **Internet Information Services (IIS)**  

**Operating System:** Windows 10 (21H2)

---

## Post-Install Configuration Objectives

- Configure **Roles**  
- Configure **Departments**  
- Configure **Teams**  
- Configure **Agents**  
- Configure **Users**  
- Configure **SLAs**  
- Configure **Help Topics**  

---

## Configuration Steps

### 1. Configure Roles

**Path:** Admin Panel → Agents → Roles  

- Example: **Supreme Admin** role created to grant full administrative permissions.  

**Why:** Roles control permissions and access levels for agents, ensuring security and proper workflow.  

<details>
<summary>Screenshots</summary>

![OS Ticket PIS 1](https://github.com/user-attachments/assets/216f0685-df4e-4494-876d-6818e0788280)  
![OS Ticket PIS 2](https://github.com/user-attachments/assets/cbc58fde-6d0f-4588-81c8-63a8d9cc7f0e)

</details>

---

### 2. Configure Departments

**Path:** Admin Panel → Agents → Departments  

- Example: **SysAdmins** department created to group related agents.  

**Why:** Departments organize agents for ticket routing and reporting.  

<details>
<summary>Screenshot</summary>

![OS Ticket PIS 3](https://github.com/user-attachments/assets/055e8294-072d-46cc-8fe9-372d64b98a3d)

</details>

---

### 3. Configure Teams

**Path:** Admin Panel → Agents → Teams  

- Example: **Online Banking** team created to manage specific support areas.  

**Why:** Teams help structure groups of agents across departments for collaborative ticket handling.  

<details>
<summary>Screenshot</summary>

![OS Ticket PIS 4](https://github.com/user-attachments/assets/2d2c4c28-be99-4a34-846c-9083bd56ce76)

</details>

---

### 4. Allow Users to Create Tickets

**Path:** Admin Panel → Settings → User Settings  

- Option: **Uncheck** “unregistered users can create tickets”  

**Why:** Controls whether anyone can submit tickets, improving security and reducing spam.  

<details>
<summary>Screenshot</summary>

![OS Ticket PIS 5](https://github.com/user-attachments/assets/2c644168-56bb-4cdb-bccd-15e12ca02978)

</details>

---

### 5. Configure Agents

**Path:** Admin Panel → Agents → Add New  

- Example agents:  
  - Jane (Dept: SysAdmins)  
  - John (Dept: Support)  

**Why:** Agents handle incoming tickets; assigning them to departments ensures proper routing.  

<details>
<summary>Screenshots</summary>

![OS Ticket PIS 6](https://github.com/user-attachments/assets/bb03b461-ac60-48c1-a1f3-363637d09bf2)  
![OS Ticket PIS 7](https://github.com/user-attachments/assets/e2fe11d5-e561-4bc3-aec9-6ae90e5225c5)  
![OS Ticket PIS 8](https://github.com/user-attachments/assets/2289e323-8bed-4cfb-948f-2946f7abb2a4)  
![OS Ticket PIS 9](https://github.com/user-attachments/assets/dbdbf07e-9701-4d26-ab94-c1696aa68740)

</details>

---

### 6. Configure Users

**Path:** Agent Panel → Users → Add New  

- Example users: Karen, Ken  

**Why:** Users are the ticket submitters; adding them ensures proper assignment and communication.  

<details>
<summary>Screenshots</summary>

![OS Ticket PIS 10](https://github.com/user-attachments/assets/86d85028-9501-412a-b342-aefc439482fe)  
![OS Ticket PIS 11](https://github.com/user-attachments/assets/13fa0ad1-b8d1-4447-b0ca-395ee9851cad)

</details>

---

### 7. Configure SLA (Service Level Agreements)

**Path:** Admin Panel → Manage → SLA  

- Example SLAs: Sev-A, Sev-B, Sev-C  

**Why:** SLAs define response and resolution targets, ensuring timely support.  

<details>
<summary>Screenshots</summary>

![OS Ticket PIS 12](https://github.com/user-attachments/assets/1d6e7028-472d-4651-8c31-d4f3e59b17ce)  
![OS Ticket PIS 13](https://github.com/user-attachments/assets/7e6fa8e5-81ca-458f-b48d-9ae9815458ac)

</details>

---

### 8. Configure Help Topics

**Path:** Admin Panel → Manage → Help Topics  

- Examples:  
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  
  - Other  

**Why:** Help Topics categorize tickets to streamline routing and reporting.  

<details>
<summary>Screenshots</summary>

![OS Ticket PIS 14](https://github.com/user-attachments/assets/28d03e9a-7829-4c4b-a90a-bc22cc6d3b72)  
![OS Ticket PIS 15](https://github.com/user-attachments/assets/0fe052cb-cb98-4120-b15d-48e7e0a80517)

</details>

---

✅ **Post-install configuration complete! osTicket is now ready for production use.**

