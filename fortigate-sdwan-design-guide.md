# FortiGate SD-WAN Design Guide

## Overview

FortiGate SD-WAN enables intelligent traffic steering across multiple WAN links using application-aware routing and performance-based path selection.

## SD-WAN Components

### SD-WAN Zones

- WAN1
- WAN2
- MPLS
- Internet

### SD-WAN Members

- MPLS Circuit
- Broadband Internet
- LTE Backup

## Performance SLA

Monitor:

- Latency
- Jitter
- Packet Loss

## SD-WAN Rules

- Business Applications
- Voice Traffic
- Video Traffic
- Internet Browsing

## Application-Aware Routing

Benefits:

- Better user experience
- Dynamic traffic steering
- SLA-based routing

## WAN Failover

- Automatic failover
- Link health monitoring
- Session preservation

## Dynamic Path Selection

Traffic automatically switches to the best available WAN circuit based on SLA measurements.

## Branch Connectivity

- Branch Offices
- Headquarters
- Data Centers
- Cloud Connectivity

## Security Integration

- NGFW
- IPS
- Antivirus
- Web Filtering
- Application Control

## Best Practices

- Configure Performance SLA
- Use redundant WAN circuits
- Enable SD-WAN monitoring
- Test failover regularly

## Troubleshooting Tips

Check:

- SD-WAN Health
- SLA Status
- Routing Table
- VPN Tunnel Status
- WAN Link Utilization

## Real-World Example

Implemented FortiGate SD-WAN using MPLS and broadband circuits with SLA-based routing to improve application performance and provide automatic WAN failover.
