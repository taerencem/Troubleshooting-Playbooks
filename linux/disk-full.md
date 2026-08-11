# Linux Disk Full Playbook

## Symptoms
- Cannot write files
- Services crashing
- System slow

## Quick Checks
- df -h
- du -sh /*

## Deep Checks
- Check logs
- Check Docker images
- Check temp files

## Root Causes
- Log growth
- Docker bloat
- Backups stored locally

## Resolution Steps
- Clear logs
- Remove old Docker images
- Clean temp files

## Preventative Measures
- Log rotation
- Monitoring alerts
