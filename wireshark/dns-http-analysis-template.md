# Wireshark DNS and HTTP Traffic Analysis Template

## Scenario

A packet capture is available for review. The goal is to identify normal and suspicious DNS or HTTP activity and document the analysis in a way that would be useful for a SOC ticket.

## Capture Summary

| Field | Details |
|---|---|
| Capture file |  |
| Date analyzed |  |
| Analyst | Oscar Arevalo |
| Environment | Lab or training capture only. |
| Objective |  |

## Useful Display Filters

| Goal | Wireshark Filter |
|---|---|
| DNS traffic | `dns` |
| HTTP traffic | `http` |
| TLS traffic | `tls` |
| Specific IP | `ip.addr == 192.0.2.10` |
| DNS queries | `dns.flags.response == 0` |
| HTTP requests | `http.request` |
| TCP errors or resets | `tcp.analysis.flags` |

## DNS Review

| Question | Observation |
|---|---|
| Which domains were queried? |  |
| Were there repeated failed lookups? |  |
| Were domains newly registered, misspelled, or suspicious? |  |
| Did any domain resolve to unusual IP space? |  |

## HTTP Review

| Question | Observation |
|---|---|
| Which hosts were contacted? |  |
| Which URIs were requested? |  |
| Were credentials or tokens exposed in cleartext? |  |
| Were there unusual user agents? |  |
| Were files downloaded? |  |

## Findings

| Finding | Evidence | Security Relevance | Recommendation |
|---|---|---|---|
|  |  |  |  |

## Defensive Takeaway

Summarize what the packet capture taught about detection, investigation, or network behavior.
