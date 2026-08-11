# DHCP Issues Playbook

## Symptoms
- APIPA address (169.254.x.x)
- Cannot obtain IP
- Intermittent connectivity

## Quick Checks
- ipconfig /renew
- Check DHCP server availability
- Verify scope exhaustion

## Deep Checks
- Review DHCP logs
- Check rogue DHCP servers
- Validate VLAN configuration
- Check relay agents

## Root Causes
- Scope full
- DHCP server down
- Incorrect VLAN tagging
- Rogue DHCP server

## Resolution Steps
- Expand scope
- Restart DHCP service
- Fix VLAN configuration
- Remove rogue DHCP server

## Preventative Measures
- Monitor scope usage
- Use DHCP failover
