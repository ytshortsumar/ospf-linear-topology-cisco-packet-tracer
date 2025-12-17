# OSPF Configuration on Three Routers (Cisco Packet Tracer)

## 📌 Project Overview
This project demonstrates the implementation of **Open Shortest Path First (OSPF)** routing
protocol on a **linear topology of three routers** using **Cisco Packet Tracer**.

The topology consists of:
- Three Cisco 2811 Routers
- Three 2960 Switches
- Three PCs
- Serial WAN links between routers
- Separate LANs for each router

OSPF is configured in **Area 0 (Backbone)** to enable dynamic routing and full network connectivity.

---

## 🧱 Network Topology
Router0 ↔ Router1 ↔ Router2

Each router connects to:
- One LAN (PC + Switch)
- One or two serial WAN links

---

## 🛠️ Technologies Used
- Cisco Packet Tracer
- Cisco 2811 Routers
- OSPF (Process ID: 1)
- IPv4 Addressing
- Serial (DCE/DTE) Connections

---

## 📊 IP Addressing Scheme

| Device  | Interface | IP Address       | Subnet Mask       |
|--------|----------|------------------|------------------|
| Router0 | Fa0/0 | 192.168.10.1 | 255.255.255.0 |
| Router0 | Se0/0/0 | 10.1.1.1 | 255.255.255.252 |
| Router1 | Fa0/0 | 192.168.20.1 | 255.255.255.0 |
| Router1 | Se0/0/0 | 10.1.1.2 | 255.255.255.252 |
| Router1 | Se0/0/1 | 10.2.2.1 | 255.255.255.252 |
| Router2 | Fa0/0 | 192.168.30.1 | 255.255.255.0 |
| Router2 | Se0/0/0 | 10.2.2.2 | 255.255.255.252 |

---

## ⚙️ Routing Protocol
- **OSPF**
- Process ID: `1`
- Area: `0`
- All LAN and WAN networks are advertised using wildcard masks

---

## ✅ Verification & Testing
- OSPF routes verified using:
show ip route
- Successful end-to-end connectivity tested using:

ping 192.168.30.2

---

## 📂 Files Included
- `OSPF_3_Routers_Linear_Topology.pkt` – Cisco Packet Tracer project file
- `README.md` – Project documentation

---

## 🎓 Learning Outcomes
- Understanding OSPF routing
- Working with serial links
- IP addressing and subnetting
- Network troubleshooting and verification

---

## 👤 Author
**Umar Bhatti**  
Networking Student
