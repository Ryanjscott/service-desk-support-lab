# Ticket 003: DNS Connectivity Issue

## Summary
User was connected to Wi-Fi but could not access websites from their Windows laptop.

## Category
Network

## Priority
High

## Impact
User could not access web-based services, affecting normal work.

## Initial User Update
Hi, I’ve received your network issue request. I’ll check whether the issue is related to Wi-Fi connectivity, DNS resolution, IP configuration or browser/network settings and update you shortly.

## Internal Triage Note
Issue appeared isolated to one Windows device. Other users were able to access websites, so initial checks focused on the local device, IP configuration and DNS resolution.

## Troubleshooting Steps
1. Confirmed the user was connected to the correct Wi-Fi network.
2. Confirmed other users were able to access websites.
3. Ran `ipconfig` to check the device had a valid IP address.
4. Ran `ping 8.8.8.8` to test external connectivity.
5. Ran `nslookup google.com` to test DNS resolution.
6. Identified a DNS resolution issue on the user device.
7. Ran `ipconfig /flushdns` to clear the DNS resolver cache.
8. Retested website access successfully.

## Resolution
Cleared the DNS resolver cache using `ipconfig /flushdns`. User was then able to access websites successfully.

## Escalation Required
No.

## Closure Note
Issue resolved. Likely cause was a local DNS cache or resolution issue on the Windows device.

## Skills Demonstrated
- Basic network troubleshooting
- DNS issue investigation
- Command Prompt troubleshooting
- User communication
- Structured technical documentation
