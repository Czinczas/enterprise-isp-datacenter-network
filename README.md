# Enterprise ISP & Data Center Network

A complete Enterprise and ISP network designed and implemented in GNS3 as the final project for Cisco CCNA Enterprise Networking, Security and Automation (ENSA).

This project demonstrates the deployment of a scalable enterprise network connected to multiple ISPs while implementing redundancy, dynamic routing, security, and high availability technologies commonly used in production environments.

---

## Project Objectives

- Design a complete enterprise and ISP network architecture.
- Implement dynamic routing across multiple routing domains.
- Provide high availability at both Layer 2 and Layer 3.
- Secure WAN communication using encrypted tunnels.
- Deploy essential enterprise network services.
- Validate end-to-end connectivity and fault tolerance.

---

# Network Topology

> *(Insert topology image here)*

The topology consists of:

- Enterprise Campus Network
- Data Center
- Two Internet Service Providers
- Multiple Branch Connections
- Redundant Core and Distribution Layers

---

# Technologies Implemented

## Routing

- OSPF Multi-Area
- EIGRP
- eBGP
- Static Routing
- Default Routing

---

## Layer 2

- VLAN Segmentation
- EtherChannel (LACP & PAgP)
- Rapid Spanning Tree Protocol (RSTP)

---

## High Availability

- HSRP
- Gateway Redundancy
- Redundant Layer 2 Paths

---

## Security

- GRE over IPsec
- Access Control Lists (ACL)
- NAT/PAT

---

## Network Services

- DHCP
- TFTP
- QoS Classification & Marking
- DNS Simulation

---

## Monitoring & Validation

- Ping
- Traceroute
- Routing Table Verification
- OSPF Neighbor Validation
- BGP Session Verification
- Wireshark Packet Analysis

---

# Main Features

✔ Multi-Area OSPF Design

✔ ISP Connectivity using eBGP

✔ GRE over IPsec VPN

✔ Layer 2 Redundancy

✔ Gateway Redundancy with HSRP

✔ DHCP Services

✔ NAT/PAT Internet Access
Internet
↓
ISP1 -------- ISP2
↓
Core
↓
Distribution
↓
Access
↓
Data Center
