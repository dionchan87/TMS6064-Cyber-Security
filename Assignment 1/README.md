# Assignment 1 — Reconnaissance & Maintaining Access Tools

This assignment demonstrates the use of several Kali Linux tools for performing **reconnaissance** and **maintaining access** in a controlled, ethical environment.  
All commands and tests were executed on **local, safe targets only** such as `127.0.0.1` and `example.com`.

---

# Disclaimer
This project is strictly for **educational purposes only**.  
All testing was performed in a **controlled environment**, using **authorized targets**.  
No real-world systems, networks, or third-party IP addresses were targeted.

---

# Task 1 — Reconnaissance Tools
Reconnaissance tools are used to collect information about a target before attempting any form of exploitation.  
In this task, the following tools were tested:

- **Nmap**  
- **Recon-ng**  
- **Hping3**  
- **DNSRecon**

---

# 1. Nmap
Nmap is a widely-used network scanning tool for discovering hosts, ports and services on a network.

---

## Feature 1: Ping Scan
![Nmap Ping Scan](screenshots/nmap1.png)

**Explanation:**  
A ping scan checks whether the target host is online without doing a full port scan.  
Penetration testers use this to confirm the device is active before gathering deeper information.

---

## 🔹 Feature 2: Basic Port Scan

screenshot

**Explanation:**  
A basic port scan identifies which ports are open on the machine.  
This helps determine what services might be running and potentially vulnerable.

---

## 🔹 Feature 3: Service Version Detection
