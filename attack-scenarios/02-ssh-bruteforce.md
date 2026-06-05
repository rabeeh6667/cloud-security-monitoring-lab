# SSH Brute Force Simulation and Log Analysis

## Objective

Simulate an SSH brute-force attack against a cloud-hosted Ubuntu server and analyze authentication logs.

## Target

Ubuntu EC2 Instance hosted on AWS.

## Tools Used

- Kali Linux
- Hydra
- OpenSSH
- AWS EC2
- Ubuntu Server

## Commands Executed

```bash
hydra -l labuser -p WrongPassword ssh://56.228.28.30
```

## Results

Hydra successfully connected to the SSH service and attempted authentication using invalid credentials.

No valid credentials were found.

## Authentication Log Evidence

The following events were recorded:

```text
password check failed for user (labuser)
authentication failure
Failed password for labuser
```

## Analysis

The SSH daemon successfully detected and logged failed authentication attempts.

## Security Impact

Repeated occurrences of these events may indicate a brute-force attack targeting SSH services.

## Recommended Mitigations

- Disable password authentication
- Enforce SSH key authentication
- Implement Fail2Ban
- Restrict SSH access
- Monitor authentication logs

## Lessons Learned

Brute-force attacks generate identifiable log events that can be monitored and investigated by security teams.
