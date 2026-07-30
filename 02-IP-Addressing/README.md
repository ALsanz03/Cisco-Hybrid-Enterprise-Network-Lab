# IP Addressing


## Overview

This section documents the IPv4 addressing scheme used throughout the Cisco Hybrid Enterprise Network Lab.

The network uses private IPv4 addressing to simulate a small business environment. Devices are assigned static IP addresses when permanent network identification is required, while user devices such as laptops and smartphones receive addresses dynamically through DHCP.

## Network Addressing

| Network Segment | Network Address | Subnet Mask | Purpose |
|---|---|---|---|
| On-Premises LAN | 192.168.100.0/24 | 255.255.255.0 | Internal office network |
| Gateway Router | 192.168.100.1 | 255.255.255.0 | Default gateway for internal devices |

## Device IP Assignments

| Device Name | IP Address | Assignment Method | Department |
|---|---|---|---|
| R1-GATEWAY | 192.168.100.1 | Static | Network Infrastructure |
| IT-PC1 | 192.168.100.20 | Static | IT |
| HR-PC1 | 192.168.100.50 | Static | HR |
| Sales-Laptop1 | DHCP | Dynamic | Sales |
| Management-Laptop1 | DHCP | Dynamic | Management |
| HelpDesk-Laptop1 | DHCP | Dynamic | Help Desk |
| IT-Smartphone1 | DHCP | Dynamic | IT |
| HR-Smartphone1 | DHCP | Dynamic | HR |
| Sales-Smartphone1 | DHCP | Dynamic | Sales |
| Management-Smartphone1 | DHCP | Dynamic | Management |
| HelpDesk-Smartphone1 | DHCP | Dynamic | Help Desk |

![IT-PC1 IP Address Configuration](Ip%20Addressing%20IT%20pc1.png)

## Subnetting Explanation

The on-premises network uses the 192.168.100.0/24 private IPv4 range.

The /24 subnet provides:

- 256 total addresses
- 254 usable host addresses
- One network address
- One broadcast address

![R1 Gateway Subnet Configuration](R1%20Gateway%20Subnet.png)

This addressing scheme provides enough available addresses for current users and future expansion.

## Verification

Network connectivity was verified using:

- ping
- ipconfig
- DHCP address assignment testing

Successful communication between network devices confirmed proper IP addressing and connectivity.
