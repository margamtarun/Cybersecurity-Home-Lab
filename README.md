# Cybersecurity Home Lab

## Overview
This project demonstrates the creation of a cybersecurity home lab using Kali Linux and Windows 10 virtual machines. The lab simulates a real-world network environment to practice reconnaissance and service enumeration.

## Tools Used
- VirtualBox
- Kali Linux
- Windows 10
- Nmap
- TCP/IP Networking

## Lab Architecture
- Kali Linux (Attacker Machine)
- Windows 10 (Target Machine)
- Host-Only Networking Configuration

## Network Configuration
- Windows IP: 192.168.56.101
- Kali IP: 192.168.56.102
- Host-only network used for isolated communication

## Nmap Scanning Results

Basic Scan:
```bash
nmap 192.168.56.101

Discovered Open Port 
- 139/tcp — NetBIOS
- 445/tcp — SMB
- 3389/tcp — Remote Desktop Protocol (RDP)

Service Version Detection:
nmap -sV 192.168.56.101

Skills Demonstrated
- Virtual Machine Deployment
- Network Configuration
- Port Scanning
- Service Enumeration
- Firewall Configuration
- Network Troubleshooting
- Cybersecurity Reconnaissance

Future Improvements
- Vulnerability scanning
- SMB enumeration
- OS detection scans
- Automated Nmap scripting

Author
Tarun Margam
