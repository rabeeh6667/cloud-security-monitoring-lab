# Screenshots

This directory contains evidence collected during the Cloud Security Monitoring & Threat Detection Lab project.

## Infrastructure Setup

| Screenshot                         | Description                                               |
| ---------------------------------- | --------------------------------------------------------- |
| 01-aws-ubuntu-instance-running.png | AWS EC2 Ubuntu instance successfully deployed and running |
| 02-nginx-service-running.png       | Nginx web server service status                           |
| 03-nginx-webpage.png               | Nginx default web page accessible from the internet       |

## Reconnaissance & Traffic Analysis

| Screenshot                    | Description                                           |
| ----------------------------- | ----------------------------------------------------- |
| 04-wireshark-http-traffic.png | Network traffic captured and analyzed using Wireshark |
| 05-nmap-service-scan.png      | Nmap service enumeration and port scanning results    |

## SSH Security Testing

| Screenshot                   | Description                                               |
| ---------------------------- | --------------------------------------------------------- |
| 06-password-auth-enabled.png | SSH password authentication configuration for lab testing |
| 07-labuser-ssh-login.png     | Successful SSH login using the test account               |
| 08-hydra-attack.png          | SSH brute-force simulation using Hydra                    |
| 09-auth-log-failures.png     | Authentication log evidence showing failed login attempts |

## Automated Detection & Response

| Screenshot                     | Description                                              |
| ------------------------------ | -------------------------------------------------------- |
| 10-fail2ban-sshd-status.png    | Fail2Ban SSH protection jail status                      |
| 11-hydra-bruteforce-attack.png | Repeated SSH brute-force attack simulation               |
| 12-fail2ban-automatic-ban.png  | Automatic IP blocking by Fail2Ban after attack detection |

## Security Monitoring Dashboard

| Screenshot                           | Description                                                   |
| ------------------------------------ | ------------------------------------------------------------- |
| 13-monitoring-server-preparation.png | Dedicated monitoring server prepared for dashboard deployment |
| 14-grafana-service-running.png       | Grafana service successfully installed and running            |
| 15-grafana-login-screen.png          | Grafana web interface login page                              |
| 16-grafana-home-dashboard.png        | Grafana dashboard successfully deployed and accessible        |
| 17-loki-installation.png | Loki log aggregation service successfully installed |

## Architecture

The project architecture diagram is located in:

```text
architecture/cloud-security-lab-diagram.png
```

## Upcoming Dashboard Evidence

Planned screenshots for Version 2 completion:

* SSH Failed Login Dashboard
* Fail2Ban Events Dashboard
* Nginx Access Monitoring Dashboard
* Security Overview Dashboard
* Loki Data Source Configuration
* Centralized Log Monitoring Dashboard
* Threat Detection Visualizations

## Evidence Collection Purpose

The screenshots in this directory provide visual evidence of:

* Cloud infrastructure deployment
* Network reconnaissance activities
* Traffic analysis procedures
* SSH attack simulation
* Authentication log analysis
* Automated threat detection
* Incident response actions
* Security monitoring dashboard deployment

  | 17-loki-installation.png | Loki log aggregation service successfully installed |
