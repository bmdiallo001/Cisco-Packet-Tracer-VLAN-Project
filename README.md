// Cisco Packet Tracer VLAN Project

    Overview
This project demonstrates VLAN segmentation and inter-VLAN routing (Router-on-a-Stick) using Cisco Packet Tracer.

    Topology
- VLAN 10: SalesFloor (192.168.10.0/24)
- VLAN 15: Engineering (192.168.15.0/24)
- Router sub-interfaces: Fa0/0.10, Fa0/0.15
- Switch-01 & Switch-02 with trunk links

      Configuration Highlights
- Created VLANs 10 and 15
- Assigned switch ports to correct VLANs
- Configured router sub-interfaces with dot1Q encapsulation
- Verified gateway, intra-VLAN, and inter-VLAN communication

      Verification
- SalesPCs <--> Gateway (192.168.10.1) 
- EngineeringPCs <--> Gateway (192.168.15.1) 
- Sales <--> Engineering PCs (cross-VLAN ping) 

      Skills Demonstrated
- VLAN creation and port assignment
- Trunk configuration
- Router-on-a-stick inter-VLAN routing
- Network troubleshooting and verification

      Final Score
- Gateway Reachability: 10/10
- Same VLAN Communication: 10/10
- Cross-VLAN Communication: 10/10
  
  Total: 30/30
