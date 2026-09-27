# SOC Analyst Labs


A curated study collection of ten intermediate cybersecurity projects for security operations and general analyst practice. Each project is packaged as a separate ZIP archive at the repository root; the original folder structure and included project files are retained inside each archive.


## Projects


| Project | Analyst focus | Archive |
| --- | --- | --- |
| SIEM Dashboard | Log ingestion, event correlation, and alert review | [`siem-dashboard.zip`](siem-dashboard.zip) |
| Security News Scraper | Cyber threat intelligence and CVE feeds | [`security-news-scraper.zip`](security-news-scraper.zip) |
| Secrets Scanner | Exposed-secret detection and triage | [`secrets-scanner.zip`](secrets-scanner.zip) |
| JA3/JA4 TLS Fingerprinting | TLS telemetry and network threat hunting | [`ja3-ja4-tls-fingerprinting.zip`](ja3-ja4-tls-fingerprinting.zip) |
| DLP Scanner | Data classification and exposure detection | [`dlp-scanner.zip`](dlp-scanner.zip) |
| SBOM Generator & Vulnerability Matcher | Software inventory and vulnerability triage | [`sbom-generator-vulnerability-matcher.zip`](sbom-generator-vulnerability-matcher.zip) |
| Docker Security Audit | Container configuration review | [`docker-security-audit.zip`](docker-security-audit.zip) |
| Credential Rotation Enforcer | Credential hygiene and compliance | [`credential-rotation-enforcer.zip`](credential-rotation-enforcer.zip) |
| API Security Scanner | API security assessment | [`api-security-scanner.zip`](api-security-scanner.zip) |
| Binary Analysis Tool | Binary examination and malware analysis fundamentals | [`binary-analysis-tool.zip`](binary-analysis-tool.zip) |


## Source and attribution


The selected project code and project documentation originate from [CarterPerez-dev/Cybersecurity-Projects](https://github.com/CarterPerez-dev/Cybersecurity-Projects), principally under `PROJECTS/intermediate/`. This is an independently assembled collection and is not a GitHub fork. The collection curator is `cyberingsecurity`; the upstream project code is not claimed as original work. See [`UPSTREAM.md`](UPSTREAM.md) for the project-by-project source map.


No changes to the upstream project code are claimed in this collection. Any future changes should be described with a date and clear summary in the relevant project folder.


## License


The source repository is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). The upstream root license is included here, and project-specific license files are retained inside the archives. See [`LICENSE`](LICENSE) and the notices inside each archive before copying or modifying a project.


## Safe use


Use these tools only with systems, files, and networks you own or are authorized to assess. Use sample data for demonstrations, and never commit real credentials or sensitive data.


## Investigation report


- [SIEM Brute Force and Lateral Movement](https://github.com/cyberingsecurity/siem-brute-force-lateral-movement-lab) — synthetic Docker SIEM case study with alert validation and MITRE ATT&CK mapping.
