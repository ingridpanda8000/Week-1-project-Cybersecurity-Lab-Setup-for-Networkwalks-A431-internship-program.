# Week 1 Project: Cybersecurity Lab Setup for NetworkWalks A431 Internship Program

## 📌 Project Overview
This repository documents the complete setup of my cybersecurity lab environment as part of the **NetworkWalks A431 Internship Program**. This lab serves as the foundational infrastructure for all upcoming weekly projects, enabling hands-on practice with penetration testing, defense strategies, and security monitoring in an isolated, controlled environment.

---

## 🎯 Objectives
1. **Download & Install VirtualBox** – Set up VirtualBox as the primary virtualization platform on the host machine.
2. **Configure VirtualBox Network Settings** – Create and configure a NAT Network with subnet `10.0.0.0/24` for isolated VM communication.
3. **Deploy Kali Linux VM with IP Configuration & Snapshot** – Download, import, and configure Kali Linux with proper IP settings, followed by creating a baseline snapshot as a backup for future rollback.


---

## 🛠️ Tools & Technologies Used
| Tool | Purpose |
|------|---------|
| **VirtualBox** | Virtualization platform for running VMs |
| **Kali Linux** | Penetration testing and security analysis OS |
| **NAT Network** | Isolated network for lab VMs (10.0.0.0/24) |

---

## 📋 Step-by-Step Setup Process

### 1. Download & Install VirtualBox
Download and install VirtualBox on your laptop/PC from the official website: 🔗 [https://virtualbox.org/wiki/Downloads](https://virtualbox.org/wiki/Downloads)

![VirtualBox Installation](https://github.com/user-attachments/assets/9f9f0afa-7a00-4832-89c0-ab842fb16d46)

---

### 2. Configure VirtualBox Network Settings
Create a **NAT Network** with the subnet `10.0.0.0/24` to allow isolated communication between VMs.

![Network Configuration](https://github.com/user-attachments/assets/4ad8d137-2ec3-4032-a8c3-3ea205961cb4)

---

### 3. Download & Import Kali Linux Virtual Machine
Download the pre-built Kali Linux VM from the official website:
🔗 [https://kali.org/get-kali](https://kali.org/get-kali)

Import the OVA file into VirtualBox and configure the VM settings.

![Kali Linux Import](https://github.com/user-attachments/assets/d689eba2-d324-4b7f-938d-b4e4e5a802ef)

---

### 4. Configure Kali Linux IP Settings
Set up the IP configuration for Kali Linux to ensure proper connectivity within the lab network.

![Kali IP Configuration](https://github.com/user-attachments/assets/487c11b5-fb57-454c-8a41-b3c9866e47dc)

---

### 5. Take VM Snapshot
Create a baseline snapshot of the Kali Linux VM. This allows you to revert to a clean state if anything goes wrong during future experiments.

![VM Snapshot](https://github.com/user-attachments/assets/9f9e2585-47d5-4399-ac51-0e24e55d5ac2)

---

## ✅ Verification Checklist
- [ ] VirtualBox installed successfully
- [ ] NAT Network (10.0.0.0/24) created
- [ ] Kali Linux VM imported and running
- [ ] Network connectivity verified
- [ ] VM snapshot taken

---
