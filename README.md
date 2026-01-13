# Basic Static Routing - Cisco Packet Tracer

## 📌 Project Overview
This is a fundamental networking lab focused on configuring a Cisco Router to inter-connect two distinct local area networks (LANs). The goal is to establish end-to-end connectivity between two workstations on different subnets.

## 🏗️ Topology
- **Router:** 1x Cisco 1941 (serving as the gateway).
- **Switch:** 1x Cisco 2960.
- **Hosts:** 2x Generic PCs.

## 🛠️ Configuration Highlights
- **Interface Assignment:** Configuring IP addresses on `G0/0` and `G0/1`.
- **Gateway Setup:** Ensuring both PCs point to the correct router interfaces.
- **Verification:** Using `show ip interface brief` to check the status of physical links.

## ✅ Validation
- **Connectivity:** Successful ping between PC0 and PC1.
- **Status:** All interfaces are in `up/up` state.

## 📁 Repository Contents
- `01_topology.png`
- `02_router_config.png`
- `03_pc_ip_setup.png`
- `04_ping_test.png`
