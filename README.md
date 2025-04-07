<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

![image](https://github.com/user-attachments/assets/272c3f06-f11c-4de6-ad10-7b424fd7d9c2)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

1️⃣ Configure Roles 🎭 – Set up different roles to manage permissions and responsibilities.

2️⃣ Configure Departments 🏢 – Organize your support system by creating departments for better workflow.

3️⃣ Configure Teams 👩‍💻👨‍💻 – Group agents into teams to handle tickets efficiently.

4️⃣ Configure Agents & Users 🛠️ – Add your support agents and users, assigning them to the right roles and departments.

5️⃣ Configure SLA & Help Topics ⏳📌 – Set up Service Level Agreements (SLAs) to manage response times and create help topics for a seamless support experience.

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/0a01c281-6074-437b-be0a-d38cddd58a06)



![image](https://github.com/user-attachments/assets/e9b748ea-c202-4dcf-b552-9d70e2ad75f1)


![image](https://github.com/user-attachments/assets/06e47837-0b7f-40c7-83eb-af1964be07a7)

### **How to Set Up osTicket (Step-by-Step Guide for Beginners) 🚀**  

If you're new to **osTicket**, this guide will walk you through setting it up from scratch. Follow these steps to configure roles, agents, users, and ticket settings easily!  

---  

### **1️⃣ Access Your osTicket Dashboard**  
To begin, open your web browser and go to:  
- **Admin/Analyst Login Page:** `http://localhost/osTicket/scp/login.php`  
- **End Users Portal:** `http://localhost/osTicket` (this is where customers submit tickets)  

---  

### **2️⃣ Set Up Roles & Permissions**  
Roles define what agents can do.  
1. Go to **Admin Panel → Agents → Roles**  
2. Create a new role or edit an existing one  
3. Assign permissions (e.g., **Supreme Admin** can access all settings)  

---  

### **3️⃣ Create Departments for Ticket Management**  
Departments organize tickets and control who sees them.  
1. Go to **Admin Panel → Agents → Departments**  
2. Add departments like **Help Desk, SysAdmins, and Networking**  
3. Agents assigned to a department will only see tickets related to their team  

---  

### **4️⃣ Group Agents into Teams**  
Teams allow agents from different departments to work together.  
1. Go to **Admin Panel → Agents → Teams**  
2. Create a team (e.g., **Online Banking Support**)  
3. Assign agents from different departments to collaborate on tickets  

---  

### **5️⃣ Control Who Can Submit Tickets**  
Decide whether anyone can create tickets or if registration is required.  
1. Go to **Admin Panel → Settings → User Settings**  
2. To allow open ticket submissions, **UNCHECK** "Require registration"  
3. If you want users to **log in before creating tickets**, leave this option checked  

---  

### **6️⃣ Add Agents (Help Desk Staff/Support Team)**  
Agents handle customer tickets.  
1. Go to **Admin Panel → Agents → Add New**  
2. Enter agent details and assign them to a department  
   - Example: **Jane (SysAdmins), John (Support Team)**  

---  

### **7️⃣ Add Users (Customers Who Submit Tickets)**  
Users are your customers or employees submitting tickets for help.  
1. Go to **Agent Panel → Users → Add New**  
2. Enter user details  
   - Example: **Karen and Ken** (Users needing IT support)  

---  

### **8️⃣ Configure SLA (Service Level Agreements)**  
SLAs define how quickly tickets should be handled.  
1. Go to **Admin Panel → Manage → SLA**  
2. Create SLAs based on priority:  
   - **Sev-A:** 1-hour response (24/7) 🚨  
   - **Sev-B:** 4-hour response (24/7) ⏳  
   - **Sev-C:** 8-hour response (Business Hours) 🕘  

---  

### **9️⃣ Set Up Help Topics (For Ticket Categorization)**  
Help Topics make it easier for users to choose the right issue category.  
1. Go to **Admin Panel → Manage → Help Topics**  
2. Add common issues:  
   - **Business Critical Outage** 🚨  
   - **Personal Computer Issues** 💻  
   - **Equipment Request** 📦  
   - **Password Reset** 🔑  
   - **Other** ❓  

---  



