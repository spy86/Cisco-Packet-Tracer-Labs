### InterVLAN ###

### Description ###

You are the Network Administrator at Ranet, and have to config both switch "Ranet-SW" and router "Ranet-GW" via its console terminal as below:

1. Set Ranet-SW to seperate VLAN to be VLAN 10 and VLAN 20 and set its member as: VLAN 10: Fa0/1, Fa0/2 VLAN 20: Fa0/3, Fa0/4
3. Enable feature "Portfast" on all access ports.
2. Set both Ranet-SW and Ranet-GW to route between VLAN 10 and VLAN 20: - Use interface Fa0/0.1 and Fa0/0.2 on Ranet-GW as sub-interface for VLAN 10 and VLAN 20 respectively - Please note that all hosts in each VLAN set IP Default Gateway to be the last IP of its own subnet.

If everything is correct, All hosts will be able to connect with each other.

### Topology ###

![Alt Text](https://content.screencast.com/users/snajperm14/folders/Default/media/93e0782f-34e6-438f-87fd-d8b701fb1355/netwo04.PNG)
