# Basic Network Troubleshooting Guide

## Purpose
This guide provides a basic Level 1 process for investigating Windows network connectivity issues.

## Common Symptoms
- User is connected to Wi-Fi but websites do not load
- User cannot access internal systems
- DNS errors in browser
- Shared drives unavailable
- Connection works for other users but not one device

## Initial Checks
1. Confirm whether the issue affects one user or multiple users.
2. Confirm the device is connected to the correct network.
3. Check whether other websites are accessible.
4. Test whether other users are affected.
5. Check IP configuration using `ipconfig`.
6. Test external connectivity using `ping 8.8.8.8`.
7. Test DNS resolution using `nslookup google.com`.

## Common Fixes
- Disconnect and reconnect Wi-Fi
- Restart the device
- Run `ipconfig /flushdns`
- Restart browser
- Test another browser
- Confirm VPN status if internal resources are affected

## Escalation Criteria
Escalate if:
- Multiple users are affected
- Internal systems are unavailable across the network
- Device has no valid IP address after reconnecting
- DNS or DHCP issue appears wider than one device
- Firewall, router or switch issue is suspected

## Notes
Always record what tests were performed and whether the issue appears isolated or widespread.
