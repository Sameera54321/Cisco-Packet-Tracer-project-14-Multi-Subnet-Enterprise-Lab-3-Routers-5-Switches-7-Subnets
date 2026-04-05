# Cisco-Packet-Tracer-project-14-Multi‑Subnet Enterprise Lab – 3 Routers, 5 Switches, 7 Subnets

I’m excited to share my latest Cisco Packet Tracer project – a multi‑subnet enterprise network with two routers (Router0, Router1), three 2960 switches, multiple PCs, and a server. The topology spans seven different IP subnets, including 20.10.10.0/8, 20.10.20.0/24, 192.168.0.0/24, 192.168.50.0/24, 172.16.31.0/16, 10.10.10.0/8, and 200.10.150.0/24.

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-14-Multi-Subnet-Enterprise-Lab-2-Routers-3-Switches-7-Subnets/blob/main/7.jpg?raw=true)

## 📌 Summary

### Multi‑Subnet Enterprise Lab is a Cisco Packet Tracer simulation that models a small but complex corporate network. It includes:

    2 routers (Cisco 2911 or similar – named Router0, Router1)

    3 switches (Cisco 2960‑24TT – Switch0, Switch2, Switch3)

    Multiple end devices – PCs and one server (Server0)

    7 distinct IP subnets (see table below)

### The project demonstrates:

    Routing between different subnets using static routes or a dynamic protocol (OSPF recommended)

    VLAN creation on switches to isolate traffic (e.g., VLAN 10 for 192.168.0.0/24, VLAN 20 for 192.168.50.0/24, etc.)

    Switch‑to‑router connections (trunk or access ports)

    Server‑based services – DHCP to assign IPs to PCs, DNS, or HTTP

    Basic troubleshooting – ping, traceroute, show ip route, show vlan

## ✨ Features

    ✅ 2 routers – fully configurable for static or dynamic routing

    ✅ 3 switches – support VLANs, trunking, STP, port security

    ✅ Multiple subnets – 20.10.10.0/8, 20.10.20.0/24, 192.168.0.0/24, 192.168.50.0/24, 172.16.31.0/16, 10.10.10.0/8, 200.10.150.0/24

    ✅ Inter‑router connectivity – Router0 ↔ Router1 via 20.10.10.0/8 or 20.10.20.0/24

    ✅ Server0 – provides network services (DHCP, DNS, web)

    ✅ VLAN segmentation – logical separation of PCs and server

    ✅ Full Packet Tracer file (.pkt) – ready to open and practise

    ✅ Documentation – IP addressing plan, VLAN mapping, routing table examples

### Sample IP addressing:

| Device | IP Address | Subnet / Mask |
| :--- | :--- | :--- |
| Router0 (int 1) | 20.10.10.1 | 20.10.10.0/8 |
| Router0 (int 2) | 20.10.20.2 | 20.10.20.0/24 |
| Router0 (int 3) | 192.168.0.1 | 192.168.0.0/24 |
| Router0 (int 4) | 10.10.10.1 | 10.10.10.0/8 |
| Router0 (int 5) | 192.168.50.1 | 192.168.50.0/24 |
| Router1 (int 1) | 20.10.10.2 | 20.10.10.0/8 |
| Router1 (int 2) | 20.10.20.3 | 20.10.20.0/24 |
| Router1 (int 3) | 172.16.31.1 | 172.16.31.0/16 |
| Router1 (int 4) | 200.10.150.1 | 200.10.150.0/24 |
| PC1 | 192.168.0.10 | 192.168.0.0/24 |
| PC2 | 192.168.50.25 | 192.168.50.0/24 |
| PC3 | 10.10.10.10 | 10.10.10.0/8 |
| Server0 | 172.16.31.12 | 172.16.31.0/16 |
| (other PC) | 200.10.150.10 | 200.10.150.0/24 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – all router, switch, and end‑device configurations

    (Optional) Text editor – for documenting configs

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add new features – e.g., dynamic routing (OSPF), additional VLANs, NAT, or a wireless AP.

    Improve security (ACLs, port security, SSH).

    Update the documentation with new IP schemes or diagrams.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
