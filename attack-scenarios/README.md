# Attack Scenarios

This document describes the attack simulations performed during the Cloud Security Monitoring & Threat Detection Lab and the corresponding detection and response activities.

---

## Scenario 1: Nmap Reconnaissance & Traffic Analysis

### Objective

Identify exposed services running on the target server and analyze network traffic generated during reconnaissance activities.

### Tools Used

* Kali Linux
* Nmap
* Wireshark

### Activities Performed

* Conducted TCP port scanning against the target server
* Enumerated running services
* Identified open network ports
* Captured network traffic using Wireshark
* Analyzed packet-level communication

### Evidence Collected

* Nmap scan results
* Service enumeration results
* Packet capture analysis

### Outcome

Successfully identified exposed services and analyzed network traffic generated during reconnaissance operations.

---

## Scenario 2: SSH Brute Force Detection

### Objective

Simulate an SSH brute-force attack and identify authentication failures through system log analysis.

### Tools Used

* Kali Linux
* Hydra
* OpenSSH
* Ubuntu Server

### Activities Performed

* Enabled password authentication for lab testing
* Created a dedicated test account
* Generated multiple SSH login attempts using Hydra
* Monitored authentication logs
* Identified failed login events

### Evidence Collected

* Hydra attack output
* Authentication log entries
* Failed login records

### Outcome

Successfully simulated an SSH brute-force attack and detected authentication failures through log analysis.

---

## Scenario 3: Fail2Ban Detection & Automated Response

### Objective

Validate automated threat detection and response capabilities using Fail2Ban.

### Tools Used

* Fail2Ban
* OpenSSH
* Ubuntu Server

### Activities Performed

* Installed and configured Fail2Ban
* Enabled SSH protection jail
* Generated repeated failed login attempts
* Monitored Fail2Ban activity
* Verified automatic IP address blocking

### Evidence Collected

* Fail2Ban status output
* Authentication failure logs
* Banned IP address records

### Outcome

Successfully detected repeated authentication failures and automatically blocked the attacking IP address.

---

## Security Monitoring Dashboard

### Objective

Deploy a centralized monitoring platform to visualize infrastructure and security-related metrics.

### Tools Used

* Grafana
* Prometheus
* Node Exporter

### Activities Performed

* Deployed dedicated monitoring server
* Installed Grafana
* Configured Prometheus monitoring
* Collected system metrics using Node Exporter
* Built monitoring dashboard

### Evidence Collected

* Grafana dashboard screenshots
* Prometheus service status
* Node Exporter metrics output

### Outcome

Successfully deployed a real-time monitoring dashboard capable of visualizing infrastructure performance and system health metrics.

---

## Summary

The lab demonstrated the complete lifecycle of:

1. Reconnaissance and service discovery
2. SSH attack simulation
3. Log-based threat detection
4. Automated incident response
5. Security monitoring and visualization

These activities collectively simulate core Security Operations Center (SOC) functions within a cloud-based environment.
