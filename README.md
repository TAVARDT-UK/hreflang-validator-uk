<p align="center">
  <a href="https://ag.tavardt.com/uk/">
    <img src="https://ag.tavardt.com/img/tavardt-banner.png" alt="TAVARDT" width="1024" />
  </a>
</p>

# Hreflang and International SEO Validator

[![Hreflang Validator](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/uk/hreflang-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audits alternate return tags, regional language targeting en-GB, and global x-default fallback architecture.

Developed and maintained by the international search architecture and web standards division at **TAVARDT**.

***

## Risk Vectors and Operational Impact in International SEO

Flawed hreflang tags precipitate severe search crawl budget dissipation and regional search visibility loss. When alternate links lack reciprocal returns or self-referencing definitions, search engines discard geographical targeting directives.

This technical failure directs British consumers to international page variations, depressing user engagement and transaction completion. Automated auditing maintains pristine cross-border technical integrity across multi-market digital properties.

***

## Core Technical Audit Capabilities

* **Self-Referencing Annotation Verification**: Confirms every audited URL includes a self-referencing alternate link, avoiding search engine indexing disqualification.
* **Global x-default Fallback Inspection**: Verifies mandatory x-default routing for international visitors outside targeted geographical regions.
* **ISO 639-1 and ISO 3166-1 Syntax Validation**: Validates two-letter language and country combinations against international standards to prevent malformed regional targeting.
* **Canonical Tag Consistency**: Identifies critical conflicts where canonical link headers or tags point away from declared alternate URLs.
* **Dual-Source Parsing**: Extracts hreflang annotations from both HTML head tags and HTTP Link response headers seamlessly.
* **International Health Score**: Computes an objective 0 to 100 compliance metric classifying platforms as COMPLIANT, WARNING, or CRITICAL.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external packages.

```bash
git clone https://github.com/TAVARDT-UK/hreflang-validator-uk.git
cd hreflang-validator-uk
python hreflang_validator.py https://company.co.uk
```

To output structured JSON for automated pipelines and quality audits:

```bash
python hreflang_validator.py https://company.co.uk -j
```

***

## Technical Frequently Asked Questions

### 1. What causes search engines to silently ignore hreflang annotations?
Missing reciprocal return tags and omitted self-referencing links cause crawlers to discard entire alternate tag clusters. This utility inspects tag symmetry and identifies syntax omissions before indexation degradation occurs.

### 2. Why is the x-default annotation essential for multi-regional websites?
The x-default tag provides an authoritative fallback destination for visitors arriving from unassigned geographical territories. Omitting this declaration forces search engines to guess appropriate routing, decreasing international conversion rates.

### 3. How does the validator detect conflicts between canonical and hreflang directives?
The script extracts both canonical declarations and alternate links to verify absolute target alignment. Any discrepancy triggers a critical alert and penalises the overall compliance score by 20 points.

### 4. Does the tool support HTTP Link response headers in addition to HTML tags?
The parser extracts annotations from both HTML head elements and raw HTTP Link headers. This dual capability allows auditing non-HTML assets such as PDF documents and dynamic API endpoints.

### 5. Which international standards govern the validation of language and region codes?
The validator enforces ISO 639-1 for two-letter language identifiers and ISO 3166-1 alpha-2 for regional country codes. Invalid or reversed combinations generate automated warnings and score deductions.

***

## International SEO and Global Architecture Advisory

For multi-market deployments and technical alignment with W3C Internationalisation Standards, consult **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Distributed under the MIT License. See the LICENSE file for complete terms.

***

© 2026 TAVARDT. All rights reserved.
