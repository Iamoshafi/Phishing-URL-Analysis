# Phishing Analysis Lab

A structured analysis of live phishing URLs sourced from OpenPhish, 
investigating domain infrastructure, hosting providers, and attack 
techniques using VirusTotal, WHOIS, and MXToolbox.

## Methodology
Each sample is analyzed across four layers:
1. URL structure (typosquatting, suspicious patterns)
2. Domain intelligence (WHOIS, registration date, legitimacy)
3. Hosting infrastructure (IP, ASN, hosting provider)
4. Threat intelligence (VirusTotal detection score)

All findings are mapped to MITRE ATT&CK techniques.

Note: Samples are sourced from OpenPhish's live URL feed rather than full email captures. Analysis covers URL structure, domain intelligence, and hosting infrastructure.

## Tools Used
- VirusTotal (virustotal.com)
- WHOIS (whois.domaintools.com)
- MXToolbox (mxtoolbox.com)
- OpenPhish (openphish.com)