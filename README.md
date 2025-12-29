# Packet-tracer-enterprise-network
Cisco Packet Tracer — 3-Tier Enterprise Network (OSPF/RIPv2 + ACLs)

## Overview
Built a Core–Distribution–Access enterprise network in Cisco Packet Tracer with multi-department segmentation, dynamic routing, and security controls.

## Key Features
- OSPF Area 0 in core/distribution
- RIPv2 at access layer
- Route redistribution between OSPF and RIP
- Extended ACLs to restrict inter-department access and block Telnet/FTP/TFTP
- Verification with routing tables, neighbor adjacencies, and end-to-end ping tests

## What’s in this repo
- **/report/**: Final report PDF
- **/screenshots/**: Topology + verification evidence
- **/configs/**: Router/switch configurations
- **/packet-tracer-file/**: .pkt file (optional)

## Verification (examples)
- `show ip route`
- `show ip ospf neighbor`
- `show access-lists`
- Ping tests between departments
