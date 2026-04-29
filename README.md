# Identity-Access-and-User-Lifecycle-Administration
# Identity, Access, and User Lifecycle Administration (Active Directory Lab)

## Overview
This project simulates identity and access administration in a small enterprise Windows domain environment. 

I built a Windows Server 2022 domain controller, joined a Windows 10 client, and implemented department-based access controls using Active Directory security groups. The lab includes user onboarding, access validation, account lockout troubleshooting, and user offboarding to reflect real-world IT support and access management workflows.

---

## Environment
- Windows Server 2022 (Domain Controller)
- Windows 10 Client Machine
- VirtualBox
- Active Directory Domain Services (AD DS)

---

## Objectives
- Configure a domain environment with centralized identity management  
- Implement role-based access control using security groups  
- Enforce least privilege access to shared resources  
- Simulate real-world IT support scenarios involving user accounts and permissions  
- Document troubleshooting and support workflows  

---

## Skills Demonstrated
- Active Directory user and group management  
- Identity and access control (RBAC, least privilege)  
- NTFS and share permission configuration  
- Troubleshooting access and authentication issues  
- User lifecycle management (onboarding, support, offboarding)  
- Documentation and ticket-style communication  

---

## Lab Topology
- 1 Domain Controller (Windows Server 2022)
- 1 Client Machine (Windows 10)
- Domain-based authentication
- Centralized file shares hosted on the server

---

## Scenarios Completed

### 1. User Onboarding
- Created a new user account in Active Directory  
- Assigned user to appropriate department security groups  
- Verified domain login from Windows 10 client  
- Configured initial access to shared resources  

---

### 2. Access Control Implementation
- Created shared folders for:
  - Public
  - Operations
  - HR
  - Finance  
- Configured NTFS and share permissions using security groups  
- Implemented least privilege access model  

---

### 3. Access Validation
- Verified user access from client machine  
- Confirmed:
  - Access to Public folder  
  - Denied access to unauthorized department folders  
- Validated proper permission enforcement  

---

### 4. Account Lockout Troubleshooting
- Simulated user account lockout  
- Identified issue using Active Directory tools  
- Unlocked account and restored access  
- Verified successful login  

---

### 5. User Offboarding
- Disabled user account  
- Removed group memberships  
- Revoked access to shared resources  
- Ensured access was fully terminated  

---

## Key Takeaways
- Proper group-based access control simplifies permission management  
- Least privilege is critical for reducing unnecessary access  
- Many access issues stem from incorrect group membership  
- Clear documentation improves troubleshooting efficiency  

---

## Tools Used
- Active Directory Users and Computers (ADUC)  
- Windows File Server  
- Windows 10 Client  
- VirtualBox  

---

## What This Simulates in a Real Environment
This lab reflects common responsibilities in help desk and junior systems administration roles, including:

- User account provisioning and support  
- Access control and permission management  
- Troubleshooting login and access issues  
- Supporting shared resources in a domain environment  
