# TCP and UDP Notes

TCP and UDP behavior matters in security analysis because many alerts are based on ports, flags, session behavior, and expected service communication.

| Protocol | Characteristics | Security Relevance |
|---|---|---|
| TCP | Connection-oriented, uses handshake and flags. | Useful for identifying scans, sessions, resets, and service behavior. |
| UDP | Connectionless, lower overhead. | Common in DNS, DHCP, VoIP, and some tunneling or amplification activity. |

## Defensive Use

Understanding TCP and UDP helps analysts interpret Nmap results, firewall logs, packet captures, and suspicious connection attempts.
