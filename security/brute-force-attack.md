# Brute Force Attack Playbook

## Symptoms
- Multiple failed logins
- Fail2Ban bans
- High auth.log activity

## Quick Checks
- Review auth.log
- Check Fail2Ban status
- Identify attacking IPs

## Deep Checks
- Review firewall logs
- Check SSH configuration
- Validate IDS/IPS alerts

## Root Causes
- Internet-exposed SSH
- Weak passwords
- No rate limiting

## Resolution Steps
- Enable Fail2Ban
- Harden SSH
- Block IPs
- Update firewall rules

## Preventative Measures
- Use key-based authentication
- Change SSH port
