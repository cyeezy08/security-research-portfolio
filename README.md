# leviathanx — Security Research & Responsible Disclosure

Independent security researcher. Responsible disclosure track record on identity infrastructure, cloud, and PHP core.

## Disclosure track record

| Target | Finding | Status |
|---|---|---|
| Keycloak (identity platform used by thousands of enterprises) | Unauthenticated account takeover via reset-credentials flow state replay (required action chain skip) | Reported to keycloak-security@googlegroups.com — acknowledged, in triage |
| AWS Trust & Safety | Exposed unauthenticated DICOM medical imaging (PACS) endpoints on Azure | Reported — remediated |
| PHP 8.4.26 (CVE-2026-109618/109619) | Validated working exploit chain, identified silent offsets bug in published exploit (Debian tag drift: bookworm vs trixie) | Analysis published privately |

## What I do

- **Vulnerability research** — patch-diff analysis, required-action/flow-logic bugs, memory corruption variant hunting
- **Responsible disclosure** — coordinated disclosure to vendor security teams, never public before fix
- **Pentest reports** — full manual penetration testing with working proofs of concept, CVSS scoring, plain-language remediation. 48-hour delivery.
- **Exploit validation** — testing public exploits against patched vs unpatched builds, identifying where published tools fail and why

## Methodology

Every finding is manually verified with a working proof of concept. No scanner dumps. No theoretical bugs. Each report includes:
- Root cause analysis
- Step-by-step reproduction
- Control test against patched version
- Detection guidance
- CVSS 3.1 scoring

## Tools & capabilities

- **Recon:** Shodan (EDU plan — 190k+ query credits), subdomain enumeration, asset discovery
- **Testing:** Burp Suite, sqlmap, custom exploit validation, OWASP methodology
- **AI-assisted analysis:** patch-diff reading, flow-logic auditing, required-action enforcement review
- **Reporting:** Professional pentest reports, responsible disclosure emails, GitHub Security Advisories

## Contact

- Email: leviathanxcloud@pm.me
- GitHub: cyeezy08

## Note on AI usage

I use AI tools to assist with lab setup, request automation, and drafting — consistent with the disclosure policies of the programs I report to. Every finding is manually validated against live instances. I can explain vulnerabilities, impact, and reproduction steps in my own words.
