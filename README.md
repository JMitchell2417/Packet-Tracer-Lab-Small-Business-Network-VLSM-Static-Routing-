# Packet Tracer Lab: Small Business Network (VLSM + Static Routing)

<img src="/images/network__screenshot.jpg" alt="Network Screenhot" width="600"/>

### Project Description

Designed and implemented a small business network using Variable Length Subnet Masking (VLSM) and static routing to support multiple LANs with efficient IP address utilization and full end-to-end connectivity.

**Overview**

This project simulates a real-world small office network with two departments connected through a point-to-point WAN link. The network was subnetted from a single /24 address space to meet varying host requirements while minimizing wasted IP addresses. Static routing was configured between routers to enable communication across all subnets.

**Tools Used**

- Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4 Subnetting (VLSM)
- Static Routing

**How It Works**

- Subnetted a /24 network using VLSM to support multiple LANs and a WAN link.

- Assigned IP addresses following best practices:

  - First usable IPs to end devices
  - Last usable IPs to router LAN interfaces

- Configured router interfaces and enabled connectivity.

- Implemented static routes to direct traffic between non-directly connected networks.

- Verified network functionality using ping, show ip route, and show ip interface brief.

**Business Value**

- Demonstrates efficient IP address planning for growing networks.

- Improves reliability by ensuring consistent routing paths.

- Reduces troubleshooting time through clear network segmentation.

- Reflects real-world networking tasks commonly performed in help desk and NOC environments.
