# CCNA-Static-Routing-Project

# Cisco Packet Tracer - Static Routing Project

## Overview
This project demonstrates configuring static routes between three Cisco routers to allow communication between different networks.

## Objectives
- Rename each host to clearly understand which device belongs where
- Configure IP addresses on router interfaces
- Configure static routes
- Copy running configuration to startup
- Verify end-to-end connectivity
- Test routing using ping and traceroute commands

## Network Topology

<img width="933" height="321" alt="Project1 - Network Topology" src="https://github.com/user-attachments/assets/1cbecc8b-a24e-44b5-9ec4-85ff4a196e1d" />


## IP Addressing

| Device | Interface | IP Address |
|---------|-----------|------------|
| Router1 | Fa0/0 | 10.0.1.2 |
| Router1 | Fa0/1 | 10.0.0.1 |
| Router2 | Fa0/1 | 10.0.0.2 |
| Router2 | Fa0/0 | 10.1.0.2 |
| Router3 | Fa0/0 | 10.1.0.1 |
| Router3 | Fa0/1 | 10.1.1.2 |
| PC1     | Fa0   | 10.0.1.3 |
| PC3     | Fa0   | 10.1.1.3 |

## Configuration

Configured IP addressing and enabled interfaces using commands such as:
- 'interface FastEthernet'
- 'ip address'
- 'duplex auto'
- 'speed auto'
- 'no shutdown'

Configured static routes on each router to reach remote networks.

## Verification

- Successful ping from PC1 to PC2
- Checked the traceroute it took from each device
- Verified routing tables
- Confirmed end-to-end connectivity

## Skills Demonstrated

- Cisco IOS CLI
- Interface configuration
- Static routing
- IP addressing
- Network troubleshooting

## Files Included

- **Packet Tracer/Static Routing Project.pkt** - Cisco Packet Tracer lab file
- **Configs/** - Router running configurations
- **Images/** - Screenshots of the topology and verification tests
