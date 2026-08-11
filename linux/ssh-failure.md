# Linux SSH Failure Playbook

## Symptoms
- Cannot SSH into server
- Connection refused
- Timeout
- Permission denied

## Quick Checks
- Ping server
- Check port 22
- Verify firewall rules
- Check Fail2Ban status

## Deep Checks
- Review /var/log/auth.log
- Check sshd_config
- Restart SSH service
- Verify key permissions

## Root Causes
- SSH service down
- Firewall block
- Wrong permissions
- Fail2Ban ban

## Resolution Steps
- Restart SSH
- Fix permissions
- Unban IP
- Update firewall rules

## Preventative Measures
- SSH hardening
- Fail2Ban monitoring
