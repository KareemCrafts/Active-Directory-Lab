# Active Directory Lab Environment

## 📸 Screenshots

### Active Directory Users and Computers
<img width="1015" height="846" alt="ServerManagerDashboard" src="https://github.com/user-attachments/assets/bba2d105-ea73-421f-ae54-a9d38a73b661" />

### Domain Controller ping
<img width="1010" height="751" alt="Ping" src="https://github.com/user-attachments/assets/0d6aa167-e9c4-4d5a-be48-d28aec35f48d" />

### Network Configuration
<img width="977" height="777" alt="NetworkConfiguration" src="https://github.com/user-attachments/assets/eeb19238-ef86-46d0-a63c-b03084ae1316" />


### Setting DomainName
<img width="1020" height="768" alt="DomainName" src="https://github.com/user-attachments/assets/762980c1-459a-4cc7-93fb-fa0652e24882" />


### Domain-Joined Workstation
<img width="1013" height="838" alt="Test" src="https://github.com/user-attachments/assets/6dbe67a8-6e01-421c-b6e9-052af6ae1bf9" />


## 📋 Overview
Built a virtualized Active Directory lab environment to gain hands-on experience with enterprise Windows security, domain administration, and Group Policy management.

## 🏗️ Lab Architecture

**Infrastructure:**
- **Domain Controller:** Windows Server 2019 (DC-Server)
- **Workstations:** Windows 10 Pro (Workstation)
- **Virtualization Platform:** VMware Workstation
- **Domain Name:** kareem.local
- **Network Configuration:** NAT

## 🛠️ Technologies Used

- Windows Server 2019
- Active Directory Domain Services (AD DS)
- Group Policy Objects (GPO)
- DNS Services
- Authentication Protocols: Kerberos, NTLM, LDAP
- PowerShell
- VMware Workstation

## 📝 Implementation Steps

### 1. Domain Controller Setup
- Installed Windows Server 2019 on virtual machine
- Configured Active Directory Domain Services (AD DS) role
- Promoted server to Domain Controller
- Created domain: **cerulean.local**
- Set up DNS services for domain resolution

### 2. Active Directory Configuration
- Created Organizational Units (OUs) for logical grouping:
  - HR Department
  - IT Department
  - Finance Department
- Created domain user accounts (Lily, Markus)
- Configured security groups with appropriate permissions
- Assigned Domain Admin privileges to specific users
- Implemented least privilege access control

### 3. Group Policy Implementation
- Created GPO for command-line process logging
- Configured security policies for password complexity
- Tested GPO inheritance and enforcement
- Linked policies to specific OUs

### 4. Workstation Domain Integration
- Installed Windows 10 Pro on two virtual machines
- Configured DNS settings to point to Domain Controller
- Successfully joined workstations to cerulean.local domain
- Tested domain user authentication (Kerberos)
- Verified Group Policy application on workstations

## 🎯 Key Learning Outcomes

- Understanding of Active Directory architecture and components
- Hands-on experience with domain administration and user management
- Knowledge of authentication protocols (Kerberos, NTLM, LDAP)
- Group Policy configuration and troubleshooting
- DNS configuration for domain services
- Security best practices: least privilege, segregation of duties, audit logging

## 💡 Skills Demonstrated

- Active Directory administration
- Windows Server management
- Group Policy configuration
- DNS configuration and troubleshooting
- Domain integration and management
- Security hardening and access control
- Virtualization and lab environment setup

## 🔐 Security Best Practices Implemented

- **Least Privilege Principle:** Users granted minimum necessary permissions
- **Segregation of Duties:** Administrative tasks split between roles
- **Audit Logging:** Enabled command-line logging for security monitoring
- **Strong Password Policies:** Enforced via Group Policy
- **Organizational Units:** Logical separation of resources and users



## 📚 References

- [Microsoft Active Directory Documentation](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/)
- [VMware Workstation Documentation](https://www.vmware.com/products/workstation-pro.html)

---

**Author:** [Kareem Tamer Yousef]  
**Date:** January 2026  
**Contact:** [kareemtamer2512@gmail.com] | [www.linkedin.com/in/kareem-alshaer-b540a8297]
