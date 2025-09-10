# Lab 2 – TCP 3-Way Handshake

## Objective
Capture and analyze the TCP 3-way handshake using Wireshark.

##  Tools
- Wireshark
- Browser

## Steps
1. Started capture in Wireshark.
2. Opened https://www.google.com in browser.
3. Applied filter: `tcp.flags.syn==1 || tcp.flags.ack==1`.

## Findings
- SYN → My PC (192.168.0.34) → Google server (142.250.187.195)
- SYN, ACK → Google server → My PC
- ACK → My PC → Google server

This 3-step exchange establishes a reliable TCP connection.

## Screenshots
- Screenshot of the 3 packets (SYN, SYN/ACK, ACK) — `SS2.png`

## Files
- `tcp-3way-handshake-google.pcapng`
- `screenshot2.png`


