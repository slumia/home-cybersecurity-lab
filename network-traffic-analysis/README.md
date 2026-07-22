# Wireshark Network Analysis

## Overview

This lab demonstrates the use of Wireshark to capture and analyze DNS traffic generated on a local network. The objective was to observe DNS query and response behavior, inspect packet contents, and become familiar with protocol analysis techniques commonly used during network troubleshooting and security investigations.

---

## Lab Environment

| Component | Technology |
|-----------|------------|
| Packet Analyzer | Wireshark |
| Protocol | DNS |
| Operating System | macOS |
| Network | Local Area Network |

---

## Objectives

- Capture live network traffic
- Filter DNS packets
- Analyze DNS queries and responses
- Inspect packet headers and payloads
- Interpret network communication between a client and DNS server

---

## Analysis

During the capture, Wireshark was used to observe DNS requests generated while browsing the web.

The analysis included:

- DNS query and response pairs
- Source and destination IP addresses
- Requested domain names
- IPv4 and IPv6 DNS records
- UDP transport
- Packet details and hexadecimal representation

This exercise demonstrates the ability to inspect network traffic and understand how DNS resolution occurs between a client and a DNS server.

---

## Skills Demonstrated

- Packet Analysis
- DNS
- Network Troubleshooting
- TCP/IP
- UDP
- Wireshark
- Protocol Analysis

---

## Screenshot

### DNS Traffic Analysis

![Wireshark DNS Analysis](screenshots/wireshark-dns-analysis.png)

---

## Key Takeaways

This lab reinforced the fundamentals of packet capture and protocol analysis by examining live DNS traffic. Understanding how DNS queries and responses appear in Wireshark is an important skill for troubleshooting network issues and investigating suspicious network activity in security operations.
