# Architecture Overview

## Attack Workstation

The attack workstation is a Kali Linux machine used to perform reconnaissance, traffic analysis, and attack simulations.

Tools:
- Nmap
- Hydra
- Wireshark

## Target Server

AWS EC2 Ubuntu Server hosting:

- Nginx Web Server
- OpenSSH
- Fail2Ban

## Log Sources

- Authentication Logs
- Nginx Access Logs

## Security Controls

- SSH Authentication
- Fail2Ban Automated Response
