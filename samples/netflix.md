## Sample 3: Impersonating Netflix Payment gateway.

### URL Analysis
- URL: https://netflixpayment.creditcard/
- VirusTotal: 20/92 vendors flagged as malicious
- Domain: netflixpayment.creditcard
- Domain Registered: June 14, 2026 (1 day ago)
- WHOIS: OR
- Hosting IP: N/A - no public DNS record found
- Status: Has no public DNS record on MXtoolbox, but seems to have its details redacted on WHOIS

## Key Observations
- Domain registered just 1 day before analysis — freshly created phishing infrastructure
- Vanity TLD (.creditcard) chosen deliberately to imply payment context and create urgency
- WHOIS privacy protection used to hide attacker identity
- No DNS record suggests domain is either still being configured or was rapidly taken down after detection
- Netflix exclusively uses netflix.com — any other domain claiming to be Netflix is fraudulent

### MITRE ATT&CK Mapping
- T1566.002 — Spearphishing Link
- T1583.001 — Acquire Infrastructure: Domains
(purpose-built domain, registered 1 day prior)

### Analyst Notes
This sample represents the most common phishing infrastructure pattern — a purpose-built domain registered days before a campaign launches, using a vanity TLD to add credibility. 
The combination of a brand-new domain, WHOIS privacy protection, and a payment-themed URL targeting Netflix subscribers suggests a credential/payment harvesting campaign. 

Compared to Sample 1 (compromised legitimate domain) and Sample 2 (typosquatting, already taken down), this represents a third infrastructure pattern: freshly registered purpose-built domain with vanity TLD. Users are most at risk from this type because the URL looks payment-related and creates immediate urgency.