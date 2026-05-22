# FUTURE_CS_01
## scanme.nmap.org Vulnerability Assessment Report

The passive vulnerability assessment of scanme.nmap.org identified 7 findings — none at Critical or High severity. The server is functional and has a basic firewall in place, but is running noticeably outdated software (Apache 2.4.7, OpenSSH 6.6.1p1) and is missing several HTTP security headers that are now considered baseline security hygiene.
All identified issues are remediable through Apache server configuration changes — no application code modifications are needed. Implementing the recommended HTTP security headers (CSP, X-Frame-Options, X-Content-Type-Options) and suppressing version information would eliminate all 6 active findings.
This assessment was conducted passively and non-intrusively as per the authorized scope. No exploitation was attempted. A follow-up active scan or penetration test (beyond the scope of this task) could reveal additional vulnerabilities in the underlying services.
