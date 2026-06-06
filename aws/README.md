# AWS Infrastructure Documentation

## Overview

This directory contains documentation related to the AWS cloud infrastructure used for the Cloud Security Monitoring & Threat Detection Lab.

The AWS environment provides the target systems used for attack simulation, log generation, threat detection, and automated response testing.

## Cloud Environment

### Cloud Provider

* Amazon Web Services (AWS)

### Service Used

* Amazon EC2

---

## EC2 Instances

### Target Server

**Purpose**

* Primary attack target
* Service hosting
* Log generation

**Operating System**

* Ubuntu Server

**Services Installed**

* Nginx
* OpenSSH
* Fail2Ban

**Security Features**

* SSH access control
* Authentication logging
* Automated attack mitigation

---

### Wazuh Server (Planned Enhancement)

**Purpose**

* Centralized security monitoring
* Threat detection dashboard
* Log aggregation

**Operating System**

* Ubuntu Server

**Planned Components**

* Wazuh Manager
* Wazuh Dashboard
* Wazuh Indexer

---

## Security Group Configuration

### Inbound Rules

| Port | Protocol | Purpose     |
| ---- | -------- | ----------- |
| 22   | TCP      | SSH Access  |
| 80   | TCP      | HTTP Access |

### Security Considerations

* Restricted administrative access
* Controlled exposure of services
* Cloud-hosted attack simulation environment

---

## Infrastructure Deployment Steps

### 1. EC2 Instance Creation

* Created Ubuntu Server instance
* Configured networking
* Assigned public IP address

### 2. Service Deployment

* Installed Nginx
* Enabled OpenSSH
* Configured Fail2Ban

### 3. Security Testing

* Nmap reconnaissance
* SSH brute-force simulation
* Traffic analysis
* Automated response validation

---

## Infrastructure Components

### Web Service

* Nginx Web Server
* HTTP Service
* Access Log Generation

### Remote Access Service

* OpenSSH
* Secure Remote Administration
* Authentication Monitoring

### Security Controls

* Fail2Ban
* Automated IP Blocking
* Brute Force Protection

---

## Monitoring Data Sources

### Authentication Logs

```text
/var/log/auth.log
```

### Nginx Access Logs

```text
/var/log/nginx/access.log
```

### Nginx Error Logs

```text
/var/log/nginx/error.log
```

---

## Future Enhancements

* Wazuh SIEM Deployment
* Centralized Log Collection
* Threat Detection Dashboard
* Security Alert Correlation
* Advanced Monitoring Capabilities

## Lessons Learned

* Cloud infrastructure can be used to simulate realistic attack scenarios.
* Proper security group configuration is critical for protecting cloud resources.
* Log collection and monitoring are essential components of cloud security.
* Automated response mechanisms improve security posture and reduce risk.

