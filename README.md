Secure Healthcare Network - README

 Overview
- Design and implement a secure network for Melbourne Health Services.
- Ensure confidentiality, integrity, and availability (CIA) with VLANs, DHCP, OSPF, and security measures.

Problem Statement
- Reliance on third-party IT services increases security risks and costs.
- Need for independent, secure, and scalable network infrastructure.
- Ensure seamless communication between HQ and branch hospital.

 Implementation Steps
1. Network Design & Planning
- Identify requirements for HQ and branch.
- Define VLAN segmentation and subnetting.
- Plan topology and device placements.

2. Network Configuration
- Set up VLANs and inter-VLAN routing.
- Configure OSPF for dynamic routing.
- Implement DHCP for dynamic IP allocation.

3. Security Measures
- Apply ACLs for access restrictions.
- Set up VPN for secure communication.
- Enable port-security and SSH.
- Implement NAT/PAT for public IP usage.

4. Testing & Validation
- Verify VLANs (`show vlan brief`).
- Check routing (`show ip route`).
- Ensure DHCP, VPN, and security functionality.

Network Topology
- Core Routers: Connect HQ and branch with redundancy.
- Multilayer Switches: Handle inter-VLAN communication.
- Access Switches: Connect end-user devices.
- Server Room: Hosts DHCP, DNS, web, and email servers.
- Wireless Access Points: Provide seamless connectivity.

 Expected Outcomes
- Improved security and reduced operational costs.
- Efficient communication with minimal latency.
- Scalable and reliable network design.
- Optimized bandwidth usage and performance.

Resources Used
- Cisco Packet Tracer for simulation.
- Cisco routers and switches.
- OSPF, VLANs, and subnetting.
- Security protocols: ACLs, VPN, SSH, NAT/PAT.

 Conclusion
- Secure, efficient, and scalable network for healthcare.
- Reduces costs, enhances security, and supports future expansion.


