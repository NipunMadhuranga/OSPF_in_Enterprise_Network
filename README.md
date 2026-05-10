🚀 OSPF Dynamic Routing with Inter-VLAN & DHCP – Enterprise Network Simulation (Cisco Packet Tracer) 🌐

Successfully designed and implemented a multi-site enterprise network using OSPF Area 0 as the core dynamic routing protocol, supported by router-on-a-stick inter-VLAN routing, VLAN segmentation, WAN serial links, and per-VLAN DHCP services. 💻🔥

🔹 OSPF Dynamic Routing (Area 0) 🧠
Configured single-area OSPF across three routers (R1, R2, R3) for dynamic route exchange.
✅ Network statements added for all LAN and WAN subnets using wildcard masks
✅ Verified OSPF adjacencies: LOADING → FULL state achieved
✅ show 'ip route ospf' confirmed OSPF-learned routes – no static routes required

🔹 VLAN Segmentation & Trunking 🧩
Created VLANs across switches S1,S2 and S3.
✅ Access ports assigned to end devices
✅ Trunk ports configured for switch-to-switch and router-to-switch connectivity

🔹 Router-on-a-Stick Inter-VLAN Routing 🚦
Configured 802.1Q subinterfaces on all three routers.
🔸 R1: G0/0.60, .70, .80
🔸 R2: G0/0.30, .40, .50
🔸 R3: G0/0.10, .20
🔸 Enabled inter-VLAN communication across all VLANs using a single physical interface per router


🔹 Per-VLAN DHCP 📡
Automated IP assignment for end devices.
✔ R1: DHCP pools for VLAN 60, 70, 80
✔ R2: DHCP pools for VLAN 30, 40, 50
✔ R3: DHCP pools for VLAN 10, 20
✔ Gateway addresses excluded from each pool
✔ Verified IP leases on all end devices

🔹 Verification & Troubleshooting 🛠️
Used standard Cisco IOS tools to validate functionality.
🔍 show ip interface brief – Interface status
🔍 show ip route / show ip ospf neighbor – OSPF routes & adjacencies
🔍 show ip dhcp binding – DHCP leases

🔹 Connectivity Testing 📡
Verified end-to-end communication across all VLANs and routers using ICMP ping.
📉 Achieved full connectivity across all VLANs

📌 This lab enhanced my understanding of:
✅ OSPF single-area configuration, adjacency formation, and route propagation
✅ Router-on-a-stick with 802.1Q subinterfaces
✅ VLAN trunking and access port configuration
✅ Per-VLAN DHCP server setup
✅ WAN serial link configuration (clock rate, DCE/DTE)
✅ Structured network troubleshooting


