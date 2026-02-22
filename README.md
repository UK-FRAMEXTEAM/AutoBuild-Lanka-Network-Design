# AutoBuild-Lanka-Network-Design
Transport Network Design Implementation for AutoBuild Lanka – VLAN, Redundancy, WAN, Security &amp; Troubleshooting (Cisco Packet Tracer)
## 🖥 Network Topology

![Network Diagram](Network-Diagram/Network-Topology.png)

# 🚗 AutoBuild Lanka – Transport Network Design

## 📌 Overview

This project was developed as part of the Pearson BTEC HND in Computing  
Unit 27 – Transport Network Design.

The objective was to design and implement a secure, redundant, and scalable enterprise network for AutoBuild Lanka, with branches in Colombo and Hambantota.

---

## 🏢 Branch Structure

### Hambantota Branch
- Engineering & Design
- Quality Control
- Production Management
- Inventory & Logistics
- HR
- IT & Security
- Server Room

### Colombo Branch
- HR
- IT & Security
- Management
- Server Room

---

## 🌐 Network Design Model

Selected Model: **Collapsed Core Model**

Why?
- Cost effective
- High redundancy
- Scalable
- Suitable for medium enterprise
- Supports VLAN segmentation & ACL policies

---

## 🔐 Key Technologies Implemented

- VLAN Segmentation
- Inter-VLAN Routing
- HSRP / VRRP (Gateway Redundancy)
- Link Aggregation (LACP)
- OSPF Routing
- ACL for Access Control
- Dual ISP Redundancy
- Secure WAN Design
- DHCP & Static IP Allocation
- Server Room Isolation (10.254.2.0/27)

---

## 📊 IP Allocation Plan

- 192.168.10.0/24 – Department VLANs
- 10.254.2.0/27 – Server Room (Static IPs)

Detailed IP table available in `/IP-Addressing/`

---

## 🔄 Redundancy Features

- Layer 2 Redundancy (STP)
- Layer 3 Redundancy (HSRP/VRRP)
- EtherChannel (LACP)
- Dual Core Switch Architecture
- Multiple ISP Gateway Design

---

## 🔒 Security Implementation

- VLAN Isolation
- ACL Restrictions
- WAN Encryption (VPN/IPsec Concept)
- Server Segmentation
- Access Control Between Departments

---

## 🛠 WAN Technology

Recommended:
- IPsec VPN between Colombo & Hambantota
- OSPF for Dynamic Routing
- Dual ISP Failover

---

## 🧪 Troubleshooting & Monitoring

- Ping & Traceroute Testing
- Layered Troubleshooting (OSI Model)
- Gateway Reachability Testing
- ACL Debugging
- Routing Table Verification

---

## 📁 Project Files

- Network Diagram → `/Network-Diagram/`
- Packet Tracer File → `/Packet-Tracer-Files/`
- IP Allocation Table → `/IP-Addressing/`
- Assignment Documentation → `/Assignment-Document/`

---

## 👨‍💻 Author

Pasindu Nilupul  
BEng (Hons) Computer Networking & Cloud Security (Top-Up)  
London Metropolitan University (UK)

Aspiring Network Engineer
