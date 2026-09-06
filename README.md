# 🔐 Cybersecurity Lab — Week 01

## Kali Linux Deployment & Virtualization with Oracle VirtualBox

---

## 📌 Project Overview

This project documents my first practical cybersecurity laboratory exercise.

The objective was to build a virtual cybersecurity laboratory environment for penetration-testing and ethical-hacking practice by deploying Kali Linux v2026.2 using Oracle VirtualBox v7.2.

The project provided practical experience with:

- Virtualization
- Kali Linux
- Linux system administration
- Networking
- Troubleshooting
- Hardware resource management
- Technical documentation
- Cybersecurity laboratory setup

The laboratory was performed on a Lenovo laptop running Windows with 4 GB of RAM.

---

## 🎯 Objectives

The main objectives of this project were to:

- Install and use Oracle VirtualBox
- Deploy Kali Linux in a virtual machine
- Configure virtual machine resources
- Start and access Kali Linux
- Learn basic Linux terminal commands
- Check system information
- Identify network interfaces
- Test network connectivity
- Identify performance limitations
- Troubleshoot limited hardware resources
- Understand NAT networking
- Build a practical cybersecurity laboratory environment
- Document the project as part of a cybersecurity portfolio

---

## 🔐 Cybersecurity Lab Environment

![Cybersecurity](https://img.shields.io/badge/Skill-Cybersecurity-red?style=for-the-badge&logo=hackthebox&logoColor=white)

![VirtualBox](https://img.shields.io/badge/VirtualBox-7.2-blue?style=for-the-badge&logo=virtualbox&logoColor=white)

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-2026.2-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)

---

## 💻 Lab Environment

### Host Computer

| Component | Details |
|---|---|
| Computer | Lenovo Laptop |
| Model/Type | 81H5 |
| Host Operating System | Windows |
| RAM | 4 GB |

### Virtual Machine

| Resource | Configuration |
|---|---|
| Operating System | Kali Linux v2026.2 |
| Virtualization Platform | Oracle VirtualBox v7.2 |
| Network Mode | NAT |
| RAM | Configured according to available host resources |
| CPU | Configured according to available host resources |
| Storage | Virtual disk |

---

## 🏗️ Lab Architecture

```text
                 ┌─────────────────────────┐
                 │     Lenovo Laptop       │
                 │       Windows Host      │
                 │        4 GB RAM         │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │    VirtualBox v7.2       │
                 │   Virtualization Layer   │
                 └────────────┬────────────┘
                              │
                              ▼
                 ┌─────────────────────────┐
                 │   Kali Linux v2026.2    │
                 │     Virtual Machine     │
                 └────────────┬────────────┘
                              │
                    ┌─────────┴─────────┐
                    ▼                   ▼
             Linux Terminal       NAT Network
                    │                   │
                    ▼                   ▼
             System Checks       Internet Test

---

# 🚀 Kali Linux Deployment

## Step 1 — VirtualBox Setup

Oracle VirtualBox v7.2 was used as the virtualization platform.

A virtual machine was created and configured for Kali Linux v2026.2.

The configuration included:

- Kali Linux v2026.2
- Virtual CPU resources
- Allocated RAM
- Virtual storage
- NAT networking

The resources were configured according to the available hardware of the host computer.

---

## Step 2 — Creating the Kali Linux Virtual Machine

The Kali Linux v2026.2 virtual machine was created successfully in VirtualBox.

The VM was configured with:

- Operating System: Kali Linux v2026.2
- Virtualization: VirtualBox v7.2
- Network: NAT
- Virtual RAM: Configured according to available host resources
- Virtual CPU: Configured according to available host resources
- Virtual Disk: Virtual storage

---

## Step 3 — Starting Kali Linux

The virtual machine was started through VirtualBox.

Kali Linux successfully began the boot process and loaded into the Linux desktop environment.

---

# 🐧 Linux System Validation

After starting Kali Linux, I used the Linux terminal to perform basic system checks.

## Check Current User

```bash
whoami
pwd
ls
uname -a
ip addr
ping -c 4 google.com
Command Summary
Command	Purpose
whoami	Shows the current user
pwd	Shows the current working directory
ls	Lists files and directories
uname -a	Displays system and kernel information
ip addr	Displays network interface and IP information
ping -c 4 google.com	Tests network connectivity
🛠️ Tools & Resources
7-Zip
https://7-zip.org/download.html
7-Zip was used as a file compression and extraction utility when working with downloaded files and archives.
Oracle VirtualBox
https://virtualbox.org/wiki/Downloads
Oracle VirtualBox was used to create and run the Kali Linux virtual machine.
Kali Linux
https://kali.org/get-kali
Kali Linux was used as the cybersecurity-focused operating system for the virtual laboratory environment.
📸 Project Evidence
The project will be supported by screenshots from my actual laboratory environment.
Evidence to be included:
VirtualBox VM configuration
Created Kali Linux virtual machine
Kali Linux starting
Kali Linux desktop
Linux terminal commands
Network connectivity test
Performance issue while running Kali Linux
Troubleshooting process
Screenshots used as personal project evidence should come from my actual laboratory environment. External images are not presented as evidence of my own work.
📚 Key Learning Outcomes
This project helped me develop practical knowledge of:
Cybersecurity laboratory setup
Virtualization
Oracle VirtualBox
Kali Linux
Linux operating systems
Linux terminal commands
System administration
Network interfaces
IP addressing
NAT networking
Network connectivity testing
Hardware resource allocation
Virtual machine troubleshooting
Technical documentation
GitHub portfolio development
💭 Technical Reflection
This project demonstrated that cybersecurity requires more than simply learning security tools.
A cybersecurity professional also needs to understand operating systems, networking, virtualization, hardware resources, and troubleshooting.
The 4 GB RAM limitation provided practical experience of how insufficient system resources can affect a virtualized cybersecurity environment.
The experience also demonstrated the importance of monitoring system performance and allocating resources appropriately.
🔮 Future Improvements
For future cybersecurity laboratory projects, I plan to:
Upgrade the laptop RAM to 8 GB or more
Improve Kali Linux virtual machine performance
Explore additional Kali Linux security tools
Perform controlled network-security exercises
Learn additional Linux commands
Build more cybersecurity laboratory projects
Improve technical documentation
Continue developing my GitHub cybersecurity portfolio
📊 Project Summary
Category	Details
Project	Cybersecurity Lab — Week 01
Topic	Kali Linux Deployment & Virtualization
Skill	Cybersecurity
Host Computer	Lenovo Laptop
Model/Type	81H5
Host Operating System	Windows
Host RAM	4 GB
Virtualization	VirtualBox v7.2
Guest Operating System	Kali Linux v2026.2
Networking	NAT
Main Challenge	Limited RAM
Secondary Challenge	Slow VM startup
Troubleshooting	Resource optimization and application management
Future Hardware Improvement	Upgrade to 8 GB RAM or more
Status	Completed
⚖️ Ethical & Legal Disclaimer
All cybersecurity activities documented in this portfolio are intended for educational purposes.
Security testing should only be performed on systems, networks, applications, and environments where appropriate authorization has been granted.
This laboratory environment is intended for controlled and authorized cybersecurity learning.
📖 References
Kali Linux Documentation
Oracle VirtualBox Documentation
GitHub Documentation
7-Zip Documentation
👤 Author
Kabo Sekoto
Junior Cybersecurity
This repository forms part of my practical cybersecurity learning portfolio and documents my progress through hands-on laboratory exercises.
LinkedIn:
https://linkedin.com/in/kabo-sekoto-706429259/