# Ticket 001: Microsoft 365 Login Issue

## Summary
User was unable to sign in to Microsoft 365 after changing their password.

## Category
Account Access / Microsoft 365

## Priority
Medium

## Impact
User could not access Outlook, Teams or OneDrive, which affected normal daily work.

## Initial User Update
Hi, I’ve received your request and I’m checking whether this is related to password authentication, MFA or cached credentials. I’ll update you once I’ve worked through the first checks.

## Internal Triage Note
Issue appeared to affect multiple Microsoft 365 services, not one application. Likely authentication or cached credential issue after password change.

## Troubleshooting Steps
1. Confirmed the user had internet access.
2. Confirmed the issue affected Outlook, Teams and browser sign-in.
3. Asked the user to test sign-in using a private browser window.
4. Confirmed the user had recently changed their password.
5. Identified cached credentials as the likely cause.
6. Advised the user to clear saved credentials and retry sign-in.

## Resolution
The user cleared cached credentials and successfully signed back into Microsoft 365. Outlook and Teams access were confirmed working.

## Escalation Required
No.

## Closure Note
Issue resolved. Likely cause was cached credentials following a password change.

## Skills Demonstrated
- Microsoft 365 account access troubleshooting
- User communication
- Structured ticket notes
- Root cause thinking
- Clear closure documentation
