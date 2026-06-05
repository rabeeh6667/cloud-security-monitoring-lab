# Nmap Reconnaissance and Wireshark Traffic Analysis

## Objective

Identify open ports and services on an AWS-hosted Ubuntu server and analyze network traffic generated during reconnaissance.

## Target

Ubuntu EC2 Instance hosted on AWS.

## Tools Used

* Kali Linux
* Nmap
* Wireshark
* AWS EC2
* Ubuntu Server
* Nginx

## Commands Executed

```bash
nmap 56.228.28.30
nmap -sV 56.228.28.30
```

## Results

The scan identified the following exposed services:

| Port | Service | Version        |
| ---- | ------- | -------------- |
| 22   | SSH     | OpenSSH 10.2p1 |
| 80   | HTTP    | nginx 1.28.3   |

## Wireshark Analysis

Network traffic was captured during the scan.

### Observations

* TCP communication observed between Kali Linux and AWS EC2.
* HTTP traffic captured from the Nginx web server.
* Service enumeration generated additional network traffic.

## Evidence

See screenshots directory for:

* Nmap scan results
* Wireshark captures
* Nginx verification

## Lessons Learned

Reconnaissance is the first stage of many attacks. Monitoring network traffic helps defenders identify scanning activity and exposed services.

```
```
