# SOC Simulation Lab using VMware and Splunk SIEM

## Overview

This project demonstrates a Security Operations Center (SOC) simulation lab built using VMware virtual machines and Splunk SIEM.

The lab consists of:

- Kali Linux (Attacker Machine)
- Metasploitable 2 (Target Machine)
- Ubuntu Server (Log Source)
- Splunk Enterprise (SIEM)

The objective is to simulate cyber attacks, generate security logs, and detect suspicious activities using centralized log monitoring and analysis.

---

## Technologies Used

- VMware Workstation
- Kali Linux
- Ubuntu Server
- Metasploitable 2
- Splunk Enterprise
- Nmap
- Hydra

---

## Architecture

The SOC environment consists of:

1. Kali Linux → Attack Simulation
2. Metasploitable → Vulnerable Target
3. Ubuntu Server → Log Source
4. Splunk → SIEM Analysis

---

## Simulated Attacks

### Network Scanning
- Nmap Port Scanning
- Service Enumeration

### Brute Force Attack
- Hydra SSH Brute Force

---

## Log Analysis

Security logs were collected and analyzed using Splunk SPL queries to detect:

- Failed Login Attempts
- Successful SSH Logins
- Brute Force Activity
- Suspicious IP Addresses

---

## Key Skills Demonstrated

- SIEM Monitoring
- Log Analysis
- Threat Detection
- Incident Investigation
- Network Security
- Linux Administration
- Cybersecurity Operations

---

## Project Outcome

Successfully created a virtual SOC environment capable of:

- Simulating cyber attacks
- Collecting security logs
- Detecting malicious activities
- Visualizing threats using Splunk Dashboards
