# DNS Notes

DNS translates names into IP addresses. For defenders, DNS is valuable because malware, phishing pages, command-and-control infrastructure, and suspicious tools often generate observable DNS activity.

| Record Type | Purpose |
|---|---|
| A | Maps a domain to an IPv4 address. |
| AAAA | Maps a domain to an IPv6 address. |
| CNAME | Points one name to another name. |
| MX | Identifies mail servers for a domain. |
| TXT | Stores text records, often used for verification and email security. |
| NS | Identifies authoritative name servers. |

## Defensive Questions

| Question | Why It Matters |
|---|---|
| Is the domain expected for the user or application? | Helps distinguish normal activity from suspicious traffic. |
| Is the domain misspelled or impersonating a brand? | May indicate phishing or typosquatting. |
| Are there many failed lookups? | May indicate malware domain-generation behavior or misconfiguration. |
| Is DNS going to an unusual resolver? | May indicate tunneling or bypass attempts. |
