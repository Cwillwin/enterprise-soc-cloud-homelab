# Enterprise SOC + Cloud Homelab

## Overview

This project documents the design and implementation of a hybrid enterprise security lab built to simulate real-world IT infrastructure and cybersecurity operations.

The lab includes:

- Active Directory domain infrastructure
- Windows and Linux servers
- Splunk SIEM for centralized logging
- pfSense firewall
- Suricata IDS/IPS
- Web, database, and API servers
- File server with AD permissions
- Help desk ticketing system
- Attack simulation environment
- AWS cloud infrastructure

The purpose of this lab is to develop hands-on experience with:

- Network security
- SIEM monitoring
- Windows and Linux administration
- Incident response workflows
- Cloud architecture
- Hybrid on-prem + cloud infrastructure


---

## Current Architecture

Current systems deployed:

| Hostname | Role |
|--------|------|
DC-01 | Primary Domain Controller |
DC-02 | Secondary Domain Controller |
WIN10-01 | Domain joined client |
SPLUNK-01 | SIEM log analysis server |

More infrastructure will be added in future phases.

---

## Technologies Used

### Infrastructure
- VirtualBox
- Windows Server
- Windows 10
- Ubuntu Server

### Security
- Splunk Enterprise
- Sysmon
- pfSense
- Suricata IDS

### Services
- Active Directory
- DNS
- SMB file shares
- Apache / Nginx
- MySQL
- REST APIs
- osTicket ticketing system

### Cloud
- AWS EC2
- AWS VPC
- AWS IAM
- AWS S3
- AWS CloudWatch

---

## Project Phases
[✔] Phase 1 — Core SOC Lab
[ ] Phase 2 — pfSense Firewall Deployment
[ ] Phase 3 — Suricata IDS Integration
[ ] Phase 4 — Enterprise File Server
[ ] Phase 5 — Ticketing System Deployment
[ ] Phase 6 — Web + Database Infrastructure
[ ] Phase 7 — API Development
[ ] Phase 8 — Attack Simulation Lab
[ ] Phase 9 — AWS Cloud Infrastructure
[ ] Phase 10 — Hybrid Monitoring and Security

---

## Skills Demonstrated

- Active Directory administration
- SIEM log analysis
- Windows event monitoring
- endpoint telemetry collection
- network security monitoring
- IDS/IPS deployment
- firewall configuration
- incident documentation
- infrastructure architecture
- cloud networking fundamentals

---

## Author

Caleb Williams  
Cybersecurity student and aspiring cloud/security engineer
