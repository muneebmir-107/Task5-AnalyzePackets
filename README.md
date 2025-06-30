# 🛡Task 5: Network Traffic Capture and Analysis Using Wireshark

##  Objective
Capture live network traffic using Wireshark, identify different protocols, and analyze packet details.

## Tools Used
 Wireshark (Packet Sniffer & Network Analyzer)
 Browser/Terminal (To generate traffic)
 
## Steps Followed
1. Launched Wireshark.
2. Selected the active network interface (Wi-Fi).
3. Started packet capture.
4. Visited multiple websites and pinged a domain (google.com) to generate traffic.
5. Stopped the capture after 1–2 minutes.
6. Applied filters to identify protocols: `dns`, `http`, `tcp`.
7. Saved the capture as `tcp_dns_http.pcapng`.
8. Created a short report based on the filtered results.

## Protocols Identified
- DNS – Used for resolving domain names (e.g., google.com).
- HTTP – Captured basic GET requests to unsecured websites.
- TCP – Transmission Control Protocol used for reliable communication.

## Files Included
- `tcp_dns_http.pcapng`: Raw network traffic captured using Wireshark.
- `report.md`: Summary of protocol analysis.
- `screenshot`: Screenshots of filtered view.
