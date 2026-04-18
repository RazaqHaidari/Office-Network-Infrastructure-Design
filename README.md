# Office Network Infrastructure Design

## Overview
This project demonstrates the design and implementation of a structured office network using Cisco Packet Tracer. The network connects multiple departments and enables communication between them using routers, switches, and proper IP addressing.

## Network Structure
The network is divided into the following departments:

- Computer Department → 192.168.1.0/24  
- IT Department → 192.168.2.0/24  
- Chairman Department → 192.168.3.0/24  
- Server Room → 1.0.0.0/8  

Each department is connected through switches, and routers are used to enable communication between different networks.

## Technologies Used
- Cisco Packet Tracer  
- Static Routing  
- IP Addressing and Subnetting  
- LAN Switching  
- WAN (Serial Connection)  

## Devices Used
- Routers (2)  
- Switches  
- PCs  
- Server  

## Configuration Summary

### Router Configuration
- Interfaces configured with IP addresses  
- Serial connection between routers (10.0.0.0 network)  
- Static routing implemented  

### Example Commands

enable
configure terminal

interface fastEthernet0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

ip route 192.168.3.0 255.255.255.0 10.0.0.1


## Features
- Communication between all departments  
- Centralized server access  
- Organized network using subnetting  
- Packet flow verification using simulation  

## Testing
The network was tested using:

- Ping command  
- Simulation mode  
- Router commands:
  - show ip interface brief  
  - show ip route  

## How to Use
1. Open the project in Cisco Packet Tracer  
2. Switch to Simulation mode (optional)  
3. Test using ping  
4. Use Simple PDU to observe packet flow  

## Project Outcome
The network successfully allows communication between all departments and provides centralized access to resources.

## Future Improvements
- Implement dynamic routing (RIP/OSPF)  
- Add VLANs  
- Improve network security  
- Optimize IP addressing  

## Author
Razaq Haidari
