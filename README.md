# Available .AI One-Word Domains (54,119)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-10%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-54%2C119%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .ai one-word domains from Unique Domains.

> **Important:** this repository is a **public 10,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **54,119 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/ai`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_open_search"><b>Open live .AI search</b></a> ·
  <a href="https://unique.domains/domains/tld/ai?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_create_radar"><b>Create .AI Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/ai?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./ai.csv"><b>Download CSV</b></a> ·
  <a href="./ai.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## What this repository contains

This repository is the public dataset landing page for the exact search represented by `https://unique.domains/domains/tld/ai`.

- `ai.csv` — public CSV extract (10,000 rows)
- `ai.json` — public JSON extract (10,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

Use this repo to inspect a public sample, download machine-readable files, understand the exported columns, and cite the dataset.

Use the live page to keep the exact search context, review the full live catalog, create a Radar, and turn the search into a Project without rebuilding intent.

## Snapshot of the live catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

This chart is generated from the same preview payload used to render the README counts and summary.

## Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/ai-oneword-domains/main/ai.csv")
print(df.head())
```

## Sample rows

| domain               | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar   |
| -------------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | ----------- |
| cubicdecimetre.ai    | premium   | —              | —             | 54             | 72     | 15     | —           |
| needbased.ai         | premium   | —              | —             | 50             | 72     | 10     | —           |
| fusedmultiplyadd.ai  | premium   | —              | —             | 46             | 4      | 18     | —           |
| steamheaters.ai      | premium   | —              | —             | —              | 8      | 13     | —           |
| carbonise.ai         | premium   | —              | —             | 56             | 76     | 9      | —           |
| winbyanose.ai        | premium   | —              | —             | —              | 72     | 13     | —           |
| bookconcern.ai       | available | 92.98          | —             | 54             | 72     | 12     | namecheap   |
| olivebackedoriole.ai | premium   | —              | —             | 62             | 72     | 19     | —           |
| Europeananchovy.ai   | premium   | —              | —             | 54             | 72     | 16     | —           |
| sweetshrimp.ai       | premium   | —              | —             | —              | 72     | 12     | —           |
| advocategeneral.ai   | available | 92.98          | —             | 54             | 72     | 16     | namecheap   |
| Panglossian.ai       | premium   | —              | —             | 56             | 72     | 11     | —           |
| Covidnormal.ai       | premium   | —              | —             | 58             | 4      | 12     | —           |
| winthrough.ai        | premium   | —              | —             | —              | 72     | 11     | —           |
| pitchstone.ai        | premium   | —              | —             | 56             | 72     | 10     | —           |
| parasol.ai           | resell    | —              | —             | 80             | 88     | 7      | Dynadot Inc |
| frostymoon.ai        | premium   | —              | —             | 58             | 72     | 11     | —           |
| toweled.ai           | premium   | —              | —             | —              | 8      | 7      | —           |
| Castelgandolfo.ai    | premium   | —              | —             | 48             | 72     | 14     | —           |
| GreatBarford.ai      | premium   | —              | —             | 52             | 72     | 13     | —           |

## Field summary

- `Domain` — Fully qualified domain name.
- `Status` — Current acquisition state for the domain in the public extract.
- `PurchasePrice` — Visible purchase price when available.
- `RenewalPrice` — Visible renewal price when available.
- `Attractiveness` — Composite naming score used as a decision-support signal.
- `Demand` — Relative buyer-pressure score when available.
- `Length` — Character count without the TLD.
- `Registrar` — Registrar name when known.
- `Created` — Creation timestamp when known.
- `Expires` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## How to cite

Suggested citation:

> Unique Domains. *Available .AI One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## Related links

- [Live search](https://unique.domains/domains/tld/ai?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_ai_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
