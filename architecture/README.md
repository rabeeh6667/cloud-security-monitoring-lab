# Architecture Documentation

## Overview

This directory contains the architecture design and visual documentation for the Cloud Security Monitoring & Threat Detection Lab.

The architecture demonstrates a cloud-based cybersecurity monitoring environment that simulates real-world attack scenarios, threat detection, and automated incident response.

## Architecture Diagram

![Architecture Diagram](cloud-security-lab-diagram.png)

## Lab Components

### Attack Workstation

**Operating System**

* Kali Linux

**Security Tools**

* Nmap
* Hydra
* Wireshark

**Purpose**

* Network reconnaissance
* Service enumeration
* SSH brute-force simulation
* Traffic capture and analysis

---

### Target Server

**Platform**

* AWS EC2 Ubuntu Server

**Services**

* Nginx Web Server
* OpenSSH

**Security Controls**

* Fail2Ban

**Purpose**

* Host vulnerable services for testing
* Generate security logs
* Demonstrate attack detection and response

---

### Log Sources

#### Authentication Logs

* SSH login attempts
* Successful authentications
* Failed authentication events

#### Web Server Logs

* Nginx access logs
* Nginx error logs

#### System Logs

* Service status events
* Security-related activities

---

## Attack Scenarios

### Scenario 1: Nmap Reconnaissance & Traffic Analysis

* Port scanning
* Service enumeration
* Packet capture with Wireshark
* Traffic analysis

### Scenario 2: SSH Brute Force Detection

* SSH configuration review
* Hydra attack simulation
* Authentication log analysis
* Evidence collection

### Scenario 3: Fail2Ban Detection & Automated Response

* Fail2Ban deployment
* SSH jail configuration
* Attack detection
* Automatic IP blocking

---

## Security Workflow

1. Reconnaissance activity is initiated from Kali Linux.
2. Network traffic is captured and analyzed using Wireshark.
3. SSH brute-force attempts are generated using Hydra.
4. Authentication failures are recorded on the target server.
5. Fail2Ban detects repeated failures.
6. The attacking IP address is automatically banned.
7. Detection evidence is collected and documented.

---

## Future Enhancements

* Wazuh SIEM Integration
* Threat Detection Dashboard
* Centralized Log Monitoring
* Security Alert Correlation
* SOC-Style Monitoring Environment

## Architecture Goals

* Demonstrate cloud security monitoring concepts
* Simulate realistic attack scenarios
* Validate detection capabilities
* Implement automated incident response
* Develop hands-on cybersecurity skills

