# IT Portfolio — Tobiloba Oyerogba

A collection of hands-on IT labs and projects built in a personal home lab environment.
Everything here is practical work — configured, tested, and documented by me.

---

## 🎓 Certifications

| Certification | Status | Issuer |
|--------------|--------|--------|
| Certified in Cybersecurity (CC) | ✅ Completed | ISC2 |
| CompTIA A+ (220-1101 & 220-1102) | 🔄 In Progress | CompTIA |
| CompTIA Security+ SY0-701 | 🔄 In Progress | CompTIA |
| Google Data Analytics | 🔄 In Progress | Google / Coursera |

---

## 🔬 Home Lab Environment

| Component | Detail |
|-----------|--------|
| Virtualisation | Oracle VirtualBox |
| Domain Controller | Windows Server 2022 — tobilab.local |
| Client Machine | Windows 11 Pro — joined to domain |
| Linux Machine | Ubuntu 22.04 LTS |
| Network | VirtualBox Host-only Adapter — 192.168.56.0/24 |
| Server IP | 192.168.56.10 (static) |
| Client IP | 192.168.56.20 (static) |

---

## 📁 Projects

### 01 — ServiceNow Incident Management
**Tools:** ServiceNow Personal Developer Instance  
**What I did:** Created and resolved 10 realistic IT support tickets covering hardware, software, network, access management, and service requests. Each ticket includes a full description, correct priority and category classification, and detailed resolution notes.  
👉 [View project](./01-ServiceNow-Incident-Management)

---

### 02 — Active Directory Lab
**Tools:** Windows Server 2022 • Active Directory Domain Services • Group Policy Management Console • PowerShell  
**What I did:** Built a full Active Directory domain from scratch — created the domain controller, designed a 4-OU organisational structure, created user accounts and security groups, configured Group Policy Objects, and practised core Help Desk tasks including password resets, account unlocks, and user migration between OUs.  
👉 [View project](./02-Active-Directory-Lab)

---

### 03 — PowerShell Bulk User Creation
**Tools:** PowerShell • Active Directory  
**What I did:** Wrote a PowerShell script that reads a CSV file and automatically bulk-creates Active Directory user accounts, reducing manual account creation from 30 minutes to under 10 seconds for a batch of 10 users.  
👉 [View project](./03-PowerShell-Scripts)

---

### 04 — Network Configuration Lab
**Tools:** VirtualBox • TCP/IP • DNS  
**What I did:** Configured static IP addresses and DNS settings on both VMs, set up Host-only networking so the VMs could communicate, and verified connectivity using ping, ipconfig, and nslookup. This network configuration is the foundation for the Active Directory domain join.  
👉 [View project](./04-Network-Configuration)

---

## 🛠️ Skills Demonstrated Across Projects

**Help Desk & ITSM**
- ServiceNow incident management and ticket lifecycle
- ITIL-aligned priority classification and resolution documentation
- Active Directory user management — create, reset, unlock, disable, move

**Networking**
- Static IP and DNS configuration
- Host-only VM networking
- Connectivity testing with ping, tracert, nslookup, ipconfig

**Systems Administration**
- Windows Server 2022 — roles, features, domain promotion
- Active Directory Domain Services — OUs, users, groups, GPOs
- Group Policy — password policy, screen lock, account lockout

**Scripting & Automation**
- PowerShell — New-ADUser, Import-Csv, foreach loops, bulk automation

**Security**
- ISC2 CC certified — security principles, access control, incident response
- Group Policy security controls — USB blocking, account lockout, least privilege
- Windows event log analysis — Event IDs 4625, 4672, 4688

**Virtualisation**
- VirtualBox multi-VM environment
- Windows Server and Windows 11 installation and configuration
- Domain join and network troubleshooting across VMs

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/tobiloba-oyerogba)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Profile-red?style=flat&logo=tryhackme)](https://tryhackme.com/p/tobbyoyerogba)

> Projects are added regularly as new labs are completed.
