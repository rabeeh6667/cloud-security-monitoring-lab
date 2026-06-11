# Grafana Monitoring Dashboard

## Overview

Grafana was deployed as the centralized monitoring platform for the Cloud Security Monitoring & Threat Detection Lab.

The monitoring environment provides real-time visibility into infrastructure performance, system health, and operational metrics collected from the monitoring server.

---

## Monitoring Architecture

```text
Node Exporter
       │
       ▼
Prometheus
       │
       ▼
Grafana
       │
       ▼
Security Monitoring Dashboard
```

---

## Technologies Used

* Grafana
* Prometheus
* Node Exporter
* AWS EC2
* Ubuntu Server

---

## Components

### Grafana

Responsibilities:

* Dashboard Visualization
* Infrastructure Monitoring
* Performance Analytics
* Data Visualization

### Prometheus

Responsibilities:

* Metrics Collection
* Time-Series Data Storage
* Monitoring Backend

### Node Exporter

Responsibilities:

* System Metrics Collection
* CPU Monitoring
* Memory Monitoring
* Disk Monitoring
* Network Monitoring

---

## Dashboard Capabilities

The monitoring dashboard provides visibility into:

* CPU Utilization
* Memory Usage
* Disk Usage
* Network Traffic
* System Load
* System Uptime
* Infrastructure Health

---

## Deployment Process

### Step 1: Monitoring Server Setup

* Deployed dedicated AWS EC2 monitoring server
* Configured network access
* Verified server resources

### Step 2: Grafana Installation

* Installed Grafana
* Configured dashboard access
* Verified service availability

### Step 3: Prometheus Installation

* Installed Prometheus
* Started monitoring services
* Verified metric collection

### Step 4: Node Exporter Installation

* Installed Node Exporter
* Enabled system metric collection
* Verified metrics endpoint

### Step 5: Dashboard Configuration

* Added Prometheus data source
* Imported Node Exporter dashboard
* Validated dashboard functionality

---

## Screenshots

| Screenshot                           | Description                       |
| ------------------------------------ | --------------------------------- |
| 16-grafana-home-dashboard.png        | Grafana dashboard access          |
| 17-monitoring-server-preparation.png | Monitoring server setup           |
| 18-node-exporter-metrics.png         | Node Exporter metrics collection  |
| 19-prometheus-running.png            | Prometheus service running        |
| 20-prometheus-datasource.png         | Prometheus data source configured |
| 21-security-monitoring-dashboard.png | Security monitoring dashboard     |

---

## Key Outcomes

* Successfully deployed a centralized monitoring platform
* Collected real-time infrastructure metrics
* Built an operational monitoring dashboard
* Visualized system performance and health metrics
* Extended the project into a SOC-style monitoring environment

---

## Future Enhancements

* Deploy Wazuh SIEM for centralized log monitoring
* Build SSH authentication monitoring dashboards
* Create Fail2Ban event dashboards
* Implement security alert correlation
* Configure real-time security alerting
* Monitor multiple endpoints from a centralized dashboard
