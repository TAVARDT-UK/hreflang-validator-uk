# Hreflang and International SEO Validator

[![Hreflang Validator](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/uk/hreflang-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-United%20Kingdom-00C853.svg)](https://ag.tavardt.com/uk/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits alternate return tags, regional language targeting, and x-default annotations under W3C standards.

Developed and maintained by the international search engineering division of **[TAVARDT UK](https://ag.tavardt.com/uk/)**.

---

## International SEO and Hreflang Audit Capabilities

* **Return Tag Reciprocity Verification**: Confirms that every alternate language target contains a reciprocal link pointing back to the evaluated URL.
* **ISO 639-1 and ISO 3166-1 Code Validation**: Audits language and regional country codes (e.g., `en-GB`, `en-US`, `fr-FR`) against international standards.
* **x-default Fallback Inspection**: Verifies default target configuration for visitors outside designated regional locales.
* **Canonical Tag Consistency**: Detects conflicts between canonical URLs and self-referencing hreflang annotations.
* **International Architecture Score**: Technical score from 0 to 100 with prioritized remediation guidance.

---

## Installation and Execution

Requires Python 3.8 or higher with no external dependencies required.

```bash
git clone https://github.com/TAVARDT-UK/hreflang-validator-uk.git
cd hreflang-validator-uk
python hreflang_validator.py https://company.co.uk
```

To output results in structured JSON format:

```bash
python hreflang_validator.py https://company.co.uk --json
```

---

## Comprehensive Web Diagnostic

For full web verification and deep international site crawls:

* **[Official Hreflang Checker Tool](https://tools.tavardt.com/uk/hreflang-checker/)**
* **[TAVARDT UK Enterprise Portal](https://ag.tavardt.com/uk/)**

---

## International SEO and Global Search Advisory

For enterprise international architectures aligning with W3C Standards and UK Digital Architecture, contact the specialists at **[TAVARDT UK](https://ag.tavardt.com/uk/contact/)**.
