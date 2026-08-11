# Windows Network Issues Playbook

## Symptoms
- No internet
- Limited connectivity
- Cannot reach shared drives
- DNS errors

## Quick Checks
- Check physical connection
- Verify Wi-Fi status
- Run ipconfig /all
- Ping gateway

## Deep Checks
- Check DNS server reachability
- Flush DNS: ipconfig /flushdns
- Reset adapter: netsh int ip reset
- Check firewall rules
- Review DHCP lease

## Root Causes
- DNS outage
- DHCP failure
- Firewall block
- Bad cable
- Misconfigured static IP

## Resolution Steps
- Renew IP: ipconfig /renew
- Reset TCP/IP stack
- Update NIC drivers
- Reconfigure DNS
- Restart DHCP client

## Preventative Measures
- Monitor DHCP scope
- Monitor DNS health
- Document static IP assignments
