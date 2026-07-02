# Ticket 006: VPN Remote Access Issue

## Summary
User was unable to connect to the company VPN from their home network.

## Category
Remote Access / VPN

## Priority
High

## Impact
User could not access internal systems while working remotely.

## Initial User Update
Hi, I’ve received your VPN access request. I’ll check your internet connection, VPN client status, credentials and MFA behaviour to identify where the connection is failing.

## Internal Triage Note
Issue affected remote access to internal systems. Initial checks focused on internet connectivity, VPN client status, credentials, MFA prompt behaviour and whether the issue affected other users.

## Troubleshooting Steps
1. Confirmed the user had working home internet access.
2. Confirmed other websites were loading normally.
3. Asked the user to restart the VPN client.
4. Confirmed username and password were accepted.
5. Checked whether the MFA prompt appeared.
6. Identified that the MFA prompt was not being approved within the required time.
7. Asked the user to retry login and approve MFA promptly.
8. Confirmed VPN connected successfully and internal resources were accessible.

## Resolution
User retried VPN connection and approved the MFA prompt within the required time window. VPN connected successfully and access to internal systems was restored.

## Escalation Required
No.

## Closure Note
Issue resolved. Likely cause was MFA approval timing during VPN authentication.

## Skills Demonstrated
- VPN troubleshooting
- MFA authentication awareness
- Remote access support
- Customer communication
- Structured resolution notes
