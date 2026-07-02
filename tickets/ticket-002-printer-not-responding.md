# Ticket 002: Printer Not Responding

## Summary
User was unable to print from a Windows laptop to a shared office printer.

## Category
Hardware / Printer

## Priority
Medium

## Impact
User could not print required documents, affecting normal office workflow.

## Initial User Update
Hi, I’ve received your printer issue request. I’ll check whether this is related to the printer queue, device connection, network access or the Windows print service and update you shortly.

## Internal Triage Note
Issue appeared limited to one user device rather than a full printer outage. Initial checks focused on the print queue, printer status, network connection and Windows Print Spooler service.

## Troubleshooting Steps
1. Confirmed the user was connected to the office network.
2. Confirmed the printer had power, paper and no visible error message.
3. Checked the Windows print queue and found stuck print jobs.
4. Cancelled the stuck print jobs.
5. Restarted the Windows Print Spooler service.
6. Removed and re-added the shared printer on the user device.
7. Sent a test print to confirm the printer was working.

## Resolution
Cleared stuck print jobs, restarted the Windows Print Spooler service and re-added the shared printer. Test page printed successfully.

## Escalation Required
No.

## Closure Note
Issue resolved. Likely cause was a stuck print queue on the user device.

## Skills Demonstrated
- Printer troubleshooting
- Windows Print Spooler checks
- Queue management
- Customer communication
- Structured troubleshooting documentation
