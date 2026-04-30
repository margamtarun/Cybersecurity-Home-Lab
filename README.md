# Cybersecurity Home Lab – Network Reconnaissance & Vulnerability Scanning

## Overview
Designed and implemented a cybersecurity home lab using Kali Linux and Windows virtual machines to perform network reconnaissance, service enumeration, and vulnerability scanning using industry-standard tools.

## Lab Environment
- **Attacker Machine:** Kali Linux
- **Target Machine:** Windows 10/11
- **Virtualization Platform:** Oracle VirtualBox
- **Network Type:** Host-Only Network
- **Network Range:** 192.168.56.0/24

## Tools Used
- Kali Linux
- Nmap
- SMB Enumeration Tools
- Oracle VirtualBox
- Windows Defender Firewall

## Key Activities Performed
- Configured virtualized cybersecurity lab environment
- Established host-only network communication between machines
- Performed network discovery and host identification
- Conducted TCP port scanning using Nmap
- Identified open ports and running services
- Performed service version detection
- Conducted operating system fingerprinting
- Executed vulnerability scanning using NSE scripts
- Performed SMB enumeration
- Generated structured scan reports

## Scan Results Summary

**Target IP:** 192.168.56.101  

**Open Ports Identified:**
- **139/tcp** – NetBIOS Session Service
- **445/tcp** – Microsoft SMB
- **3389/tcp** – Remote Desktop Protocol (RDP)
- **7680/tcp** – Windows Update Service

**Operating System Identified:**
- Microsoft Windows (Detected via OS Fingerprinting)

## Files Included
- `full_scan.txt` — Full scan output results
- `lab_scan.nmap` — Standard Nmap scan output
- `lab_scan.xml` — XML formatted scan output
- `lab_scan.gnmap` — Grepable Nmap output

## Skills Demonstrated
- Network Scanning
- Service Enumeration
- Vulnerability Scanning
- OS Detection
- Network Configuration
- Virtual Machine Deployment
- Firewall Configuration
- SMB Enumeration
- Cybersecurity Lab Setup

## Author
**Tarun Margam**
Cybersecurity Graduate Student
