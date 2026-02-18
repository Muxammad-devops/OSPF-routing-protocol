# 🌐 OSPF Routing Protocol Lab (Cisco Packet Tracer)

This repository contains a practical lab implementation of the **OSPF (Open Shortest Path First)** routing protocol using Cisco Packet Tracer.  
The goal of this project is to demonstrate dynamic routing, area configuration, and inter-router communication in a small-to-medium network topology.

## 📌 Objectives
- Configure OSPF on multiple routers  
- Establish dynamic routing between networks  
- Verify routing tables and neighbor relationships  
- Practice real-world network troubleshooting  

## 🛠 Tech Stack
- Cisco Packet Tracer  
- Cisco IOS  
- Networking fundamentals (IP addressing, VLAN, routing)

## 🧩 Topology Overview
The topology includes multiple routers connected through point-to-point links and LAN segments.  
Each router participates in **OSPF Area 0 (Backbone)** to simplify initial learning and ensure full connectivity.

## ⚙️ Configuration (Example)

### Basic IP Configuration
```bash
Router(config)# interface g0/0
Router(config-if)# ip address 192.168.1.1 255.255.255.0
Router(config-if)# no shutdown
