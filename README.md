# 🔐 Cybersecurity Lab — Week 01

## Kali Linux Deployment & Virtualization with Oracle VirtualBox

**Author:** Kabo Sekoto  
**Field:** Cybersecurity  
**Project:** 1st Project — 1st Week  
**Status:** Completed

---

## 📌 Project Overview

This project documents my first practical cybersecurity laboratory exercise.

The purpose of this project was to deploy and run Kali Linux as a virtual machine using Oracle VirtualBox. The project provided practical experience with virtualization, Linux, system administration, networking, troubleshooting, and technical documentation.

The laboratory was performed on a Lenovo laptop running Windows with 4 GB of RAM.

---

## 🎯 Objectives

The main objectives of this project were to:

- Install and use Oracle VirtualBox
- Create a Kali Linux virtual machine
- Configure virtual machine resources
- Start and access Kali Linux
- Learn basic Linux terminal commands
- Check system information
- Identify network interfaces
- Test network connectivity
- Identify performance problems
- Troubleshoot limited system resources
- Document the work as part of a cybersecurity portfolio

---

## 🛠️ Technologies & Tools

| Technology / Tool | Purpose |
|---|---|
| Kali Linux | Cybersecurity-focused Linux operating system |
| Oracle VirtualBox | Virtualization platform |
| Windows | Host operating system |
| Linux Terminal | System administration and testing |
| GitHub | Project documentation and portfolio |

---

## 💻 Lab Environment

### Host Computer

| Component | Details |
|---|---|
| Computer | Lenovo laptop |
| Model/Type | 81H5 |
| Host Operating System | Windows |
| RAM | 4 GB |
| Virtualization Software | Oracle VirtualBox |

### Virtual Machine

| Resource | Configuration |
|---|---|
| Operating System | Kali Linux |
| Virtualization | Oracle VirtualBox |
| Network Mode | NAT |
| RAM | Configured according to available host resources |
| CPU | Configured according to available host resources |
| Storage | Virtual disk |

---

## 🏗️ Lab Architecture

```text
                 Lenovo Laptop
                Windows Host OS
                       │
                       │
               Oracle VirtualBox
                       │
                       │
                Kali Linux VM
                       │
              ┌────────┴────────┐
              │                 │
        Linux Terminal     Network Connection
              │                 │
       System Commands       Internet Test