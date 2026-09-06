# 🔐 Cybersecurity Lab — Week 01

## Kali Linux Deployment & Virtualization with Oracle VirtualBox

---

## 📌 Project Overview

This project documents my first practical cybersecurity laboratory exercise.

The objective was to build a virtual cybersecurity laboratory environment for penetration-testing and ethical-hacking practice by deploying Kali Linux v2026.2 using VirtualBox v7.2.

The project provided practical experience with virtualization, Linux, system administration, networking, troubleshooting, and technical documentation.

The laboratory was performed on a Lenovo laptop running Windows with 4 GB of RAM.

---

## 🎯 Objectives

The main objectives of this project were to:

- Install and use VirtualBox
- Create a Kali Linux virtual machine
- Configure virtual machine resources
- Start and access Kali Linux
- Learn basic Linux terminal commands
- Check system information
- Identify network interfaces
- Test network connectivity
- Identify performance limitations
- Troubleshoot limited system resources
- Build a practical cybersecurity laboratory environment
- Document the work as part of a cybersecurity portfolio

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
| Virtualization | VirtualBox v7.2 |
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
                VirtualBox v7.2
                       │
                       │
              Kali Linux v2026.2
                       │
              ┌────────┴────────┐
              │                 │
        Linux Terminal     Network Connection
              │                 │
       System Commands       Internet Test