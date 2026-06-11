# Architecture

## Overview

The Cloud Security Monitoring & Threat Detection Lab consists of an attack workstation, a target server, and a dedicated monitoring platform.

The environment simulates common security operations activities including reconnaissance, attack simulation, threat detection, incident response, and infrastructure monitoring.

---

## Architecture Diagram

The architecture diagram is located in:

```text
cloud-security-lab-diagram.png
```

---

## Architecture Components

### Kali Linux Attack Workstation

Purpose:

* Security Testing
* Reconnaissance
* Attack Simulation

Tools:

* Nmap
* Hydra
* Wireshark

---

### AWS Ubuntu Target Server

Purpose:

* Attack Target
* Service Hosting
* Security Monitoring

Services:

* Nginx Web Server
* OpenSSH
* Fail2Ban

Functions:

* Service Enumeration
* Authentication Monitoring
* Automated Threat Response

---

### Monitoring Server

Purpose:

* Infrastructure Monitoring
* Metrics Collection
* Dashboard Visualization

Components:

* Grafana
* Prometheus
* Node Exporter

Functions:

* System Monitoring
* Performance Analytics
* Dashboard Visualization
* Infrastructure Health Monitoring

---

## Data Flow

```text
Kali Linux
(Attack Workstation)
        │
        ▼
AWS Ubuntu Target Server
(Nginx + OpenSSH + Fail2Ban)
        │
        ├── Authentication Events
        ├── Security Events
        └── System Metrics
                │
                ▼
Monitoring Server
(Prometheus + Node Exporter)
                │
                ▼
Grafana Dashboard
                │
                ▼
Security Monitoring & Visualization
```

---

## Security Workflow

### Phase 1: Reconnaissance

* Nmap scans target server
* Open ports identified
* Running services enumerated

### Phase 2: Attack Simulation

* Hydra generates SSH brute-force attempts
* Authentication failures recorded
* Security events generated

### Phase 3: Threat Detection

* Authentication logs analyzed
* Failed login attempts identified
* Security events documented

### Phase 4: Automated Response

* Fail2Ban detects repeated failures
* Attacking IP address blocked
* Incident response validated

### Phase 5: Monitoring & Visualization

* Node Exporter collects system metrics
* Prometheus stores monitoring data
* Grafana visualizes infrastructure health

---

## Key Capabilities

* Cloud Infrastructure Deployment
* Security Monitoring
* Threat Detection
* Attack Simulation
* Authentication Log Analysis
* Automated Incident Response
* Dashboard-Based Monitoring
* Infrastructure Visualization

---

## Future Enhancements

* Wazuh SIEM Deployment
* Centralized Log Collection
* Security Alert Correlation
* Real-Time Alerting
* Multi-Host Monitoring
* SOC-Style Security Operations
