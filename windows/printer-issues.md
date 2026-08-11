# Windows Printer Issues Playbook

## Symptoms
- Printer offline
- Jobs stuck in queue
- Cannot install printer
- Access denied

## Quick Checks
- Restart spooler
- Clear print queue
- Verify network connectivity
- Check permissions

## Deep Checks
- Reinstall printer driver
- Reset spooler service
- Check print server health
- Review event logs

## Root Causes
- Corrupted driver
- Spooler crash
- Network outage
- Permissions issue

## Resolution Steps
- Restart spooler: net stop spooler / net start spooler
- Delete stuck jobs
- Reinstall printer
- Update drivers

## Preventative Measures
- Use universal drivers
- Monitor print server
