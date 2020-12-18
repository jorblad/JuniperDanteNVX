# JuniperDanteNVX
Set of configuration for Juniper switches in Audio Video environment for DANTE and NVX.

The vlan device is one vlan that holds both Dante, NVX and control information, if you can separate it on different vlans that might work better.

QoS configuration is something I will add later but for now its only multicast and igmp-snooping that I have setup.

# Usage
Replace VLAN and interfaces with the one you want to use
Add these configuration lines to your configuration or enter configure mode and write load merge terminal and copy paste the content of the this configuration file and commit
