# NetSec Lab Socket Suite (Single-Client)

> **Educational Use Only** – This project is intended for use in a **controlled lab environment** that you own or have explicit permission to test.  
> Some features (e.g., ARP spoofing, DoS) can disrupt networks and must **never** be run on public or unauthorized systems.

---

## 📌 Overview
The **NetSec Lab Socket Suite** is a Python-based, single-client **server + client** system designed for demonstrating and practicing core offensive network security techniques in a safe, isolated environment.

It showcases:
- Socket programming in Python
- Real-time server-client communication
- Network enumeration and attack simulation techniques
- Centralized logging for auditability
- Integration with Kali Linux’s **rockyou.txt** wordlist

---

## 🚀 Features
- **Port Scanning & Banner Grabbing** – Scan custom ports and retrieve banners
- **Brute Force Modules**:
  - Web login (form-based)
  - FTP
  - SSH
  - All using **rockyou.txt**
- **ARP Scan & ARP Spoofing** *(Lab Only)* – Discover devices or poison ARP tables
- **DoS Simulation** *(Lab Only)*:
  - ICMP Flood
  - SYN Flood
- **Timestamped Messages** – Every server response includes a timestamp
- **Centralized Logging** – All actions logged to `server_client_log.txt` with client IP and timestamp
- **Clean Menu-Driven UI** – Easy to navigate over the client socket interface

---

## 🗂 Project Structure
MYSERVER.py # Server code (single-client)
client.py # Simple cross-platform client

## ⚙ Requirements
- **Python:** 3.9+
- **OS:** Linux (Kali recommended for rockyou integration), macOS, or Windows (client only)
- **Dependencies:**
  ```bash
  pip install -r requirements.txt

Kali rockyou.txt wordlist:
sudo apt install wordlists
sudo gunzip /usr/share/wordlists/rockyou.txt.gz    # if gzipped

🏆 About This Project
Built as part of a cybersecurity portfolio to demonstrate:
Secure lab environment setup
Network attack simulation in Python
Logging and timestamp integration
Professional project documentation

🔒 Ethical & Legal Notes
Do NOT use this tool on networks, devices, or accounts without explicit written permission.
ARP spoofing, flooding, and brute force attacks are disruptive and should only be tested in a private lab.
You are responsible for understanding and complying with applicable laws.
