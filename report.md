## Wireshark Protocol Analysis Report

## Overview
This report outlines the results of analyzing a `.pcapng` file captured using Wireshark. The objective was to identify and study at least three network protocols.

---

## Protocols Observed

### 1. DNS (Domain Name System)
- Filter Used: `dns`
- Description: Used to resolve domain names (e.g., google.com to IP).
- Example Packet:
- - Query: `google.com`
---

### 2. HTTP (HyperText Transfer Protocol)
- Filter Used: `http`
- Description: Application-layer protocol for transferring web resources.
- Example Packet:
  - Method: `GET`
  - Host: `example.com`
  - URL: `/index.html`

---

### 3. TCP (Transmission Control Protocol)
- Filter Used: `tcp`
- Description: Ensures reliable delivery of data packets.
- Example Observations:
  - 3-Way Handshake: SYN, SYN-ACK, ACK
  - Followed by data transfer

---

## Notes:
- Traffic was captured over Wi-Fi.
- Packet filtering was done using Wireshark’s display filter bar.
- All data analyzed were unencrypted (HTTP, not HTTPS).
- Capture duration: ~2 minutes.

