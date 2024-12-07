# osticket-postinstall-config
# **osTicket Post-Installation Configuration**

## **Overview**
This section describes the post-installation configuration of the osTicket ticketing system. It covers setting up user roles, departments, agents, SLA policies, and help topics to prepare the system for effective IT support ticket management.

---

## **Steps Performed**

### **1. Accessing osTicket Panels**
- **Admin/Analyst Login Page**:  
  [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users URL**:  
  [http://localhost/osTicket](http://localhost/osTicket)

---

### **2. Understanding the Agent Panel vs Admin Panel**
- **Agent Panel**: For day-to-day ticket management by support agents.  
- **Admin Panel**: For system configuration and administrative tasks.

---

### **3. Configure Roles**
- **Path**:  
  `Admin Panel -> Agents -> Roles`
- **Role Created**:  
  - **Name**: Supreme Admin


---

### **4. Configure Departments**
- **Path**:  
  `Admin Panel -> Agents -> Departments`
- **Departments Created**:  
  - SysAdmins (manages ticket visibility for system administrators)


---

### **5. Configure Teams**
- **Path**:  
  `Admin Panel -> Agents -> Teams`
- **Team Created**:  
  - Online Banking (includes agents from multiple departments)


---

### **6. Allow/Restrict Ticket Creation**
- **Path**:  
  `Admin Panel -> Settings -> User Settings`
- **Configuration**:  
  - **Unchecked**: "Unregistered users can create tickets"
  - **Checked**: "Require registration and login to create tickets"


---

### **7. Configure Agents**
- **Path**:  
  `Admin Panel -> Agents -> Add New`
- **Agents Added**:  
  - **Jane**: Assigned to **SysAdmins** department  
  - **John**: Assigned to **Support** department  


---

### **8. Configure Users**
- **Path**:  
  `Agent Panel -> Users -> Add New`
- **Users Added**:  
  - **Karen**  
  - **Ken**


---

### **9. Configure SLA Policies**
- **Path**:  
  `Admin Panel -> Manage -> SLA`
- **SLA Policies Created**:
  1. **Sev-A**: 1-hour grace period, 24/7 schedule  
  2. **Sev-B**: 4-hour grace period, 24/7 schedule  
  3. **Sev-C**: 8-hour grace period, business hours schedule  


---

### **10. Configure Help Topics**
- **Path**:  
  `Admin Panel -> Manage -> Help Topics`
- **Help Topics Created**:
  - Business Critical Outage  
  - Personal Computer Issues  
  - Equipment Request  
  - Password Reset  
  - Other  



---

## **Conclusion**
The post-installation configuration ensures that osTicket is set up for efficient use. Roles, departments, and teams allow for proper agent organization, while SLA policies and help topics ensure a streamlined ticket resolution process.

---

