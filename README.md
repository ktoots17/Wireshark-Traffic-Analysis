# Wireshark Packet Capture and Analysis

## Introduction
This project demonstrates my ability to use Wireshark to capture and analyze network traffic, applying concepts from my CompTIA Network+ certification. The goal was to study common protocols (e.g., DNS, HTTP, HTTPS) and verify secure data transmission, aligning with Security+ principles.

## Setup
- **Environment**: Kali Linux 2024.4 on VMware Worksation Pro
- **Tool**: Wireshark 4.4.0
- **Network**: Home Wi-Fi, capturing traffic from my VM

## Process
1. Launched Wireshark on my VM and started a capture on the active network interface (e.g., eth0).
2. Browsed a safe website (yahoo.com) to generate traffic.
3. Applied filters for DNS, HTTP, and HTTPS to analyze specific packets.
4. Saved the capture as a .pcap file for review.

## Findings
- **DNS Query**: Observed a DNS request for bbc.com resolving to 151.101.0.81 (see dns_filter.png).
- **TCP Handshake**: Identified a three-way handshake for HTTP traffic, confirming reliable connections (see tcp_stream.png).
- **HTTPS Security**: Confirmed HTTPS traffic used TLS 1.3, ensuring encrypted data (see https_traffic.png).

## Conclusion
This project reinforced my understanding of network protocols and security. I learned to filter packets in Wireshark and verify secure communications, skills relevant to IT support and network administration.

## Tools Used
- Wireshark 4.4.0
- VMware Workstation Pro 7.0
- Kali Linux 2024.4

## Screenshots
- [DNS Filter](dns_filter.png)
- [TCP Stream](tcp_stream.png)
- [HTTPS Traffic](https_traffic.png)
