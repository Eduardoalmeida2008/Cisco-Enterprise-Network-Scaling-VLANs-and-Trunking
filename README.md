# Enterprise Network Scaling & Redundancy - Project 2

## 📌 Overview
This project focuses on the scalability and reliability of enterprise networks. It demonstrates the implementation of link aggregation, VLAN management protocols, and optimized trunking to ensure high availability and efficient bandwidth utilization in a Cisco environment.

## 🏗️ Technical Features
- **Link Aggregation (EtherChannel):** Configured LACP/PAgP to increase bandwidth and provide link redundancy between switches.
- **VLAN Trunking Protocol (VTP):** Automated VLAN propagation across the network to ensure consistency and reduce configuration errors.
- **STP Optimization:** Fine-tuned Spanning Tree Protocol to prevent loops while maintaining fast convergence.
- **Inter-VLAN Communication:** Integrated Layer 3 routing to connect distinct departmental segments.

## 🛠️ Configuration Highlights
- **EtherChannel:** Grouping physical interfaces into logical bundles for fault tolerance.
- **Trunking:** Implementation of IEEE 802.1Q for cross-switch VLAN communication.
- **Port Security:** (Optional, if used) Applied MAC-address filtering to secure access ports.

## ✅ Validation & Evidence
The network performance and stability were validated through:
- **Redundancy Tests:** Disconnecting physical links to verify EtherChannel failover.
- **VTP Status:** Confirming VLAN synchronization across the server-client hierarchy.
- **Connectivity Matrix:** Full ICMP (Ping) verification across all network nodes.

## 📁 Repository Contents
| File | Description |
| :--- | :--- |
| `01_network_topology.png` | Complete physical and logical diagram. |
| `02_etherchannel_status.png` | Verification of Port-Channel interfaces. |
| `03_vtp_configuration.png` | Evidence of VTP domain and mode setup. |
| `04_vlan_database.png` | Final VLAN distribution on all switches. |
| `05_connectivity_proof.png` | End-to-end ping tests success. |

---
*Technical dossier developed for infrastructure validation and portfolio demonstration.*
