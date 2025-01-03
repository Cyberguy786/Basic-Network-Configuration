# Basic Network Configuration using Packet Tracer

This project demonstrates a simple network setup using Cisco Packet Tracer with the following components:
- 1 Router
- 2 Switch
- 4 PCs

## Topology
![Network Topology](topology_diagram.png)

## Steps Performed
1. Configured the router and switch interfaces with the following IPs:
   - Router:
G0/0 (Switch 1): 192.168.1.1
G0/1 (Switch 2): 192.168.2.1
   - PC0: 192.168.1.10
   - PC1: 192.168.1.11
   - PC2: 192.168.2.10
   - PC3: 192.168.2.11
     
2. Verified connectivity by sending PDUs (ping) between devices.

## Files
- `basic_network_Config.pkt`: Packet Tracer file with the topology.
- `Router0_running-config.txt`: CLI configurations for the router.
