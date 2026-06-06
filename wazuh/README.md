# Wazuh SIEM Integration (Planned Enhancement)

## Overview

Wazuh is an open-source Security Information and Event Management (SIEM) platform that provides log collection, threat detection, security monitoring, file integrity monitoring, and incident response capabilities.

This project plans to integrate Wazuh to provide centralized security monitoring and a real-time threat detection dashboard.

## Objectives

* Centralize log collection from AWS Ubuntu servers
* Monitor SSH authentication events
* Detect brute-force login attempts
* Generate security alerts
* Visualize threats through a web-based dashboard
* Enhance incident response capabilities

## Planned Architecture

### Wazuh Server

* Wazuh Manager
* Wazuh Indexer
* Wazuh Dashboard

### Monitored Endpoint

* AWS EC2 Ubuntu Server
* Nginx Web Server
* OpenSSH
* Fail2Ban

### Log Sources

* Authentication Logs (`/var/log/auth.log`)
* Nginx Access Logs
* Nginx Error Logs
* System Logs

## Planned Detection Use Cases

### SSH Brute Force Detection

Monitor repeated failed SSH login attempts and generate alerts.

### Authentication Monitoring

Track successful and failed login events.

### Web Server Monitoring

Monitor Nginx access and error logs.

### Security Event Correlation

Correlate multiple events to identify suspicious activity.

## Future Dashboard Components

* Security Events Overview
* Authentication Failure Dashboard
* SSH Attack Monitoring
* Failed Login Alerts
* Endpoint Health Monitoring
* Threat Intelligence Integration

## Current Status

* [ ] Wazuh Server Deployment
* [ ] Wazuh Agent Installation
* [ ] Log Collection Configuration
* [ ] Dashboard Configuration
* [ ] Alert Validation
* [ ] Threat Detection Testing

## Future Work

The next phase of this project will involve deploying a dedicated Wazuh server with sufficient resources, connecting monitored endpoints, collecting security events, and validating threat detection capabilities through simulated attacks.

## Expected Outcome

The Wazuh integration will transform this lab into a Security Operations Center (SOC)-style environment capable of centralized monitoring, alerting, and security event analysis.

