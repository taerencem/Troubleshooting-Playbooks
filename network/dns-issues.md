# DNS Issues Playbook

## Symptoms
- Websites not loading
- “DNS_PROBE_FINISHED_BAD_CONFIG”
- Cannot resolve hostnames
- Slow browsing

## Quick Checks
- Ping DNS server
- Check /etc/resolv.conf or Windows DNS settings
- Test with 8.8.8.8
- nslookup google.com

## Deep Checks
- Verify DNS server health
- Check AD-integrated DNS replication
- Review event logs on DNS server
- Check firewall rules blocking port 53

## Root Causes
- DNS server offline
- Misconfigured DNS settings
- Corrupted DNS cache
- Firewall block

## Resolution Steps
- Flush DNS cache
- Reset adapter
- Fix DNS server IPs
- Restart DNS service
- Rebuild DNS zones (if corrupted)

## Preventative Measures
- Monitor DNS health
- Document DNS architecture
