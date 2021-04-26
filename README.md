# Vlans-and-VTP

### Vlan
A virtual LAN is any broadcast domain that is partitioned and isolated in a computer network at the data link layer. LAN is the abbreviation for local area network and in this context virtual refers to a physical object recreated and altered by additional logic.

### VTP
VLAN Trunking Protocol is a Cisco proprietary protocol that propagates the definition of Virtual Local Area Networks on the whole local area network. To do this, VTP carries VLAN information to all the switches in a VTP domain. VTP advertisements can be sent over 802.1Q, and ISL trunks.

### Important Points
1. All switches in VTP are by default configured in server mode, but we still must update to double check
2. While using VTP, when we create new vlans, it gets updated at all switches except at the transparent mode switch, where we had to create new vlans.
3. Vlans can be implemented in scenarios when we want security over the network.
4. End devices over the same vlans were able to communicate which was not in case of those on different vlans.
