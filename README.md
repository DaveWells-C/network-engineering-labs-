# Network Engineering Labs (Cisco Packet Tracer)

A collection of hands-on network engineering labs built in **Cisco Packet Tracer** to practice enterprise routing, switching, network services, and security fundamentals. Each project includes the `.pkt` topology file, full Cisco IOS CLI configuration exports, an annotated network diagram, and troubleshooting documentation.

## Core Skills & Technologies
* **Switching & Segmentation:** VLANs, 802.1Q Trunking, Layer 3 Switched Virtual Interfaces (SVIs), Inter-VLAN Routing, Spanning Tree PortFast
* **Routing & WAN:** Static Routing, Router-on-a-Stick, OSPF Dynamic Routing, NAT/PAT
* **Network Services:** Cisco IOS DHCP Server Pools & Exclusions, DNS, HTTP
* **Network Security:** Extended Access Control Lists (ACLs), Traffic Filtering, Guest Wi-Fi Isolation (WLC)
* **Tools:** Cisco IOS CLI, Cisco Packet Tracer

---

## Lab Portfolio Index
| # | Project Folder | Key Concepts | Devices Used |
| :--- | :--- | :--- | :--- |
#example | **00** | [Basic Routing, DHCP & DNS Services](./00-basic-routing-dhcp-dns) | Multi-subnet routing, Cisco IOS CLI, DHCP pools, local DNS & HTTP web hosting | 2911 Router, 2960 Switches, Server, PCs |

---

## Repository Structure
Every lab folder follows a standardized layout for clarity and reproducibility:
* `README.md` — Project objectives, IP addressing scheme, verification tests, and troubleshooting notes.
* `topology.png` — Visual diagram of the network layout with subnet and VLAN annotations.
* `*.pkt` — Native Cisco Packet Tracer file ready to download and run.
* `configs/` — Plain-text exports of `show running-config` for every configured network device.


