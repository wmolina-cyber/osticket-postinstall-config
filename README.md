# **osTicket Post-Installation Configuration**

## **Overview**
This section demonstrates the post-installation configuration of osTicket, including setting up roles, departments, teams, SLA policies, and user permissions.

---

## **Steps Performed**

### **1. Access osTicket Panels**
- **Admin/Analyst Login Page**:  
  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
![1](https://github.com/user-attachments/assets/2d9aba89-ac28-4307-b04a-b6c6eddcea6b)
  
- **End Users URL**:  
  [http://localhost/osTicket](http://localhost/osTicket)  

---

### **2. Acknowledge Agent Panel vs Admin Panel**
- The **Agent Panel** is used by support staff to handle tickets.
  ![2](https://github.com/user-attachments/assets/0171b5fd-10f9-432e-94f1-1897190eb281)

- The **Admin Panel** is for system administrators to manage configurations and settings.  
  ![3](https://github.com/user-attachments/assets/acec2811-8359-40e4-be6a-da747859af1c)

---

### **3. Configure Roles**
- **Path**: `Admin Panel -> Agents -> Roles`
- **Role Created**: 
  - **Name**: Supreme Admin  
  ![9](https://github.com/user-attachments/assets/c6f4c8f7-d647-4af4-a064-d84ca9d53b80)

---

### **4. Configure Departments**
- **Path**: `Admin Panel -> Agents -> Departments`
- **Departments Created**: 
  - SysAdmins (for managing ticket visibility and grouping tasks)  
  ![17](https://github.com/user-attachments/assets/69815c8a-276a-4fde-b65e-a17018a05802)

---

### **5. Configure Teams**
- **Path**: `Admin Panel -> Agents -> Teams`
- **Team Created**: 
  - Online Banking (agents pulled from different departments)  
  ![22](https://github.com/user-attachments/assets/0ea0e9a0-297d-4404-90e3-674a8506653b)

---

### **6. Ticket Creation Settings**
- **Path**: `Admin Panel -> Settings -> User Settings`
- **Configuration**:  
  - **Unchecked**: Allow unregistered users to create tickets.  
  - **Checked**: Require registration and login to create tickets.  
  ![25](https://github.com/user-attachments/assets/0bf68414-41d8-472b-ac02-3091b3756138)

---

### **7. Configure Agents**
- **Path**: `Admin Panel -> Agents -> Add New`
- **Agents Added**:  
  - **Jane**: Assigned to **SysAdmins** department.  
  - **John**: Assigned to **Support** department.  
  ![34](https://github.com/user-attachments/assets/b38ca609-6ef4-45f9-9f06-4e736d7ca75a)

---

### **8. Configure Users**
- **Path**: `Agent Panel -> Users -> Add New`
- **Users Added**:  
  - **Karen**   
  ![37](https://github.com/user-attachments/assets/2040a3c1-4953-479b-afc4-94c8348cd0c0)

---

### **9. Configure SLA Policies**
- **Path**: `Admin Panel -> Manage -> SLA`
- **SLA Policies Created**:
  1. **Sev-A**: 1-hour grace period, 24/7 schedule  
  2. **Sev-B**: 4-hour grace period, 24/7 schedule  
  3. **Sev-C**: 8-hour grace period, business hours schedule  
  ![45](https://github.com/user-attachments/assets/8aa1b3b8-08b4-4db0-977f-e27ac1146fb2)

---

### **10. Configure Help Topics**
- **Path**: `Admin Panel -> Manage -> Help Topics`
- **Help Topics Created**:
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  
  - Other  
  ![48](https://github.com/user-attachments/assets/0589f9c2-4705-4054-99f0-13b3034ed1cc)

---

## **Conclusion**
This post-installation configuration sets up osTicket for efficient ticket management, with clear roles, permissions, SLA policies, and user workflows.

