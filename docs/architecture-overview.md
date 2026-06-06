# Architecture Overview

## Purpose

The Cloud Security Monitoring & Threat Detection Lab was designed to simulate real-world cybersecurity monitoring, attack detection, and automated response within a cloud environment.

## Architecture Components

### Attacker System

**Platform:** Kali Linux

**Tools Used:**

* Nmap
* Hydra
* Wireshark

**Responsibilities:**

* Reconnaissance
* Service Enumeration
* SSH Brute Force Simulation
* Network Traffic Generation

---

### Target System

**Platform:** AWS EC2 Ubuntu Server

**Services:**

* Nginx Web Server
* OpenSSH

**Security Controls:**

* Fail2Ban

**Responsibilities:**

* Generate security events
* Produce authentication logs
* Provide services for testing
* Demonstrate attack detection

---

### Monitoring Sources

#### Authentication Logs

Location:

```text
/var/log/auth.log
```

Used to identify:

* Failed SSH logins
* Successful logins
* Brute force activity

#### Web Server Logs

```text
/var/log/nginx/access.log
/var/log/nginx/error.log
```

Used to monitor web traffic and service activity.

---

## Security Workflow

1. Nmap scans identify exposed services.
2. Wireshark captures generated network traffic.
3. Hydra performs SSH brute force attempts.
4. Authentication logs record failed logins.
5. Fail2Ban detects malicious behavior.
6. The attacking IP is automatically blocked.
7. Evidence is collected and documented.

## Future Enhancements

* Wazuh SIEM Integration
* Threat Detection Dashboard
* Centralized Log Collection
* Security Alert Correlation
