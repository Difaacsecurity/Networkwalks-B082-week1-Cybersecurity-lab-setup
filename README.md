# 🔐 Cybersecurity Lab Setup – Week 1

Building a controlled virtual cybersecurity laboratory using VirtualBox and Kali Linux for future cybersecurity, networking, SOC, and security-testing projects.
## 📌 Project Overview
This project is the foundation for my upcoming cybersecurity labs and practical projects.

The main goal of Week 1 was to build and configure a virtual cybersecurity environment using **Oracle VirtualBox** and **Kali Linux**.

The lab provides a controlled environment where I can safely practice cybersecurity concepts, networking, security tools, and future penetration-testing activities.

## 🎯 Objectives

The main objectives of this project are to:

* Install and configure 7-Zip
* Install Oracle VirtualBox
* Create a VirtualBox NAT Network
* Download and import Kali Linux
* Connect Kali Linux to the lab network
* Configure and verify Kali Linux networking
* Create a clean Virtual Machine snapshot
* Document the complete lab setup
* Prepare the environment for future cybersecurity projects

## 🛡️ Purpose of the Lab

The purpose of this laboratory is to provide an isolated and controlled environment for cybersecurity learning and practical experimentation.

The environment will be used for future activities such as:

* Network reconnaissance
* Network scanning
* Vulnerability assessment
* Packet analysis
* Security tool practice
* SOC-related exercises
* Cybersecurity labs
* Authorized penetration-testing practice

> ⚠️ **Ethical Use:**
> This laboratory is intended for educational purposes and authorized security testing only. Security tools must only be used against systems that I own or have explicit permission to test.


# ⚙️ Lab Configuration

| Component                    | Configuration             |
| ---------------------------- | ------------------------- |
| 🖥️ Host Operating System    | Windows 11                |
| 🧰 Hypervisor                | Oracle VirtualBox         |
| 🐉 Security Operating System | Kali Linux                |
| 🌐 Virtual Network           | NAT Network               |
| 📡 Network Range             | 10.0.0.0/24               |
| 📦 Archive Tool              | 7-Zip                     |
| 💻 Repository                | GitHub                    |
| 📚 Program                   | Networkwalks – Batch B082 |
| 📅 Week                      | Week 1                    |

---

# 🪜 Lab Setup Procedure

## Step 1 – Install 7-Zip

I installed **7-Zip** on my Windows host machine.

### Why?

7-Zip is useful for extracting and managing compressed files, including virtual machine files distributed in compressed formats.

### Result

The installation was completed successfully and the system was ready to extract the required laboratory files.

<img width="780" height="396" alt="Screenshot 2026-08-10 115659" src="https://github.com/user-attachments/assets/f498e944-02a4-4b22-8360-03b1295dc42b" />


# Step 2 – Install Oracle VirtualBox

I installed **Oracle VirtualBox** on my Windows host machine.

### Why?

VirtualBox provides the virtualization platform required to create, configure, and manage virtual machines for the cybersecurity laboratory.

### Result

VirtualBox was successfully installed and ready for the laboratory configuration.

<img width="1916" height="1032" alt="1" src="https://github.com/user-attachments/assets/c6c44336-5556-4617-ade0-124da6fc842a" />

# Step 3 – Create NAT Network

I created a dedicated **NAT Network** in VirtualBox.

### Network Configuration

Network Type: NAT Network
Network Range: 10.0.0.0/24

### Why?

The NAT Network provides a controlled virtual networking environment for the cybersecurity laboratory.

It also allows additional virtual machines to be connected to the same laboratory network in future projects.

<img width="1908" height="977" alt="2" src="https://github.com/user-attachments/assets/0c7597aa-b974-4487-b8e6-9163b054d331" />


# Step 4 – Install and Import Kali Linux

I downloaded and imported **Kali Linux** into Oracle VirtualBox.

The Kali Linux virtual machine was connected to the laboratory NAT Network.

### Why Kali Linux?

Kali Linux is a security-focused operating system that provides many tools used for:

* Network analysis
* Security testing
* Vulnerability assessment
* Digital forensics
* Penetration testing
* Cybersecurity learning

### Result

Kali Linux was successfully imported into VirtualBox and connected to the laboratory network.

<img width="1911" height="954" alt="3" src="https://github.com/user-attachments/assets/15b694ce-9032-4268-b422-13ee595396e4" />


# Step 5 – Configure Kali Linux Network

I configured Kali Linux to connect to the laboratory network.

IP Address:
10.0.0.2/24

Gateway:
10.0.0.1

DNS:
8.8.8.8

I then verified that Kali Linux received an IP address from the configured virtual network.

### Why?

Correct network configuration is important because future cybersecurity machines and targets will need to communicate within the laboratory environment.

### 📸 Screenshot

<img width="689" height="546" alt="4" src="https://github.com/user-attachments/assets/f20e2ca1-5796-4e0c-b5f4-84fb7dde34b2" />


# Step 6 – Create a Virtual Machine Snapshot

After completing the initial Kali Linux configuration, I created a VirtualBox snapshot.

### Snapshot Name

<img width="1901" height="1010" alt="5" src="https://github.com/user-attachments/assets/d7a2af7b-7ce5-4196-94b5-2a5f57e4ff03" />


### Why?

The snapshot provides a clean restore point.

If a future cybersecurity experiment changes or damages the Kali Linux environment, I can restore the virtual machine to this clean baseline.



# 🔎 Lab Verification

After completing the initial setup, the laboratory environment was checked to make sure the configuration was working correctly.


# 🐞 Problems Encountered & Solutions

Documenting problems and solutions is an important part of this project because troubleshooting is an essential cybersecurity and IT skill.

## Problem 1 – Network Configuration

During the lab setup, the Kali Linux network configuration needed to be checked to ensure that the virtual machine was correctly connected to the NAT Network.

### Solution

I reviewed the VirtualBox network adapter configuration and verified that Kali Linux was connected to the correct NAT Network.

## Problem 2 – Maintaining a Clean Lab Environment

Cybersecurity experiments can modify system configurations or files.

### Solution

I created a VirtualBox snapshot after completing the initial setup.

This provides a clean recovery point for future cybersecurity experiments.


# 💡 What I Learned

During Week 1, I learned how to build the foundation of a virtual cybersecurity laboratory.

### Technical Skills

1. How to install and use 7-Zip.
2. How to install Oracle VirtualBox.
3. How virtualization can be used for cybersecurity training.
4. How to create a NAT Network in VirtualBox.
5. How to import Kali Linux as a virtual machine.
6. How to connect a virtual machine to a virtual network.
7. How to check Kali Linux network configuration.
8. How to create and use VM snapshots.

### Professional Skills

I also learned that professional cybersecurity work is not only about technical skills.

It is also important to:

* Document technical work clearly.
* Capture evidence using screenshots.
* Record configurations.
* Document problems and solutions.
* Maintain a clean laboratory environment.
* Build a professional GitHub portfolio.


# 🔐 Security & Ethical Use

This laboratory is designed for **educational and authorized security testing purposes only**.

All future penetration-testing, scanning, exploitation, and security-testing activities will be performed only against systems that I own or have explicit authorization to test.


# 🔗 Tools & Technologies

* **Windows 11** – Host Operating System
* **Oracle VirtualBox** – Virtualization Platform
* **Kali Linux** – Cybersecurity Operating System
* **7-Zip** – Archive Management
* **GitHub** – Project Documentation & Version Control


# 📚 Future Development

This Week 1 laboratory will serve as the foundation for future cybersecurity projects.

Planned future activities may include:

* Windows Server laboratory
* Active Directory laboratory
* Network scanning
* Vulnerability assessment
* SIEM laboratory
* Splunk practice
* SOC monitoring
* Incident detection and response
* Network traffic analysis
* Penetration-testing labs



# 👤 Author

**Abbas Ali Gedi**

**Cybersecurity | SOC Analyst | IT Support Specialist**

**Program:** Networkwalks
**Batch:** B082
**Week:** 01

### GitHub

**Difaacsecurity**

### LinkedIn

[Abbas Ali Gedi](https://www.linkedin.com/in/abbas-ali-gedi-95432b381/)


# 📌 Project Status

**Status: ✅ Completed – Week 1**

The initial cybersecurity laboratory environment has been successfully prepared and is ready to support future cybersecurity, networking, and SOC projects.


## ⭐ Key Takeaway

> **Build it. Document it. Practice it. Defend it.**

This laboratory is the starting point for my practical cybersecurity journey.
