# Cloud Security Monitoring & Threat Detection Lab

A hands-on cloud security project demonstrating threat detection, SIEM monitoring, attack simulation, and incident response using AWS and open-source security tools.

## Technologies

- AWS EC2
- Ubuntu Server
- Kali Linux
- Wazuh SIEM
- Suricata IDS
- Nginx

## Skills Demonstrated

- AWS EC2 Administration
- Linux System Administration
- Network Security
- Threat Detection
- Security Monitoring
- Vulnerability Assessment
- Incident Response
- Cloud Security

## Architecture

Kali Linux → Ubuntu Target → Monitoring Platform

## Project Progress

- [x] AWS Account Setup
- [x] Ubuntu EC2 Deployment
- [x] Nginx Installation
- [x] Nmap Reconnaissance
- [x] Service Enumeration
- [x] Wireshark Traffic Analysis
- [x] SSH Security Hardening Analysis
- [x] SSH Brute Force Simulation
- [x] Authentication Log Analysis
- [x] Fail2Ban Detection & Response
- [ ] Threat Detection Dashboard
- [ ] Final Report

## Completed Milestones

### Milestone 1: Cloud Infrastructure Setup

* Created AWS EC2 Ubuntu Server
* Configured Security Groups
* Deployed Nginx Web Server

### Milestone 2: Reconnaissance & Traffic Analysis

* Performed Nmap Port Scanning
* Enumerated Running Services
* Captured and Analyzed Network Traffic using Wireshark
  
## Milestone 3: SSH Attack Detection & Log Analysis

- Analyzed SSH Security Configuration
- Enabled Password Authentication for Lab Testing
- Created Dedicated Test User
- Simulated SSH Brute Force Attack using Hydra
- Monitored Authentication Logs
- Identified Failed Login Attempts
- Documented Detection Evidence

## Milestone 4: Automated Threat Detection & Response

- Installed Fail2Ban
- Configured SSH Protection Jail
- Generated SSH Brute Force Attempts
- Detected Authentication Failures
- Automatically Banned Attacking IP
- Collected Detection Evidence

## Attack Scenarios

### Scenario 1: Nmap Reconnaissance & Traffic Analysis
- Port Scanning
- Service Enumeration
- Wireshark Packet Analysis

### Scenario 2: SSH Brute Force Detection
- SSH Security Configuration Review
- Hydra Brute Force Simulation
- Authentication Log Analysis
- Detection Evidence Collection

### Scenario 3: Fail2Ban Detection & Automated Response

- Fail2Ban Installation & Configuration
- SSH Protection Jail Setup
- Multiple Failed Login Attempt Simulation
- Authentication Failure Detection
- Automated IP Address Blocking
- Incident Response Validation
  
## Goal

Build a cloud-based Security Operations Center (SOC) lab capable of detecting and analyzing security threats in real time.
