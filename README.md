# DNS Cache Poisoning Prevention with ICMP Ping

## Overview
This project focuses on using ICMP ping to prevent DNS cache poisoning. By verifying ICMP ping replies, we can ensure that DNS queries receive responses from legitimate servers. The simulation of this model is conducted using Cisco Packet Tracer to illustrate how ICMP ping can help in securing DNS responses.

## Objectives
- **Prevent DNS Cache Poisoning**: Use ICMP ping to verify the legitimacy of DNS responses.
- **Ensure DNS Query Validity**: Confirm that replies are from legitimate DNS servers.
- **Simulation**: Implement and test the model using Cisco Packet Tracer.

## How It Works
1. **ICMP Ping**: When a DNS server receives a query, it sends an ICMP ping to the IP address returned in the DNS reply.
2. **Verification**: If the ICMP ping receives a reply, it indicates that the IP address is from a legitimate server.
3. **DNS Query Response**: Based on the ICMP ping result, the DNS server accepts or rejects the response to prevent cache poisoning.

## Tools and Technologies
- **Cisco Packet Tracer**: For simulating the network model and ICMP ping verification.

## Getting Started
### Prerequisites
- Cisco Packet Tracer installed on your system.
- Basic understanding of DNS, ICMP ping, and network security concepts.
