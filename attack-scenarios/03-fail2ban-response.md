# Fail2Ban Detection and Automated Response

## Objective

Demonstrate automatic detection and blocking of repeated SSH authentication failures.

## Tools Used

- Ubuntu Server
- Fail2Ban
- OpenSSH
- Hydra
- AWS EC2

## Configuration

```ini
[sshd]
enabled = true
maxretry = 3
findtime = 60
bantime = 600
```

## Attack Simulation

Multiple failed SSH login attempts were generated using Hydra from Kali Linux.

## Detection

Fail2Ban monitored SSH authentication logs and detected repeated failed login attempts.

## Automated Response

The attacking IP address exceeded the configured threshold and was automatically banned.

## Evidence

- Fail2Ban SSH jail status
- Hydra attack output
- Authentication logs
- Ban confirmation

## Results

- Failed attempts detected: 5
- Banned IPs: 1

## Lessons Learned

Fail2Ban provides an effective automated defense against brute-force attacks by monitoring logs and blocking malicious IP addresses.
