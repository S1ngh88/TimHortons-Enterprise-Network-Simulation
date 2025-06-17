# Tim Hortons Enterprise Network Simulation 🌐

This project simulates a fully connected multi-branch enterprise network for Tim Hortons using Cisco Packet Tracer. It covers secure network design, dynamic IP allocation, inter-branch routing, and remote administration using SSH.

## 🌍 Branches Included
- Wolverhampton (Head Office)
- Birmingham
- London
- Manchester

## 📌 Key Features
- **VLAN Segmentation** for Staff and Guest Wi-Fi (VLANs 10–60)
- **DHCP Configuration** per VLAN to automate IP addressing
- **OSPF Routing** across all branches for dynamic route updates
- **SSH Security Setup** – Remote access allowed only from Admin PC (192.168.70.12)
- **Wireless Access Points** with dual SSIDs (Staff / Guest)
- **Access Control** to prevent Guest network from communicating with internal hosts

## 🔒 Security
- SSH-only access for routers
- Guest Wi-Fi isolation via VLAN + ACL concepts
- Admin-only remote access from secure head office machine

## 🖼️ Network Topology
![Network Topology](./NetworkDiagram.png)

## 📂 Files Included
- **Configurations/** – All router and switch commands
- **PacketTracer/** – Complete .pkt file
- **Documentation/** – Final PDF report explaining all steps

## 💻 Tools Used
- Cisco Packet Tracer
- VLANs, DHCP, OSPF, SSH
- Wi-Fi SSID Mapping
- Subnetting and IP Routing

## 🧠 Author
Prince Singh  
[LinkedIn](https://www.linkedin.com/in/princesingh137/)
