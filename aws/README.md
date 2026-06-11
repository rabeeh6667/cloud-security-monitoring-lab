# AWS Deployment

## Overview

AWS EC2 was used to deploy and host the Cloud Security Monitoring & Threat Detection Lab environment.

The deployment consists of a target server used for attack simulation and a dedicated monitoring server used for infrastructure monitoring and dashboard visualization.

---

## AWS Infrastructure

### Target Server

Purpose:

* Web Server Hosting
* SSH Services
* Security Testing Target

Configuration:

* Ubuntu Server
* Nginx Web Server
* OpenSSH
* Fail2Ban

Functions:

* Service Enumeration
* Authentication Monitoring
* Attack Simulation
* Automated Threat Response

---

### Monitoring Server

Purpose:

* Infrastructure Monitoring
* Metrics Collection
* Dashboard Visualization

Configuration:

* Ubuntu Server
* Grafana
* Prometheus
* Node Exporter

Functions:

* System Monitoring
* Performance Analytics
* Dashboard Visualization
* Infrastructure Health Monitoring

---

## AWS Services Used

### Amazon EC2

Used for:

* Ubuntu Server Deployment
* Monitoring Server Deployment
* Security Testing Environment

### Security Groups

Configured for:

* SSH Access (Port 22)
* HTTP Access (Port 80)
* Grafana Access (Port 3000)
* Monitoring Services

---

## Deployment Process

### Phase 1: Target Server Deployment

* Created Ubuntu EC2 instance
* Configured Security Groups
* Connected using SSH
* Updated system packages
* Installed Nginx
* Installed Fail2Ban

### Phase 2: Security Testing Environment

* Configured OpenSSH
* Enabled lab authentication testing
* Created dedicated test account
* Performed attack simulations

### Phase 3: Monitoring Platform Deployment

* Created monitoring server
* Installed Grafana
* Installed Prometheus
* Installed Node Exporter
* Configured monitoring dashboard

---

## Security Configuration

Implemented controls:

* Security Group Rules
* SSH Access Control
* Fail2Ban Protection
* Automated IP Blocking
* Infrastructure Monitoring

---

## Architecture Summary

```text id="0qyw0g"
AWS EC2 Environment

├── Target Server
│   ├── Ubuntu Server
│   ├── Nginx
│   ├── OpenSSH
│   └── Fail2Ban
│
└── Monitoring Server
    ├── Grafana
    ├── Prometheus
    └── Node Exporter
```

---

## Key Outcomes

* Successfully deployed cloud-based infrastructure
* Configured security monitoring environment
* Performed attack simulation activities
* Implemented automated incident response
* Built a centralized monitoring dashboard
* Demonstrated cloud security operations concepts

---

## Future Enhancements

* Wazuh SIEM Deployment
* Centralized Log Collection
* Multi-Host Monitoring
* Security Alert Correlation
* Real-Time Security Alerting
* Expanded SOC Monitoring Environment
