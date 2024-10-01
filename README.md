# Mathematics Olympiad Network Setup

## Overview
This project was created as part of a university assignment at Tecnológico de Monterrey, Campus Ciudad de México. The task was to design and configure a complete network for the Mexican National Mathematics Olympiad, connecting various groups such as reporters, students, professors, and staff.

## Project Scope
- **Objective**: Create a robust network capable of handling the needs of the event participants, ensuring seamless communication between different groups.
- **Network Design**: Includes switches and routers configured for specific subnets that correspond to different user groups.
  - **Reporters**: Dedicated VLANs and bandwidth for media coverage.
  - **Students**: A secure network for participants in the competition.
  - **Professors and Staff**: Separate networks with access to administrative tools.

## Features
- **VLAN Configuration**: Each user group (Reporters, Students, Professors, Staff) is assigned to its own VLAN, ensuring network segmentation and security.
- **Routing Protocols**: OSPF was implemented for dynamic routing between different network segments.
- **Access Control**: ACLs were set to limit access between different user groups and secure the network.
- **QoS Settings**: Quality of Service was applied to prioritize bandwidth for critical activities such as live reporting and event management.
- **Redundancy**: Redundant paths and failover mechanisms were implemented to ensure high availability throughout the event.

## How to Open the Project
1. Open Cisco PacketTracer.
2. Navigate to `File > Open`.
3. Select the project file `olympiad_network.pkt`.

## File Structure
- **olympiad_network.pkt**: The main PacketTracer file containing the full network setup.
- **configurations.txt**: Text file with the detailed configuration commands for switches, routers, and ACLs.
  
## Conclusion
This project successfully simulates the network requirements for a large-scale event, ensuring the smooth operation of all activities related to the Mexican National Mathematics Olympiad.

## Credits
Developed by Diego Samperio, Rodrigo Rocha, Leonardo López and Santiago Moreno for the course at Tecnológico de Monterrey, Campus Ciudad de México.
