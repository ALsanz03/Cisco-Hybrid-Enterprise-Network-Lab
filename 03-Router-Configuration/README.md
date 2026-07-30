# Router Configuration

## Overview

This section documents the configuration of the R1-GATEWAY router used in the Cisco Hybrid Enterprise Network Lab.

The router provides gateway services for the on-premises network and enables communication between internal network devices and external network segments.

The router was configured with IPv4 addressing, active interfaces, and routing functionality to support network connectivity.

---

## Router Information

| Device Name | Model | Hostname | Physical Location | Purpose |
|---|---|---|---|---|
| R1-GATEWAY | Cisco 2911 Router | Router | Intercity > Home City > Corporate Office > Main Wiring Closet > Rack > R1 Gateway | Provides routing and gateway services for the network |

---

## Interface Configuration

| Interface | Status | IP Address | Subnet Mask | Purpose |
|---|---|---|---|---|
| GigabitEthernet 0/0 | Up | 192.168.100.1/24 | 255.255.255.0 | On-premises LAN gateway |
| GigabitEthernet 0/1 | Up | 172.16.255.1/30 | 255.255.255.252 | External/WAN connection |

---

## Network Role

R1-GATEWAY performs the following functions:

- Provides the default gateway for on-premises devices
- Routes traffic between network segments
- Connects the local network to external infrastructure
- Provides Layer 3 routing functionality

---

## Verification

![R1 Gateway Interface Configuration](R1%20Gateway%20Subnet.png)

Router connectivity was verified using:

show ip interface brief

This command confirms:

- Interface status
- Assigned IP addresses
- Active network connections

ping 
was used to verify communication between connected devices.

![Router Ping Test](router%20ping.png)
