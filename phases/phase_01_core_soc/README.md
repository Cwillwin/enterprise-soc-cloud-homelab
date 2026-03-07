# Phase 1 — Core SOC Lab

## Objective

Deploy a foundational Security Operations Center (SOC) environment with centralized logging to monitor activity inside a Windows Active Directory domain.

---

## Infrastructure

| System | Role |
|------|------|
| DC-01 | Primary Domain Controller |
| DC-02 | Secondary Domain Controller |
| WIN10-01 | Domain Client |
| SPLUNK-01 | SIEM Server |

---

## Key Features

- Active Directory domain deployed
- Windows 10 client joined to the domain
- Splunk Enterprise deployed on Ubuntu
- Splunk Universal Forwarders installed
- Windows event logs forwarded to SIEM

---

## Security Value

Centralized logging allows monitoring of:

- authentication events
- account lockouts
- privilege escalation
- suspicious login activity

This provides the foundation for a functional SOC monitoring environment.

---

## Challenges Encountered

### SMB Access Issue

Accessing network shares using hostname initially failed.

Example:

\\WIN10-01

Access using the IP address worked correctly.

### Root Cause

DNS resolution and virtualization integration issues.

### Fix

Installing VirtualBox Guest Additions on the domain controller stabilized networking and resolved hostname access issues.

---

## Outcome

The lab now supports:

- domain authentication
- centralized logging
- endpoint monitoring
- SOC visibility into authentication events
