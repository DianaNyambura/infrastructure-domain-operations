# Case Study 1: Domain DNS Migration & Configuration (n8n private hosting)

## Objective
Migrate a domain from shared hosting to a VPS while maintaining uptime and ensuring proper email routing.

## Environment
- Domain registered via Namecheap
- VPS hosted on AWS
- Linux (Ubuntu)
- Nginx

## Tasks Performed

1. Updated A record to point to VPS public IP.
2. Configured CNAME for www subdomain.
3. Preserved existing MX records to prevent email disruption.
4. Verified DNS propagation using:
   - dig
   - nslookup
   - online DNS checkers
5. Monitored TTL propagation to minimize downtime.

## Validation

- Confirmed successful resolution via ping and curl.
- Verified website accessibility over HTTP.
- Confirmed email delivery remained uninterrupted.

## Outcome

Successful migration completed with no email downtime and minimal website disruption.
