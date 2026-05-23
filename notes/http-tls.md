# HTTP, HTTPS, and TLS Notes

HTTP and TLS traffic analysis helps defenders understand web activity, identify suspicious downloads, and recognize when sensitive data may be exposed.

| Concept | Security Relevance |
|---|---|
| HTTP method | GET, POST, PUT, DELETE, and other methods can reveal application behavior. |
| Status code | Responses such as 200, 301, 403, 404, and 500 help explain web activity. |
| User-Agent | Unusual user agents can indicate scripts, malware, or automation. |
| TLS certificate | Certificate issuer, subject, validity, and mismatch can add investigation context. |
| SNI | Server Name Indication can reveal the domain requested during TLS negotiation. |

## Defensive Use

A SOC analyst can use HTTP and TLS evidence to support phishing investigations, malware download analysis, proxy-log review, and suspicious browsing alerts.
