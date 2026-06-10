# Cloud Security Monitoring & Threat Detection Lab

A hands-on cloud security project demonstrating attack simulation, threat detection, log analysis, and automated incident response using AWS and open-source security tools.

## Project Status

### Version 1.0 (Completed)

Version 1 focuses on cloud infrastructure deployment, attack simulation, security monitoring, and automated incident response.

**Implemented Components**

* AWS EC2 Ubuntu Server
* Nginx Web Server
* OpenSSH
* Nmap Reconnaissance
* Wireshark Traffic Analysis
* Hydra SSH Brute Force Simulation
* Authentication Log Analysis
* Fail2Ban Automated Response
* Security Documentation & Reporting

### Version 2.0 (In Progress)

Version 2 extends the lab into a SOC-style monitoring environment using Grafana and Loki for centralized log monitoring and threat visualization.

**Planned Components**

* Grafana Dashboard
* Loki Log Aggregation
* Promtail Log Collection
* SSH Authentication Monitoring
* Fail2Ban Event Monitoring
* Security Event Visualization
* Threat Detection Dashboard
* Security Analytics & Reporting

---

## Architecture Diagram

This diagram illustrates the cloud security monitoring lab environment, including the attack workstation, target server, security controls, and log sources used for threat detection and analysis.

![Architecture Diagram](architecture/cloud-security-lab-diagram.png)

---

## Technologies Used (Version 1)

### Cloud & Infrastructure

* AWS EC2
* Ubuntu Server
* Kali Linux

### Security & Monitoring

* Nmap
* Wireshark
* Hydra
* OpenSSH
* Fail2Ban
* Nginx

### Planned Technologies (Version 2)

* Grafana
* Loki
* Promtail
* Threat Detection Dashboard

---

## Skills Demonstrated

* AWS EC2 Administration
* Linux System Administration
* Network Security
* Threat Detection
* Security Monitoring
* Vulnerability Assessment
* Incident Response
* Cloud Security
* Security Log Analysis
* Security Operations Fundamentals
* Dashboard Deployment & Monitoring

---

## Architecture

```text
Kali Linux (Attacker)
        │
        ▼
AWS Ubuntu Target Server
(Nginx + OpenSSH + Fail2Ban)
        │
        ▼
Authentication Logs & Nginx Logs
        │
        ▼
Loki
        │
        ▼
Grafana Dashboard
```

---

## Project Progress

### Version 1.0

* [x] AWS Account Setup
* [x] Ubuntu EC2 Deployment
* [x] Nginx Installation
* [x] Nmap Reconnaissance
* [x] Service Enumeration
* [x] Wireshark Traffic Analysis
* [x] SSH Security Hardening Analysis
* [x] SSH Brute Force Simulation
* [x] Authentication Log Analysis
* [x] Fail2Ban Detection & Response
* [x] Final Report

### Version 2.0

* [x] Monitoring Server Deployment
* [x] Grafana Installation
* [x] Grafana Dashboard Access
* [ ] Loki Installation
* [ ] Promtail Configuration
* [ ] Centralized Log Collection
* [ ] Threat Detection Dashboard
* [ ] Security Event Visualization
* [ ] Security Monitoring Analyticss

---

## Completed Milestones

### Milestone 1: Cloud Infrastructure Setup

* Created AWS EC2 Ubuntu Server
* Configured Security Groups
* Deployed Nginx Web Server

### Milestone 2: Reconnaissance & Traffic Analysis

* Performed Nmap Port Scanning
* Enumerated Running Services
* Captured and Analyzed Network Traffic using Wireshark

### Milestone 3: SSH Attack Detection & Log Analysis

* Analyzed SSH Security Configuration
* Enabled Password Authentication for Lab Testing
* Created Dedicated Test User
* Simulated SSH Brute Force Attack using Hydra
* Monitored Authentication Logs
* Identified Failed Login Attempts
* Documented Detection Evidence

### Milestone 4: Automated Threat Detection & Response

* Installed Fail2Ban
* Configured SSH Protection Jail
* Generated SSH Brute Force Attempts
* Detected Authentication Failures
* Automatically Banned Attacking IP
* Collected Detection Evidence

### Milestone 5: Security Monitoring Dashboard

- Deployed Dedicated Monitoring Server
- Installed Grafana
- Configured Dashboard Access
- Prepared Centralized Monitoring Platform
- Verified Dashboard Availability

---

## Attack Scenarios

### Scenario 1: Nmap Reconnaissance & Traffic Analysis

* Port Scanning
* Service Enumeration
* Wireshark Packet Analysis

### Scenario 2: SSH Brute Force Detection

* SSH Security Configuration Review
* Hydra Brute Force Simulation
* Authentication Log Analysis
* Detection Evidence Collection

### Scenario 3: Fail2Ban Detection & Automated Response

* Fail2Ban Installation & Configuration
* SSH Protection Jail Setup
* Multiple Failed Login Attempt Simulation
* Authentication Failure Detection
* Automated IP Address Blocking
* Incident Response Validation

---

## Future Enhancements (Version 2)

* Deploy Grafana Dashboard
* Deploy Loki Log Aggregation
* Configure Promtail Log Collection
* Build SSH Authentication Dashboard
* Build Fail2Ban Monitoring Dashboard
* Build Security Event Overview Dashboard
* Implement Real-Time Threat Monitoring
* Expand into a SOC-Style Monitoring Environment

---

## Goal

Build a cloud-based Security Operations Center (SOC) lab capable of detecting, monitoring, visualizing, and responding to security threats in real time.
