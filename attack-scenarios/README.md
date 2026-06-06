# Attack Scenarios

## Overview

This directory contains documented attack simulations performed as part of the Cloud Security Monitoring & Threat Detection Lab.

The scenarios demonstrate the attack lifecycle from reconnaissance to threat detection and automated response within a controlled cloud-based environment.

## Lab Environment

### Attacker

* Kali Linux

### Target

* AWS EC2 Ubuntu Server
* Nginx Web Server
* OpenSSH

### Security Controls

* Fail2Ban

### Monitoring Sources

* Authentication Logs
* Nginx Access Logs
* System Logs

---

## Scenario 1: Nmap Reconnaissance & Traffic Analysis

**File:** `01-nmap-reconnaissance.md`

### Objective

Identify exposed services and analyze network traffic generated during reconnaissance activities.

### Tools Used

* Nmap
* Wireshark

### Activities

* Port scanning
* Service enumeration
* Traffic capture
* Packet analysis

### Key Findings

* SSH service identified
* HTTP service identified
* Network traffic successfully captured and analyzed

---

## Scenario 2: SSH Brute Force Detection

**File:** `02-ssh-bruteforce.md`

### Objective

Simulate an SSH brute-force attack and analyze authentication logs.

### Tools Used

* Hydra
* OpenSSH

### Activities

* SSH login testing
* Password attack simulation
* Authentication log monitoring

### Key Findings

* Failed login attempts detected
* Authentication events recorded
* Attack evidence collected

---

## Scenario 3: Fail2Ban Detection & Automated Response

**File:** `03-fail2ban-response.md`

### Objective

Demonstrate automated detection and blocking of SSH brute-force attacks.

### Tools Used

* Fail2Ban
* Hydra

### Activities

* SSH jail configuration
* Attack simulation
* Detection monitoring
* Automated IP blocking

### Key Findings

* Attack detected successfully
* Authentication failures monitored
* Attacking IP automatically blocked

---

## Security Workflow

1. Reconnaissance using Nmap
2. Traffic analysis using Wireshark
3. SSH brute-force simulation using Hydra
4. Authentication log monitoring
5. Threat detection using Fail2Ban
6. Automated incident response

## Lessons Learned

* Reconnaissance activities generate identifiable network traffic.
* Authentication failures provide valuable detection indicators.
* Log monitoring is essential for threat detection.
* Automated response mechanisms reduce attack effectiveness.
* Cloud-hosted systems require continuous monitoring and protection.

## Future Enhancements

* Wazuh SIEM Integration
* Threat Detection Dashboard
* Centralized Log Collection
* Security Alert Correlation
* Advanced Detection Rules

