# Lab 3 – HTTPS / TLS Handshake

##  Objective
Capture and analyze the TLS handshake during a secure HTTPS connection.

## Tools
- Wireshark
- Browser

##  Steps
1. Started Wireshark capture.
2. Opened https://www.google.com in browser.
3. Applied filter: `tls`.

##  Findings
- **Client Hello** → My PC initiated the handshake with Google, proposing TLS version and cipher suites.
- **Server Hello** → Google confirmed the TLS version (TLSv1.2) and selected cipher.
- **Application Data** → After key exchange, encrypted HTTPS traffic began.

> Note: Wireshark shows `TLSv1.2` as the negotiated protocol. Certificate and key exchange steps are part of this flow, but some TLS 1.3 details may be hidden due to encryption.

##  Screenshots
- `SS3.png` – Showing Client Hello, Server Hello, and encrypted Application Data.

## Files
- `tls-handshake-google.pcapng`
- `SS3.png`
- `README.md`

