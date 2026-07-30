# Switch Configuration
## Overview

This section documents the configuration and role of the SW1-CORE switch used in the Cisco Hybrid Enterprise Network Lab.

The core switch provides connectivity between wired network devices within the on-premises environment. It serves as the central connection point between the gateway router, wireless infrastructure, and end-user devices.

The switch configuration was verified to ensure proper device connectivity and network communication.

## Verification

The switch configuration was verified using Cisco IOS commands: show interfaces status

show interfaces status
This command was used to verify active switch ports and connected devices.
![Switch Interface Status](Switch%20interface.png)

show vlan brief
This command was used to verify VLAN availability and port assignments.
![Switch VLAN Configuration](Switch%20Vlan.png)

show mac address-table
This command was used to verify that the switch was learning connected device MAC addresses.
![Switch MAC Address Table](Switch%20Mac%20Address.png)



