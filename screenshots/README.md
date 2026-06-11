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

| Screenshot                           | Description                       |
| ------------------------------------ | --------------------------------- |
| 13-monitoring-server-running.png     | Monitoring server deployment      |
| 14-grafana-service-running.png       | Grafana service running           |
| 15-grafana-login-screen.png          | Grafana login page                |
| 16-grafana-home-dashboard.png        | Grafana dashboard access          |
| 17-monitoring-server-preparation.png | Monitoring server setup           |
| 18-node-exporter-metrics.png         | Node Exporter metrics collection  |
| 19-prometheus-running.png            | Prometheus service running        |
| 20-prometheus-datasource.png         | Prometheus data source configured |
| 21-security-monitoring-dashboard.png | Security monitoring dashboard     |

## Architecture

The project architecture diagram is located in:

```text
architecture/cloud-security-lab-diagram.png
```
