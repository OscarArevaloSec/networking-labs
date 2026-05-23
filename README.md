# Networking Labs

This repository documents networking fundamentals and traffic-analysis practice with a security focus. The goal is to build the networking confidence needed for SOC analysis, incident triage, vulnerability management, and defensive troubleshooting.

## Topic Index

| Topic | Description | Portfolio Evidence | Status |
|---|---|---|---|
| Subnetting | CIDR, subnet masks, host ranges, and worked examples. | [Subnetting Notes](notes/subnetting.md) | Drafted |
| TCP and UDP | Three-way handshake, ports, flags, and service behavior. | [TCP UDP Notes](notes/tcp-udp.md) | Drafted |
| DNS | Resolution process, record types, suspicious domain patterns. | [DNS Notes](notes/dns.md) | Drafted |
| HTTP, HTTPS, and TLS | Request/response cycle, TLS handshake, certificates. | [HTTP TLS Notes](notes/http-tls.md) | Drafted |
| Wireshark Analysis | Capture filters, display filters, traffic interpretation. | [DNS and HTTP Analysis Template](wireshark/dns-http-analysis-template.md) | Drafted |
| Firewall Rules | Default-deny principles and rule documentation. | [Firewall Notes](notes/firewall-rules.md) | Template |

## Tools Used

| Tool | Purpose |
|---|---|
| Wireshark | Packet capture review and protocol analysis. |
| tcpdump | Command-line packet capture. |
| Nmap | Authorized host and service discovery in labs. |
| ss and netstat | Local socket and listening-service review. |
| dig and nslookup | DNS query testing and troubleshooting. |

## Portfolio Standard

Each networking lab should explain the question being answered, the traffic reviewed, the filters used, the observations, the security relevance, and the defensive takeaway.
