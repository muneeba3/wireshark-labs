# Lab 1 – DNS Analysis

## Objective
Capture and analyze DNS queries and responses when accessing websites.

##  Tools
- Wireshark
- Browser (Chrome/Edge)

## Steps
1. Opened Wireshark on Wi-Fi interface.
2. Visited websites: Google, YouTube, Grammarly.
3. Stopped capture and applied filter: `dns`.

## Findings
## Queries
- `music.youtube.com` → DNS Query sent from my PC (192.168.0.34) to router (192.168.0.1).
- `waa-pa.clients6.google.com` → DNS Query for Google services.
- `grammarly.io` → DNS Query from Grammarly browser extension.

###  Responses
- DNS Response for `music.youtube.com` → Returned IP address (A record).
- DNS Response for `waa-pa.clients6.google.com` → Returned multiple Google IP addresses.
- Some responses also returned **AAAA records** (IPv6 addresses).



## 📁 Files
- `dns-lookup-youtube-google.pcapng` → Raw packet capture



