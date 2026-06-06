# Methodology

## Project Approach

A structured cybersecurity testing methodology was used to simulate attacks, monitor activity, analyze logs, and validate automated response mechanisms.

## Phase 1: Infrastructure Deployment

### Objectives

* Deploy cloud infrastructure
* Configure target services
* Prepare testing environment

### Activities

* Created AWS EC2 Ubuntu instance
* Configured security groups
* Installed Nginx
* Verified SSH connectivity

---

## Phase 2: Reconnaissance

### Objectives

Identify exposed services and potential attack surfaces.

### Activities

* Performed Nmap scans
* Enumerated running services
* Identified open ports

### Results

* Port 22 (SSH)
* Port 80 (HTTP)

---

## Phase 3: Traffic Analysis

### Objectives

Analyze network traffic generated during reconnaissance.

### Activities

* Captured packets using Wireshark
* Observed HTTP traffic
* Examined protocol behavior

---

## Phase 4: Attack Simulation

### Objectives

Simulate unauthorized access attempts.

### Activities

* Enabled password authentication
* Created test user account
* Executed Hydra brute-force attack

---

## Phase 5: Detection

### Objectives

Identify attack indicators.

### Activities

* Reviewed authentication logs
* Monitored failed login attempts
* Collected attack evidence

---

## Phase 6: Automated Response

### Objectives

Automatically block malicious activity.

### Activities

* Installed Fail2Ban
* Configured SSH protection
* Triggered attack detection
* Verified IP ban

## Conclusion

The methodology successfully demonstrated attack simulation, detection, analysis, and automated response within a cloud environment.
