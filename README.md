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