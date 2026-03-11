# CCNA OSPF Lab

This project demonstrates the configuration and verification of the Open Shortest Path First (OSPF) routing protocol using Cisco Packet Tracer.

## Lab Overview
The lab includes multiple routers connected in an OSPF Area 0 topology. Each router is configured with loopback interfaces and participates in OSPF routing.

## Objectives
- Configure IP addresses on router interfaces
- Configure loopback interfaces
- Enable OSPF on all routers
- Configure passive interfaces where appropriate
- Configure reference bandwidth for OSPF
- Configure R1 as an ASBR to advertise a default route
- Verify OSPF neighbor relationships

## Files Included
- Packet Tracer topology file (.pkt)
- Router configurations
- OSPF routing setup

## Verification Commands
The following commands were used to verify the configuration:

```
Do show ip interface brief 
show ip ospf neighbor  
show ip route  
show ip ospf interface
show running-config
show ip ospf database
```
## Toplagy  
<img width="765" height="347" alt="image" src="https://github.com/user-attachments/assets/f6c017c8-cb97-46aa-ad14-c8adb7963e9a" />

## What I learned
- Configured multi-router OSPF Area 0 topology
- Implemented loopback interfaces for router IDs
- Configured passive interfaces to reduce unnecessary OSPF updates
- Advertised a default route using an ASBR
- Verified adjacency and routing tables using Cisco IOS commands


## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI
