# Multi-VLAN-DHCP-Network
Multi VLAN network configuration with DHCP and inter-VLAN routing using Cisco Packet Tracer

## Project Overview
- Configured a multi-VLAN network for IT, HR, and Sales departments using Cisco Packet Tracer.
- Created VLAN Segmentation, enabled inter-VLAN routing using Router-on-a-Stick, and configured DHCP on the router for automatic IP addressa assignment.
## Tools Used
- Cisco Packet Tracer.
## Network Design
- VLAN 2 IT - 192.168.1.0/24
- VLAN 3 HR - 192.168.2.0/24
- VLAN 4 Sales - 192.168.3.0/24
## Configuration Details
- Created VLANs on Switch
- Configured trunk port between router and switch
- Crated router sub-interfaces using dot1Q
- Assigned gateway IP address
- Configured DHCP pools for each VLAN
- Connected end devices through access ports
## Testing & Verification
- Verified IP address allocation using ipconfig
- Tested inter-VLAN communication using ping
- Checked DHCP bidings on router
- Verified VLAN configuration using show vlan brief
## Outcome 
- All departments received automatic IP address and successfully, communicated across VLANS.
