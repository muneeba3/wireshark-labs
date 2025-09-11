# Lab 5 – ARP & ICMP Analysis

##  Objective
Capture and analyze ARP and ICMP traffic to understand network-level communication and diagnostics.

##  Tools
- Wireshark
- Terminal / Command Prompt (ping command)
- Browser (optional)

##  Steps
1. Started Wireshark capture on active interface.
2. Generated ARP traffic by pinging router: `ping [router-ip]`.
3. Generated ICMP traffic by pinging external server: `ping 8.8.8.8`.
4. Applied filter: `arp or icmp`.

##  Findings
- **ARP Requests / Replies** → PC learned MAC addresses of devices on network.
- **ICMP Echo Request / Reply** → Measured network latency, confirmed connectivity.
- Observed normal traffic patterns, no anomalies.



## Files
- `arp-icmp-capture.pcapng`
- `SS5.png`
- `README.md`