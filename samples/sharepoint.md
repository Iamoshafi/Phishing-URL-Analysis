## Sample 1: Compromised Mexican Business Website Impersonating Microsoft SharePoint

### URL Analysis
- URL: https://grupocaceres.mx/file/sharepoint-3D7/
- VirusTotal: 23/92 vendors flagged as malicious (phishing)
- Domain registered: November 16, 2012
- WHOIS: Dan Cristian Caceres Garay, Mazatlan, Sinaloa, Mexico
- Hosting IP: 161.35.124.162 (DigitalOcean, LLC)

### Key Observations
- Domain is 14 years old — not a newly registered phishing domain
- Likely a compromised legitimate business website with phishing page planted in subdirectory (/file/sharepoint-3D7/)
- Hosted on DigitalOcean despite being a Mexican business,suggesting infrastructure was changed after compromise
- SharePoint impersonation targets corporate credentials

### MITRE ATT&CK Mapping
- T1566.002 — Spearphishing Link
- T1584.001 — Compromise Infrastructure: Domains

### My Notes
The age of this domain is the most significant finding. A 14-year-old domain with a real registered owner impersonating SharePoint strongly suggests website compromise rather than a purpose-built phishing domain. 
This makes it more dangerous than typical phishing infrastructure — the domain has established reputation and is less likely to be caught by filters that flag newly registered domains. Recommend reporting to DigitalOcean abuse team and notifying the domain owner.