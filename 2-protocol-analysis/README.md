# Protocol Analysis Project

## Overview
A comprehensive deep-packet forensic audit and behavioral analysis of fundamental network and application-layer protocols. This project explores how data is encapsulated, transmitted, and secured across the OSI model.

## Key Objectives
- Dissect Layer 2 and Layer 3 control traffic, including 802.1Q VLAN tagging and ARP resolution.
- Audit critical infrastructure services like DHCP stateful leases and DNS resolution.
- Evaluate the security posture of application-layer data transfers by comparing plaintext protocols with cryptographic channels.

## Contents
- [analysis-report.pdf](./analysis-report/) - Full project report containing hex-dump decodes and sequence diagrams.
- [findings/](./findings/) - Raw packet capture logs, terminal trace transcripts, and protocol flow charts.

## Technologies Used
- Wireshark / Packet Capture (pcap) Analysis
- Hex Dump Decoding
- TCP/IP Protocol Suite (DHCP, DNS, FTP, SMTP/POP3, SIP, NTPv4)
- Secure Shell (SSH) vs. Telnet

## Results/Findings
Mapped the exact bitwise structures of IP option headers (Record Route/Timestamp) and validated VoIP SIP/RTP signaling flows. The security audit successfully demonstrated the vulnerabilities of plaintext Telnet sessions compared to the multi-step cryptographic handshakes of modern SSH implementation.

## Course Information
- Course: COS370 & COS372
- University: [Your University]
- Date: [Month, Year]
