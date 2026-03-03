# 🚀 Hybrid Identity Infrastructure Lab (Azure + Active Directory + Microsoft 365)

## 📌 Project Overview
This project demonstrates the deployment of a **real-world Hybrid Identity Infrastructure** simulating an enterprise IT environment using:

- Microsoft Azure
- Windows Server Active Directory
- Microsoft Entra ID (Azure AD)
- Microsoft 365
- Azure AD Connect Sync
- Group-Based Licensing

--------GitHub Folder Structure----------

Hybrid-Identity-Lab/
│
├── README.md
├── Architecture/
│   └── architecture-diagram.png
│
├── Screenshots/
│   ├── Azure-VNet.png
│   ├── DC01-Setup.png
│   ├── AD-Users.png
│   ├── Entra-Sync.png
│   └── Licensing.png
│
└── Notes/
    └── Lab-Steps.docx

----------------------------------------------------------------------------------------------------------------------------------

The goal of this lab was to understand how modern organizations integrate **On-Premises Active Directory with Cloud Identity Services**.

---

## 🏗️ Architecture Overview

Hybrid Environment:

On-Prem Active Directory (DC01)
        ↓
Azure AD Connect Sync
        ↓
Microsoft Entra ID
        ↓
Microsoft 365 Services
        ↓
Intune Ready Devices

---

## ☁️ Technologies Used

- Microsoft Azure
- Windows Server 2019 / 2022
- Active Directory Domain Services (AD DS)
- DNS Services
- Microsoft Entra ID
- Azure AD Connect
- Microsoft 365 Admin Center
- Virtual Network (VNet)
- Organizational Units (OU)
- Security Groups
- Group-Based Licensing

---

## 🔧 Lab Implementation Steps

### ✅ 1. Azure Infrastructure Setup
- Created Azure Resource Group
- Configured Virtual Network & Subnet
- Deployed Windows Server VM (DC01)

### ✅ 2. Domain Controller Deployment
- Installed AD DS Role
- Promoted Server to Domain Controller
- Created new Forest:
  
### ✅ 3. Active Directory Configuration
- Created Organizational Units:
  - Finance
  - HR
  - IT Admins
- Created domain users
- Applied department-based structure

### ✅ 4. Custom Domain Integration
- Purchased domain from GoDaddy
- Verified domain in Microsoft 365
- Added UPN suffix:
- 
### ✅ 5. Hybrid Identity Setup
- Installed Microsoft Entra Connect
- Configured OU-based synchronization
- Enabled Password Hash Synchronization
- Synced On-Prem AD users to Entra ID

### ✅ 6. Security Group Implementation
- Created Finance Security Group
- Added department users
- Enabled centralized access management

### ✅ 7. Microsoft 365 Integration
- Users automatically synced to M365
- Assigned licenses using Group-Based Licensing
- Verified successful cloud identity sync

---

## ✅ Key Outcomes

✔ Hybrid Identity successfully configured  
✔ On-Prem users synchronized to Microsoft Entra ID  
✔ Department-based identity management  
✔ Enterprise-style access control  
✔ Microsoft 365 automated licensing  

---

## 🎯 AZ-104 Concepts Covered

- Manage Azure Active Directory objects
- Configure Hybrid Identity
- Manage Virtual Networks
- Deploy Azure Virtual Machines
- Implement Identity Synchronization
- Role-Based Access Control (RBAC)
- Identity Governance

---

## 🧠 Real-World Scenario Simulated

Finance department employees receive:
- Domain joined accounts
- Microsoft 365 access
- License assignment via security groups
- Centralized identity management

Similar to enterprise environments used by Microsoft-based organizations.

---

## 🚀 Future Improvements

- Microsoft Intune Enrollment
- Windows Autopilot Deployment
- Zero-Touch Laptop Provisioning
- Conditional Access Policies
- Endpoint Security Policies

---

## 📸 Lab Screenshots

Screenshots included in repository showing:
- Domain Controller deployment
- Azure AD Connect setup
- OU creation
- User synchronization
- License assignment

---

## 👨‍💻 Author

**Bivek Shah**  
Aspiring Cloud & Cybersecurity Engineer  

🔗 LinkedIn: https://linkedin.com/in/YOUR-LINK  
🔗 GitHub: https://github.com/bivekshah-IT

---

⭐ If you found this project useful, feel free to star the repository!
