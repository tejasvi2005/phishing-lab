# phishing-lab
Phishing Email Investigation &amp; Incident Response Lab - Email analysis, threat intelligence tools, incident reporting.

# Phishing Email Investigation & Incident Response Lab

## Overview
A hands-on cybersecurity project demonstrating phishing email analysis and incident response workflow used by Security Operations Center (SOC) analysts.

## Project Goals
- Analyze phishing emails and identify red flags
- Use threat intelligence tools for verification
- Write professional SOC-style incident reports
- Develop skills for entry-level SOC Analyst roles

## What's Included

### Samples/
- phishing_sample_001.txt - PayPal credential harvesting phishing
- phishing_sample_002.txt - Office 365 password renewal phishing
- suspicious_invoice.zip - Malicious attachment example

### Investigations/
- phishing_sample_001_analysis.txt - Detailed analysis of first email
- phishing_sample_002_analysis.txt - Detailed analysis of second email
- cyberchef_analysis.txt - String decoding documentation
- attachment_analysis.txt - File hash analysis

### Reports/
- phishing_sample_001_report.txt - Professional incident report
- phishing_sample_002_report.txt - Professional incident report
- PHISH-COMPREHENSIVE-REPORT.txt - Complete analysis report
- PROJECT-SUMMARY.txt - Project completion documentation

## Tools Used

- **VirusTotal** - Multi-engine phishing/malware detection
- **WHOIS** - Domain registration and registrant lookup
- **AbuseIPDB** - IP reputation scoring
- **CyberChef** - String encoding/decoding
- **PowerShell** - File hash calculation (SHA256)

## Skills Demonstrated

✓ Email header analysis and sender verification
✓ Typosquatting and domain spoofing detection
✓ URL and domain reputation checking
✓ Malicious IP identification
✓ File hash analysis and verification
✓ String decoding (Base64)
✓ Red flag identification and documentation
✓ Professional incident report writing
✓ Threat intelligence gathering and correlation
✓ Incident response recommendations

## Red Flags Identified

- Sender domain spoofing (fake PayPal/Microsoft domains)
- Urgency language ("IMMEDIATE", "24 HOURS", "URGENT")
- Threat language ("account deleted", "restricted access")
- Generic greetings (mass campaign targeting)
- Suspicious URLs (typosquatting, new domains)
- Privacy-protected domain registration
- Failed email authentication (SPF/DKIM/DMARC)
- Malicious IP addresses

## Incident Report Structure

Each report includes:
- Email metadata (From, To, Subject, Date)
- Red flag analysis
- Technical findings (VirusTotal, WHOIS, IP checks)
- Indicators of Compromise (IOCs)
- Threat assessment and confidence level
- Recommended actions (immediate, short-term, long-term)

## How to Use This Lab

1. Review the phishing email samples
2. Read the corresponding analysis files
3. Examine the incident reports for professional format
4. Use this as a template for analyzing real phishing emails
5. Refer to tools and methodology for your own investigations

## Learning Outcomes

After completing this lab, you can:
- Identify phishing emails reliably
- Perform technical email analysis
- Use threat intelligence tools effectively
- Write professional SOC incident reports
- Recommend security actions based on evidence
- Document investigation process

## Next Steps

To advance this project:
- Analyze 10+ additional phishing emails
- Deep dive into email header forensics (SPF/DKIM/DMARC)
- Learn Wireshark for packet capture analysis
- Build Python automation for URL checking
- Study real-world attack scenarios (BEC, CEO Fraud)

## Contact

Created: September 27, 2026
For questions or collaboration, contact [Your Name]

---

**Portfolio Project for SOC Analyst Role**
