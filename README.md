Operation RouteStorm

Three-Router Network with Static Routing | Cisco Packet Tracer

1. Project Overview

Operation RouteStorm is a multi-site network simulation designed and implemented using Cisco Packet Tracer. The project connects a Headquarters (HQ) network with two branch office networks using three routers and static routing.

The network demonstrates communication between geographically separate LANs through point-to-point router connections.

2. Network Topology

The network consists of three sites:

- Headquarters (HQ): R1-HQ, SW-HQ, PC1 and PC2
- Branch A: R2-BranchA, SW-A, PC3 and PC4
- Branch B: R3-BranchB, SW-B, PC5 and PC6

Router connectivity:

- R1-HQ connects to R2-BranchA.
- R2-BranchA connects to R3-BranchB.

3. IP Addressing Plan

Network| Network Address| Default Gateway
HQ LAN| 192.168.10.0/24| 192.168.10.1
Branch A LAN| 192.168.20.0/24| 192.168.20.1
Branch B LAN| 192.168.30.0/24| 192.168.30.1
HQ–Branch A link| 10.0.0.0/30| Point-to-point
Branch A–Branch B link| 10.0.0.4/30| Point-to-point

4. Objectives

- Design a multi-site network using three routers.
- Configure LAN addressing and router interfaces.
- Implement static routing between the three networks.
- Use /30 subnets for point-to-point router links.
- Establish end-to-end connectivity between all sites.
- Verify routing and network operation using Cisco IOS commands.

5. Configuration and Implementation

The network was implemented using Cisco Packet Tracer.

The main implementation activities included:

1. Creating the HQ and two branch-office topologies.
2. Connecting routers, switches and end devices.
3. Configuring IPv4 addressing.
4. Configuring point-to-point router links.
5. Implementing static routes to reach remote LANs.
6. Verifying routing tables and interface status.

6. Verification and Testing

The following commands were used during verification:

show ip route
show ip interface brief
ping
copy running-config startup-config

Testing included:

- Checking router interface operational status.
- Verifying static routes to remote LANs.
- Testing connectivity between HQ and Branch A.
- Testing connectivity between Branch A and Branch B.
- Verifying communication across the multi-site network.

Result: All reported connectivity tests completed with 0% packet loss.

7. Skills Practised

- Cisco Packet Tracer network simulation
- Router and switch configuration
- IPv4 addressing and subnetting
- /30 point-to-point subnetting
- Static routing using Cisco IOS
- Routing table verification
- Network connectivity troubleshooting
- Basic multi-site network design

8. Repository Structure

Operation-RouteStorm/
│
├── README.md
├── report/
│   └── Project_Report.pdf
│
└── packet-tracer/
    ├── Operation_RouteStorm.pkt
    └── screenshots/

9. Project Outcome

Successfully designed, configured and tested a three-router network connecting Headquarters and two branch offices. Static routing enabled communication between the three LANs, demonstrating the fundamentals of multi-site network connectivity.

10. Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4 addressing and static routing

11. Project Scope

This project is an educational network simulation developed to practise routing, addressing, configuration and connectivity verification concepts. It is not a production deployment.

---

Project: Operation RouteStorm
Category: Computer Networking
Platform: Cisco Packet Tracer

12. Project Screenshots

[View All Project Screenshots](packet-tracer/screenshots/)
