# 🏢 Enterprise Multi-Site Network Architecture Project – HQ Phase

## 🔧 Platform:
Cisco Packet Tracer

## 👨‍💻 Project Level:
Solutions Architect | Network Design and Implementation

---

## 📌 Overview
This is **Phase 1** of a multi-site enterprise network architecture project built using Cisco Packet Tracer. The goal is to design a secure, scalable, and fully functional network environment across a **Headquarters (HQ)** and two **Branch Offices**.

In this phase, I have fully implemented the **HQ network**, complete with routers, switches, VLANs, DHCP, DNS, OSPF, NAT, and device connectivity.

---

## 🏗️ Architecture Summary

### 🖥️ Devices Used at HQ:
- 2 Routers (ISR 4331)
- 2 Switches (Core, Access)
- 6 PCs
- 1 Servers (DHCP, DNS, Syslog)
- 1 Router (Simulating ISP)

### 🌐 Services Configured:
- **VLANs:** HR, IT, Finance, Guest, Admin, Management
- **Inter-VLAN Routing**
- **DHCP:** Configured at Server for all subnets
- **Syslog:** Logging from routers and switches
- **OSPF:** Dynamic routing protocol (Area 0)
- **NAT:** For private to public IP translation
- **Static Routing:** For default routes
- **Ping Tests:** All devices tested and reachable
- **Subnetting:** Based on CIDR for VLAN efficiency

---

## 📁 Files Included
- `Enterprise_Network_HQ.pkt` – Cisco Packet Tracer file for HQ setup
- `README.md` – Project explanation
- `network_diagram.png` –  Network topology screenshot
- `vlan_plan.txt` –  VLAN ID and IP mapping

---

## 🧠 What I Learned
- Network hierarchy (Core, Access layers)
- IP addressing and subnetting for scalability
- Router configuration with serial and Gigabit interfaces
- Configuring and verifying VLANs and trunk links
- Dynamic routing using OSPF
- NAT setup to allow internet access
- DHCP integration into enterprise architecture
- Practical use of tools like ACL, ping, and traceroute

---

## 🛠️ Tools Used
- Cisco Packet Tracer 8.x
- Subnetting Calculator

---

## 🔜 Upcoming (Next Phases)
- Add **Branch A** and **Branch B** with routers and switches
- Setup **site-to-site VPN tunnels** between branches and HQ
- Add **Access Control Lists (ACLs)** for security
- Integrate **wireless networking**
- Implement **redundancy** (HSRP/GLBP and EtherChannel)
- Add **Syslog & SNMP monitoring tools**

---

## 📎 Author
**Abdul Razzaq Talha**  
💬 [LinkedIn Profile](www.linkedin.com/in/abdulr-talha)  
📧 abdulrazzaqtalha24@gmail.com
