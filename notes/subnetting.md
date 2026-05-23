# Subnetting Notes

Subnetting is important for defenders because it helps analysts understand asset ranges, firewall rules, routing boundaries, and whether traffic is internal or external.

| Concept | Explanation |
|---|---|
| CIDR | A notation such as `/24` that describes how many bits are used for the network portion. |
| Network address | The first address in the subnet, used to identify the network. |
| Broadcast address | The final address in an IPv4 subnet, used for broadcast traffic. |
| Usable host range | Addresses that can normally be assigned to hosts. |
| Default gateway | The router address used to reach other networks. |

## Defensive Use

A SOC analyst who understands subnetting can better evaluate firewall logs, VPN logs, IDS alerts, and lateral movement patterns.
