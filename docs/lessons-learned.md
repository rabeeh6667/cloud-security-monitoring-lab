# Lessons Learned

## Technical Lessons

### AWS Infrastructure Management

* Learned how to deploy and manage EC2 instances.
* Gained experience configuring cloud networking and security groups.

### Linux Administration

* Installed and configured security services.
* Managed SSH configurations and authentication settings.
* Analyzed system logs and service status.

### Network Security

* Performed reconnaissance using Nmap.
* Understood exposed services and attack surfaces.
* Captured and analyzed traffic using Wireshark.

### Threat Detection

* Investigated authentication failures.
* Identified brute-force attack patterns.
* Collected evidence from system logs.

### Automated Response

* Implemented Fail2Ban protection.
* Validated automated IP blocking.
* Demonstrated incident response capabilities.

## Challenges Encountered

### SSH Authentication Configuration

Password authentication required additional configuration because cloud-init settings overrode the default SSH configuration.

### Resource Constraints

The Wazuh deployment required more resources than available on the current lab server.

### Log Analysis

Understanding authentication logs required reviewing multiple log entries and correlating events.

## Key Takeaways

* Security monitoring is highly dependent on log visibility.
* Automated response significantly improves defensive capabilities.
* Cloud environments require continuous monitoring and hardening.
* Practical attack simulations provide valuable learning opportunities.

## Future Improvements

* Deploy Wazuh SIEM.
* Build a threat detection dashboard.
* Implement centralized log monitoring.
* Expand the lab with additional attack scenarios.
