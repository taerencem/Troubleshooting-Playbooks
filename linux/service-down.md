# Linux Service Down Playbook

## Symptoms
- Website down
- API down
- SSH down

## Quick Checks
- systemctl status
- journalctl -xe

## Deep Checks
- Check dependencies
- Check ports
- Check logs

## Root Causes
- Crash
- Bad update
- Dependency failure

## Resolution Steps
- Restart service
- Roll back update
- Fix dependency

## Preventative Measures
- Service monitor script
