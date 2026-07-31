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

<img width="977" height="391" alt="Project1- Network Topology" src="https://github.com/user-attachments/assets/b87fab48-a7b5-4bc0-ad00-c4260997b9e0" />


## IP Addressing

| Device | Interface | IP Address |
|---------|-----------|------------|
| Router1 | Fa0/0 | 10.0.1.2 |
| Router1 | Fa0/1 | 10.0.0.1 |
| Router2 | Fa0/1 | 10.0.0.2 |
| Router2 | Fa0/0 | 10.1.0.2 |
| Router3 | Fa0/0 | 10.1.0.1 |
| Router3 | Fa0/1 | 10.1.1.2 |

## Configuration

Configured IP addressing and enabled interfaces using commands such as:
- interface FastEthernet
- ip address
- no shutdown

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
