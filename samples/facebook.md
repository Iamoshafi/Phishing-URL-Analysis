## Sample 2: Typosquatting Domain Impersonating Facebook

### URL Analysis
- URL: https://faecbook.vn/aigapbannayodaulienhecohauta?a
- VirusTotal: 21/92 vendors flagged as malicious
  (17 specifically categorized as phishing)
- Domain: faecbook.vn
- WHOIS: Invalid domain — no public DNS record found
- Status: Domain appears to have been taken down

### Key Observations
- Classic typosquatting — "faecbook" vs "facebook", designed to catch inattentive users
- Vietnamese TLD (.vn) has no connection to Facebook, which operates exclusively on facebook.com
- Long randomized query string likely a victim tracking parameter
- Domain already suspended/taken down at time of analysis but VirusTotal retains historical detection from when it was active
- Rapid takedown suggests it was reported quickly after going live

### MITRE ATT&CK Mapping
- T1566.002 — Spearphishing Link
- T1583.001 — Acquire Infrastructure: Domains (purpose-built phishing domain via typosquatting)

### My Notes
Unlike Sample 1 which used a compromised legitimate domain, this is a purpose-built phishing domain — registered specifically to impersonate Facebook. The contrast between the two samples illustrates two distinct attacker infrastructure strategies:
1. Compromising existing legitimate domains (harder to detect, 
   better reputation)
2. Registering lookalike domains (faster to set up, easier to 
   detect and take down)

The rapid takedown of this domain demonstrates effective 
threat intelligence sharing but the Indicator of compromise (IOC) should remain blocklisted since domain resurrection is common.