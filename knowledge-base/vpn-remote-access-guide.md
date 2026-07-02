# VPN Remote Access Troubleshooting Guide

## Purpose
This guide provides a basic Level 1 process for troubleshooting VPN connection issues for remote users.

## Common Symptoms
- VPN client will not connect
- User cannot access internal systems from home
- MFA prompt is not approved in time
- VPN connects but internal resources are unavailable
- User receives authentication or timeout errors

## Initial Checks
1. Confirm the user has working internet access.
2. Confirm normal websites are loading.
3. Confirm the VPN client is open and updated.
4. Confirm the username and password are accepted.
5. Confirm whether MFA prompt appears.
6. Ask whether other users are affected.
7. Confirm whether the issue started after a password change.

## Common Fixes
- Restart the VPN client
- Retry login and approve MFA promptly
- Restart the device
- Confirm correct network is being used
- Test after disconnecting and reconnecting Wi-Fi
- Confirm password is current

## Escalation Criteria
Escalate if:
- VPN client error continues after basic checks
- MFA device is unavailable
- Multiple users are affected
- Internal systems remain unavailable after VPN connects
- VPN profile or certificate issue is suspected

## Notes
Clearly document whether the failure occurs before login, during MFA, after connection or when accessing internal resources.
