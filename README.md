# Enterprise Network Simulation

## Overview
A fully functional two-site enterprise network simulation
built using Cisco Packet Tracer.

**Student:** Chalani Tharushika
**University:** University of Kelaniya
**Faculty:** Computing and Technology
**Degree:** Bachelor in Information and Communication Technology
**Specialization:** Computer Network Technology
**Year:** 3rd Year — 2026

## Technologies Implemented
- VLANs — 5 VLANs across 2 sites
- Inter-VLAN Routing — Router-on-a-Stick
- OSPF Area 0 — dynamic routing between sites
- DHCP — automatic IP assignment across all VLANs
- DNS — hostname resolution
- ACLs — Guest VLAN isolated from HQ servers
- Port Security — MAC address locking on switch ports
- SSH v2 — encrypted remote management on all devices

## Network Topology
- HQ Site: R1-HQ (Cisco 2911), SW1-HQ (Cisco 3560 L3),
  DHCP/DNS Server, 3 PCs — VLANs 10, 20, 30
- Branch Site: R2-Branch (Cisco 2911), SW2-Branch
  (Cisco 2960 L2), 2 PCs — VLANs 40, 50
- WAN: Serial link with OSPF routing

## How to Open the Simulation
1. Download and install Cisco Packet Tracer free
   at netacad.com
2. Open the .pkt file in Packet Tracer
3. All configurations are pre-loaded and working

## Verification Results
All features tested and verified including:
- OSPF neighbour state: FULL
- Cross-site ping: successful
- DHCP: all 5 PCs receive auto IP
- DNS: hostname resolution working
- ACL: Guest VLAN blocked from HQ servers
- SSH: remote login working on all 4 devices
