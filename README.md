Project Overview

This project involved the design, configuration, and validation of a full-stack enterprise network using Cisco IOS. The architecture supports integrated data and voice services across multiple departments, emphasizing security, redundancy, and efficient traffic management.

Technical Accomplishments

Layer 2 Switching & Infrastructure
VLAN Segmentation: Configured and managed multiple VLANs to segregate Management, Data, and Voice traffic, improving network security and reducing broadcast domains.

Spanning-Tree Protocol (STP): Optimized the switching fabric by manually selecting Root Bridges to ensure a predictable, loop-free topology.

Trunking & Connectivity: Established 802.1Q trunking on Gigabit interfaces between switches and routers to support high-bandwidth inter-VLAN communication.

Port-Level Optimization: Implemented Voice VLANs and basic Quality of Service (QoS) on access ports to prioritize time-sensitive VoIP traffic.

Layer 3 Routing & Services

Router-on-a-Stick (ROAS): Engineered inter-VLAN routing by configuring sub-interfaces with Dot1Q encapsulation on a Cisco ISR.

Automated Addressing: Deployed DHCP pools directly on the router to provide dynamic IP addressing for LAN hosts and IP phones.

Gateway Connectivity: Configured static default routing and PAT (Port Address Translation) to provide internal hosts with secure internet access via a simulated ISP.

Network Security & Management

Device Hardening: Secured all infrastructure devices using enable secret passwords, RSA key generation for SSH, and encrypted local credentials.

Access Control Lists (ACLs): Implemented standard and extended ACLs to restrict VTY line access, ensuring only authorized management devices can remote into the network.

AAA Protocols: Enforced local authentication for console and VTY lines to prevent unauthorized physical and logical access.

Voice over IP (VoIP)
Telephony Service: Configured Cisco Unified Communications Manager Express (CME) features, including Ephone directory numbers and auto-registration for IP telephony.


Hardware/OS: Cisco IOS (Routers & Switches)

Protocols: 802.1Q, STP, SSH, DHCP, NAT, QoS, ACL

Tools: Cisco Packet Tracer / Lab Environment
