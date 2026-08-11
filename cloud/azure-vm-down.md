# Azure VM Down Playbook

## Symptoms
- VM unreachable
- RDP/SSH failure
- Portal shows “Unavailable”

## Quick Checks
- Check VM status
- Review Azure Monitor metrics
- Validate NSG rules

## Deep Checks
- Check boot diagnostics
- Review activity logs
- Validate VNet configuration
- Check Azure Firewall

## Root Causes
- Bad update
- NSG block
- VNet misconfiguration
- Disk corruption

## Resolution Steps
- Restart VM
- Fix NSG rules
- Redeploy VM
- Restore from snapshot

## Preventative Measures
- Enable boot diagnostics
- Use update management
