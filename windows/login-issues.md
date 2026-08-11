# Windows Login Issues Playbook

## Symptoms
- User cannot log in
- Incorrect password errors
- Account locked
- Domain unavailable
- Profile corruption

## Quick Checks
1. Verify username spelling
2. Check Caps Lock
3. Confirm network connection
4. Try logging into another machine

## Deep Checks
- Check AD account status
- Reset password
- Unlock account
- Check domain controller reachability
- Review event logs:
  - Event Viewer → Windows Logs → Security
  - Event Viewer → Applications → User Profile Service

## Root Causes
- Password expired
- Account locked
- Domain controller offline
- Corrupted profile
- Network outage

## Resolution Steps
- Reset password
- Unlock account
- Recreate profile
- Rejoin domain
- Restart NetLogon service

## Preventative Measures
- Enforce password expiration notifications
- Monitor DC health
- Enable profile backup
