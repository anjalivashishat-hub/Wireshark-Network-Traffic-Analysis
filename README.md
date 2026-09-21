# Wireshark Network Traffic Analysis

## Overview

This project demonstrates basic network traffic analysis using Wireshark.

The objective was to capture and analyze network packets, identify common protocols, apply Wireshark display filters, and understand how different types of network communication appear at the packet level.

## Tools Used

- Wireshark
- Windows
- Basic TCP/IP networking concepts

## Objectives

- Understand packet capture and packet analysis
- Identify common network protocols
- Analyze DNS traffic
- Examine TCP communication
- Identify HTTP traffic
- Analyze ARP packets
- Practice Wireshark display filters
- Document observations from network traffic

## Analysis Performed

### 1. DNS Traffic

Filter used: dns
I examined: 
-Source and Destination IP addresses 

### 2. TCP Traffic 

Filter used: tcp
I examined:
-TCP flags
-TCP connection establishment

### 3. ARP traffic
Filter used: arp
ARP packets were analyzed to understand how devices discover the MAC address associated with an IP address on a local network.

Key Findings
-DNS traffic can reveal the domains being queried by a host.
-TCP flags provide useful information about the state of a connection.
The TCP three-way handshake can be observed directly in packet captures.
ARP is used for IP-to-MAC address resolution on local networks.
Wireshark display filters make it easier to isolate relevant traffic during investigation.
