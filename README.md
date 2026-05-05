# 🚀 Multi-Site Enterprise Network Design using Cisco Packet Tracer

## 📌 Overview
Designed and implemented a multi-site enterprise network with HQ and Branch connectivity.

## 🏢 Network Design
- Router0 (HQ)
- Router1 (Branch)
- Switch0, Switch1
- VLAN 10 → HR
- VLAN 20 → IT
- VLAN 30 → Sales
- VLAN 40 → Branch

## ⚙️ Features
- VLAN segmentation
- Router-on-a-stick
- OSPF routing
- DHCP
- ACL security (HR → IT blocked)

## 🔍 Verification
- show vlan brief
- show interface trunk
- show ip route
- show ip ospf neighbor

## 📸 Screenshots
## Topology
<img width="1918" height="1078" alt="01_Topology_Diagram" src="https://github.com/user-attachments/assets/8b95bf8f-c00b-4fc7-aa5d-7240f885ea16" />
## VLAN Config
<img width="1247" height="948" alt="04_Switch1_Branch_VLAN" src="https://github.com/user-attachments/assets/2a6fd881-808f-4ecc-a0ec-b3d05200f47a" />
<img width="1397" height="986" alt="02_Switch0_VLAN_Config" src="https://github.com/user-attachments/assets/6153e53e-555b-4254-b867-151358eea87f" />

## OSPF
<img width="1150" height="873" alt="06_Router1_OSPF_Neighbor" src="https://github.com/user-attachments/assets/ac719f52-a661-445a-ab4c-ec6fd72080e5" />
<img width="1097" height="875" alt="05_Router0_OSPF_Neighbor" src="https://github.com/user-attachments/assets/8761a6eb-2c24-46fa-9f59-a3c24f94a53c" />

## ACL
<img width="936" height="403" alt="10_Router0_access-list" src="https://github.com/user-attachments/assets/64ead6e5-20d0-417d-996b-e3d65d87ab76" />
<img width="923" height="333" alt="09_ACL_Blocking_Test" src="https://github.com/user-attachments/assets/9f23bb33-8c21-4a3a-97e9-7d3697367c17" />



## 🎯 Result
- Successful inter-VLAN communication
- HQ ↔ Branch connectivity
- Security implemented using ACL
