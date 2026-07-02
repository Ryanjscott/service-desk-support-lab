# Ticket 005: Outlook Mailbox Issue

## Summary
User was unable to send emails from the Outlook desktop application.

## Category
Software / Outlook

## Priority
Medium

## Impact
User could receive email but could not send messages from Outlook desktop, affecting normal communication.

## Initial User Update
Hi, I’ve received your Outlook issue request. I’ll check whether this is affecting only the desktop app or the mailbox itself, then work through connectivity, account and cached profile checks.

## Internal Triage Note
Issue appeared isolated to the Outlook desktop client. Initial checks compared Outlook desktop behaviour with webmail and reviewed connectivity, Outbox status and cached profile behaviour.

## Troubleshooting Steps
1. Confirmed the user had internet access.
2. Confirmed incoming mail was working.
3. Checked whether emails were stuck in the Outbox.
4. Asked the user to test Outlook on the web.
5. Confirmed webmail could send emails successfully.
6. Restarted Outlook and checked Work Offline status.
7. Cleared the stuck Outbox message and restarted the Outlook desktop client.
8. Sent a test email successfully.

## Resolution
Confirmed the issue was isolated to the Outlook desktop app. Cleared the stuck Outbox message, confirmed Outlook was not in offline mode and restarted the application. Test email sent successfully.

## Escalation Required
No.

## Closure Note
Issue resolved. Likely cause was a stuck Outbox message or temporary Outlook client issue.

## Skills Demonstrated
- Outlook troubleshooting
- Desktop app versus web app testing
- User communication
- Email support process
- Clear closure documentation
