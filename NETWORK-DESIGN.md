# Network Design & Configuration Guide

## Topology Type
Linear (Chain) Topology

## Routers
- Cisco 2811
- WIC-2T module installed for serial communication

## OSPF Design
- Single Area OSPF (Area 0)
- Dynamic route learning
- No static routes used

## Reason for OSPF
- Scalable
- Fast convergence
- Industry standard IGP

## Verification Commands
- show ip route
- show ip ospf neighbor
- ping
