# Multi-Floor Enterprise Network Infrastructure

## Overview
A comprehensive Cisco-based network design for a 3-story corporate building using the **3-Tier Hierarchical Model** (Core, Distribution, and Access). This project demonstrates professional-level configuration of routing, switching, and network security.

## Technical Features
* **Architecture:** 3-Tier Hierarchical Design for scalability and redundancy.
* **VLAN Segmentation:** 6 functional VLANs (Admin, ICT, Sales, etc.) to isolate traffic.
* **Routing:** Inter-VLAN routing on Layer 3 switches and OSPF for dynamic core routing.
* **Services:** Centralized DHCP with IP Helper-address configuration.
* **Security:** SSH for remote management, Port Security, and ACLs.

## Troubleshooting Log (The Challenge)
During implementation, I faced and resolved:
1. **DHCP Connectivity:** Fixed APIPA (169.254.x.x) issues by correctly configuring IP Helper-addresses and ensuring Trunk links allowed all VLANs.
2. **Routing:** Ensured full connectivity between departments using OSPF.

## Tools Used
* Cisco Packet Tracer
* Subnetting (VLSM)
