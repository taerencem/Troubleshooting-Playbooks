# Firewall Block Playbook

## Symptoms
- Cannot reach service
- Timeouts
- Connection refused

## Quick Checks
- Ping host
- Test port with nc or telnet
- Check local firewall (UFW/firewalld)

## Deep Checks
- Review perimeter firewall rules
- Check NAT configuration
- Validate security groups (cloud)

## Root Causes
- Blocked port
- Incorrect NAT
- Wrong zone assignment

## Resolution Steps
- Allow port
- Fix NAT rule
- Update firewall zone

## Preventative Measures
- Document firewall rules
- Use change control
