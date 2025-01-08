# Hotel Management Network Design & Implementation

## Overview
This project involves designing and implementing a network for a hotel management system using Cisco equipment and simulation tools. The aim is to ensure efficient communication, secure data transmission, and reliable connectivity for various departments within the hotel.

## Objectives
- Design a scalable and secure network topology for hotel operations.
- Implement VLANs, routing, and access control to segment and secure traffic.
- Ensure high availability and fault tolerance for critical services.
- Simulate and test the network using Cisco Packet Tracer.

## Features
- Segmented network with VLANs for different hotel departments (e.g., Front Desk, Management, Guest Wi-Fi).
- Inter-VLAN routing for seamless communication.
- Access Control Lists (ACLs) for enhanced security.
- DHCP and DNS configuration for dynamic IP allocation and name resolution.
- Backup and failover mechanisms for critical devices.

## Tools & Technologies
- Cisco Packet Tracer
- Cisco Routers and Switches
- VLANs and Inter-VLAN Routing
- Access Control Lists (ACLs)
- DHCP Configuration

## Subnet Allocation
- **IT**: `192.168.1.0/24`
- **Admin**: `192.168.2.0/24`
- **Sales**: `192.168.3.0/24`
- **HR**: `192.168.4.0/24`
- **Finance**: `192.168.5.0/24`
- **Logistics**: `192.168.6.0/24`
- **Store**: `192.168.7.0/24`
- **Reception**: `192.168.8.0/24`

## VLAN Allocation
- **VLAN 10**: IT Department
- **VLAN 20**: Admin Department
- **VLAN 30**: Sales Department
- **VLAN 40**: HR Department
- **VLAN 50**: Finance Department
- **VLAN 60**: Logistics Department
- **VLAN 70**: Store
- **VLAN 80**: Reception

## Design Highlights
- The network design efficiently divides the hotel into distinct VLANs (e.g., IT, Admin, Sales, HR, Reception, etc.), ensuring logical segmentation and improved security for each department.
- Interconnectivity between floors and departments is achieved using routers and switches, enabling seamless communication across the hotel.
- The use of VLANs enhances performance by reducing unnecessary traffic and isolating network segments to maintain data confidentiality.
- Wireless access points provide coverage for mobile devices, enhancing accessibility for both staff and guests.
- The network is scalable, allowing future expansions like adding more floors or departments without disrupting the existing configuration.

## Implementation Steps
1. **Network Planning**: Define the requirements and design the topology.
2. **VLAN Configuration**: Set up VLANs for different departments.
3. **Routing Setup**: Configure inter-VLAN routing on a Layer 3 switch or router.
4. **Security Implementation**: Apply ACLs to control access.
5. **IP Services**: Configure DHCP, DNS, and NAT.
6. **Testing**: Simulate and verify the network in Cisco Packet Tracer.
7. **Documentation**: Document configurations and troubleshooting steps.

## Usage
1. Open the provided Packet Tracer file.
2. Review the network topology and device configurations.
3. Simulate network operations and test connectivity.
4. Modify or extend the design as per requirements.

## Future Enhancements
- Implement Quality of Service (QoS) for prioritizing critical traffic.
- Add redundancy using HSRP/VRRP.
- Integrate a network monitoring system.

