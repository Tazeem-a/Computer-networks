Company Network Design & Implementation
A comprehensive network simulation featuring advanced routing, switching, and security protocols. 


Overview
This project simulates a complete corporate infrastructure using Cisco Packet Tracer. It demonstrates the integration of fundamental and advanced networking concepts to ensure a scalable, secure, and efficient business environment. 


Key Features & Concepts
Subnetting & IP Planning: Optimized IPv4 addressing using VLSM to reduce IP wastage across various departments.
VLANs & Inter-VLAN Routing: Logical segmentation of departments (HR, Finance, IT) with Router-on-a-Stick configuration for secure communication.
DHCP: Automated IP assignment via dedicated DHCP pools for wired and wireless clients.
Dynamic Routing (RIP): Implementation of RIPv2 for seamless packet exchange across different network segments.
Security (ACLs): Standard and Extended Access Control Lists to permit or deny specific traffic (e.g., blocking Finance access from the Guest network).
Wireless Connectivity: Implementation of WLAN using Access Points/Wireless Routers with WPA2 security for mobile devices. 


Topology Architecture
Core Layer: Provides centralized routing, dual ISP connectivity, and handles inter-VLAN and external network traffic.
Distribution/Access Layer: Layer 3 and Layer 2 switches manage VLANs, aggregate departmental traffic, and connect end devices.
End Devices: PCs, laptops, wireless devices, printers, and centralized servers (DNS, Web, Email, DHCP) connected per department VLAN.
Getting Started


Download: Ensure you have the latest version of Cisco Packet Tracer installed.
Clone: Use the command git clone <https://github.com/Tazeem-a/Computer-networks/>.
Run: Open the .pkt file directly to explore the configurations and simulation. 

