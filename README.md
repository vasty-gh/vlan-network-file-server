# vlan-network-file-server (Cisco Packet Tracer)
intervlan-routing-dhcp-network

## 🔍 Overview
This project demonstrates how to design and implement a segmented network using VLANs, inter-VLAN routing via a Layer 3 switch, DHCP, and a centralized file server.

## 🧱 Network Features
- VLAN Segmentation (VLAN 10, 20, 30, 40, 99)
- Inter-VLAN Routing with SVI on L3 Switch
- Dynamic IP assignment with DHCP
- Trunk links between switches
- File server accessible from all VLANs
- DNS set to 8.8.8.8

## 📐 Topology
![Network Topology](screenshots/topology.png)

## 🧪 Testing
- Successful DHCP leases for all PCs
- Inter-VLAN communication working
- File server accessed via browser and ping
- See `screenshots/` for results

## 🧾 IP Addressing Scheme

| VLAN | Name       | Network          | Subnet Mask          | Gateway         |
|------|------------|------------------|---------------------|------------------|
| 10   | HR         | 192.168.10.0     | 255.255.255.128     |  192.168.10.1    |
| 99   | Admin      | 192.168.50.0     | 255.255.255.192     | 192.168.50.1     |
| 30   | Finance    | 192.168.30.0     | 255.255.255.128     | 192.168.30.1     |
| 40   | Server     | 192.168.40.0     | 255.255.255.128     | 192.168.40.1     |
| 20   | IT         | 192.168.20.0     | 255.255.255.128     |  192.168.20.1    |

## ⚙️ How to Run
1. Open  in Cisco Packet Tracer.
2. Power on devices if needed.
3. Test ping between VLANs.
4. Access file server via browser or ping.

## 👩‍💻 Author
Vasty Ansomaah Adomako 
Student | Network Engineering Enthusiast

