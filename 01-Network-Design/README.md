
## Network Architecture

The network consists of two primary environments:

### On-Premises Network

The on-premises environment represents the company's local office infrastructure.

Components include:

- Gateway Router
- Core Switch
- Wireless Access Point
- Desktop Computers
- Wireless Laptops
- Mobile Devices

The on-premises network uses the IPv4 address range: 192.168.100.0/24

---

### Cloud Environment

The cloud environment represents external infrastructure and hosted services.

Components include:

- Cloud Router
- Cloud Switch
- Cloud Server

The cloud network uses the IPv4 address range: 10.10.10.0/24

![Hybrid Enterprise Network](../Screenshot%202026-07-30%20125204.png)


## Devices Used

| Device Name | Device Type | IP Address | Purpose | Network Location |
|---|---|---|---|---|
| R1-GATEWAY | Cisco Router | 192.168.100.1 | Main gateway providing routing for the on-premises network | On-Premises |
| SW1-CORE | Cisco Switch | N/A | Central switch connecting wired network devices | On-Premises |
| WAP1-Corporate | Wireless Router/AP (WRT300N) | DHCP | Provides wireless connectivity for corporate devices | On-Premises |
| IT-PC1 | PC | 192.168.100.20 | IT department workstation | On-Premises |
| HR-PC1 | PC | 192.168.100.50 | HR department workstation | On-Premises |
| Sales-Laptop1 | Laptop | DHCP | Sales department wireless workstation | Wireless |
| Management-Laptop1 | Laptop | DHCP | Management department wireless workstation | Wireless |
| HelpDesk-Laptop1 | Laptop | DHCP | Help Desk department wireless workstation | Wireless |
| IT-Smartphone1 | Smartphone | DHCP | Mobile device for IT department | Wireless |
| HR-Smartphone1 | Smartphone | DHCP | Mobile device for HR department | Wireless |
| Sales-Smartphone1 | Smartphone | DHCP | Mobile device for Sales department | Wireless |
| Management-Smartphone1 | Smartphone | DHCP | Mobile device for Management department | Wireless |
| HelpDesk-Smartphone1 | Smartphone | DHCP | Mobile device for Help Desk department | Wireless |
