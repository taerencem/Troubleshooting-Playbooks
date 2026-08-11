# AWS EC2 Down Playbook

## Symptoms
- EC2 unreachable
- SSH timeout
- Website down

## Quick Checks
- Check instance status checks
- Review CloudWatch metrics
- Verify security groups

## Deep Checks
- Check system logs
- Validate IAM role permissions
- Review VPC routing
- Check NACLs

## Root Causes
- CPU spike
- Network misconfiguration
- Security group block
- Failed update

## Resolution Steps
- Reboot instance
- Fix SG rules
- Correct route tables
- Restore from snapshot

## Preventative Measures
- Monitoring alerts
- Automated backups
