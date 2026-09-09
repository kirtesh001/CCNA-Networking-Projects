# Project 1 - Branch Office WAN Network

## 📌 Overview

This project demonstrates a simple **Branch Office WAN Network** created using **Cisco Packet Tracer**.

The network connects a central **Headquarters (HQ)** with a remote **Branch Office** using a **Serial WAN connection**.

The project includes VLAN segmentation, DHCP, DNS, routing, switches, routers, PCs, and printers.

---

## 🌐 Network Topology

The network is divided into two main locations:

### 🏢 Headquarters (HQ)

The Headquarters contains two LAN segments.

#### 💼 Sales LAN

- Cisco 2960-24TT Switch
- PC0
- PC1
- PC2
- DHCP Server
- Printer0

#### 🖥️ IT LAN

- Cisco 2960-24TT Switch
- PC3
- PC4
- PC5
- DNS Server
- Printer1

Both LAN switches are connected to the central HQ router.

---

### 🏬 Branch Office

The Branch Office contains:

- Cisco 1841 Router
- Cisco 2960-24TT Switch
- PC6
- PC7
- PC8
- PC9
- Printer2

The Branch Office router is connected to the HQ router through a **Serial WAN Link**.

---

## 🔧 Key Components

| Device Type | Description |
|-------------|-------------|
| Routers | HQ Router and Branch Office Cisco 1841 Router |
| Switches | 3 × Cisco 2960-24TT Switches |
| Servers | DHCP Server and DNS Server |
| End Devices | PCs and Printers |
| WAN Link | Serial connection between HQ and Branch Router |

---

## 🎯 Concepts Covered

This project demonstrates the following networking concepts:

- VLAN Segmentation
- LAN Configuration
- Router Configuration
- Switch Configuration
- DHCP
- DNS
- WAN Connectivity
- Routing
- Inter-office Communication
- Network Troubleshooting

---

## 🖼️ Network Topology

![Network Topology](<img width="1431" height="710" alt="01-project1-topology" src="https://github.com/user-attachments/assets/16065367-1dcd-414d-9909-71a55c4a449c" />
)

---

## 🧪 Testing

Network connectivity can be tested using commands such as:

```bash
show ip interface brief
show ip route
show vlan brief
ping <IP-Address>
traceroute <IP-Address>
