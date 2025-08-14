# netsec-lab-socket-suite
Single-client Python server + client for lab-only netsec demos: port scanning, ARP scan/spoof, FTP/SSH/Web brute-force via rockyou, DoS modules, timestamps, centralized logging. Educational use only.

# NetSec Lab Socket Suite (Single-Client)

> **Educational use only – run in a controlled lab you own or have explicit permission to test.**  
> Some features (ARP spoof, DoS) require root/admin privileges and can disrupt networks.  
> This project is for demonstrating skills, not for unauthorized access.

## Overview
Python single-client **server + client** showcasing network-security techniques for **portfolio/learning**:
- Port scanning with banner grab
- ARP scan & ARP spoof (lab only)
- Brute force modules (Web login, FTP, SSH) using **Kali’s `rockyou.txt`**
- DoS modules (ICMP flood, SYN flood) – **lab only**
- **Timestamps** on every message & **centralized logging** (`server_client_log.txt`)
- Clean, menu-driven UI over a socket client

## Why this is useful
- Demonstrates sockets, network protocols, and Python automation
- Shows responsible handling: timestamps, logging, clear lab-only disclaimers
- HR/Interviewers can run it quickly and see structured output

## Project Structure
