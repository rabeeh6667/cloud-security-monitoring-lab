# Final Project Report

## Project Title

Cloud Security Monitoring & Threat Detection Lab

## Executive Summary

This project demonstrates the deployment of a cloud-based cybersecurity monitoring environment designed to simulate attacks, analyze security events, and validate automated response mechanisms.

The lab was built using AWS EC2, Ubuntu Server, Kali Linux, Nmap, Wireshark, Hydra, Nginx, OpenSSH, and Fail2Ban.

## Objectives

* Deploy cloud infrastructure
* Simulate realistic attacks
* Analyze network traffic
* Detect malicious activity
* Automate threat response
* Document findings

## Technologies Used

* AWS EC2
* Ubuntu Server
* Kali Linux
* Nmap
* Wireshark
* Hydra
* OpenSSH
* Nginx
* Fail2Ban

## Attack Scenarios

### Scenario 1: Nmap Reconnaissance & Traffic Analysis

Activities:

* Port scanning
* Service enumeration
* Packet capture

Results:

* Identified open services
* Captured network traffic
* Analyzed communication patterns

### Scenario 2: SSH Brute Force Detection

Activities:

* SSH security review
* Hydra attack simulation
* Authentication log analysis

Results:

* Failed login attempts detected
* Attack evidence collected
* Security events documented

### Scenario 3: Fail2Ban Automated Response

Activities:

* Fail2Ban deployment
* SSH jail configuration
* Attack detection validation

Results:

* Brute-force attack detected
* Attacking IP automatically blocked
* Automated response verified

## Key Findings

* Reconnaissance activities are easily identifiable through network analysis.
* Authentication logs provide critical indicators of compromise.
* Automated response mechanisms effectively mitigate brute-force attacks.
* Cloud-hosted services require continuous monitoring and protection.

## Future Enhancements

* Wazuh SIEM Integration
* Threat Detection Dashboard
* Centralized Log Monitoring
* Security Alert Correlation
* SOC-Style Monitoring Environment

## Conclusion

The project successfully demonstrated cloud security monitoring principles through attack simulation, threat detection, log analysis, and automated incident response. The lab provided practical experience with both offensive and defensive cybersecurity techniques and established a foundation for future SIEM integration and advanced monitoring capabilities.
