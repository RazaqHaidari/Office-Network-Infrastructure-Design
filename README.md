Office Network Infrastructure Design
Overview

This project demonstrates the design and implementation of a structured office network using Cisco Packet Tracer. The network connects multiple departments and enables communication between them using routers, switches, and proper IP addressing.

Network Structure

The network is divided into the following departments:

Computer Department → 192.168.1.0/24
IT Department → 192.168.2.0/24
Chairman Department → 192.168.3.0/24
Server Room → 1.0.0.0/8

Each department is connected through switches, and routers are used to enable communication between different networks.

Technologies Used
Cisco Packet Tracer
Routing (Static Routing)
IP Addressing and Subnetting
LAN Switching
WAN (Serial Connection)
Devices Used
Routers (2)
Switches
PCs
Server
Configuration Summary
Router Configuration
Interfaces configured with IP addresses
Serial connection between routers (10.0.0.0 network)
Static routing implemented for inter-network communication
Example Commands
enable
configure terminal

interface fastEthernet0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

ip route 192.168.3.0 255.255.255.0 10.0.0.1
Features
Communication between all departments
Centralized server access
Organized network using subnetting
Simulation-based packet flow verification
Testing

The network was tested using:

Ping command for connectivity
Simulation mode for packet flow
Router verification commands:
show ip interface brief
show ip route
How to Use
Open the project file in Cisco Packet Tracer
Switch to Simulation mode (optional)
Test connectivity using ping
Observe packet flow using Simple PDU
Project Outcome

The network successfully allows communication between all departments and provides access to centralized resources through proper routing and configuration.

Future Improvements
Implement dynamic routing (RIP/OSPF)
Add VLANs for better segmentation
Improve network security (ACLs, port security)
Optimize IP addressing
Author

Razaq Haidari
