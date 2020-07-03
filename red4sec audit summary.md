# Red4Sec audit summary

- Audit length: 7 weeks. 
- Auditor homepage: https://red4sec.com

Red4Sec’s report was exhaustive, and covered the entirety of our project space, with the exception of our post-quantum cryptography, which was reviewed separately by x41 D-Sec. Below is a rundown of issues raised by Red4Sec by section of our network, as well as impact level.

During the analysis, whose report runs over 200 pages, a total of 67 vulnerabilities were detected. Many of these vulnerabilities did not pose any risk by themselves and therefore have been classified as informative.

All vulnerabilities were classified according to the impact level defined by CVSS (Common Vulnerability Scoring System): critical, high, medium, low and informative.

A summary of the issues per project area is described below.

## Blockchain

### QRL Node (Python)

Source: https://github.com/theQRL/QRL/

- **Critical:** 6 issues identified — All fixed by end of audit
- **High:** 3 issues identified — All fixed by end of audit
- **Medium:** 4 issues identified — 2 fixed by end of audit, outstanding fixes have now been applied (everything is fixed)
- **Low/Informative:** 21 issues or queries which have all been reviewed by the team, with changes made to the codebase where necessary.

### Qryptonight (C++)

- **Critical:** 1 issue identified — fixed by end of audit

### Qrllib (C++)

- **Informative:** 1 issue which was closed by the end of the audit.

## Public facing Infrastructure

### QRL Wallet (JS)

- **Critical:** 1 issue identified — fixed by end of audit
- **High:** 1 issue identified as informative by Red4Sec — the team rated it as High, however, and it was fixed by the end of the audit

### Block Explorer (JS)

- **Low/Informative:** 1 Low and 1 Informative level issue which were both closed by the end of the audit.

### theqrl.org (JS)

- **Medium:** 1 issue identified — fixed by the end of audit

## Backend & Team processes

### Infrastructure

Includes nodes, cloud services, mail services and any other service that QRL relies upon for development and other team processes.

- **Medium:** 5 issues identified — all fixed by end of audit.
- **Low/Informative:** 11 issues have been identified and all have been fixed.
