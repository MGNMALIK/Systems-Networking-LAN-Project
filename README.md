# Systems-Networking-LAN-Project
Simulated small business LAN setup using Cisco Packet Tracer.

# Systems/Networking LAN Setup Project

This project simulates a small office LAN setup using Cisco Packet Tracer. It includes a router, switch, three PCs (2 static IPs + 1 DHCP), and a shared network printer. The goal is to demonstrate foundational networking skills and create a practical, testable environment for training or portfolio purposes.

---

## Network Topology

- 1 Router (`192.168.1.1`)
- 1 Switch (Layer 2)
- 2 PCs with static IPs
  - PC0: `192.168.1.10`
  - PC1: `192.168.1.11`
- 1 PC with dynamic IP (DHCP-assigned)
  - PC2: `192.168.1.12`
- 1 Printer with static IP: `192.168.1.50`

---

## Features Demonstrated

- Static & dynamic IP assignment
- Router configuration via CLI
- DHCP pool creation & exclusion rules
- Ping testing for device reachability
- Shared device (printer) simulation
- Network design using Packet Tracer

---

## Project Files

| File/Folder | Description |
|-------------|-------------|
| `packet_tracer_file/lan_project.pkt` | Saved Packet Tracer simulation |
| `network_diagram.png` | Screenshot of the topology |
| `ping_tests/` | Screenshots from ping results between devices |
| `configs/router_config.txt` | CLI commands used to configure the router |
| `configs/dhcp_config.txt` | DHCP setup commands |
| `configs/ip_plan.xlsx` | IP assignment plan for each device |
| `notes/troubleshooting_log.md` | Issues encountered and how they were fixed |

---

## How to Run

1. Open the `.pkt` file using Cisco Packet Tracer
2. Verify connections, open each PC’s Command Prompt
3. Ping the router, other PCs, and the printer
4. Review the configurations for learning

---

## Next Expansion Ideas

- Add VLANs for department segmentation
- Introduce inter-VLAN routing
- Add an external network + NAT on the router
- Simulate internet access with a second router

---

## Skills Practiced

- IP planning & subnetting
- Router CLI navigation
- Network troubleshooting with ping
- DHCP configuration
- Small-office LAN design principles

