# Azure AD Sync Errors Playbook

## Symptoms
- Users not syncing
- Password sync failures
- Duplicate attribute errors

## Quick Checks
- Check Azure AD Connect health
- Run delta sync
- Review sync errors

## Deep Checks
- Validate OU filtering
- Check attribute conflicts
- Review event logs

## Root Causes
- Attribute duplication
- OU misconfiguration
- Connector failure

## Resolution Steps
- Fix attribute conflicts
- Update OU filtering
- Restart sync service

## Preventative Measures
- Monitor sync health
- Document identity architecture
