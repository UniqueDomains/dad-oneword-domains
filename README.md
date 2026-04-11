# Available .DAD One-Word Domains (9,777)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C777%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C777%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .dad one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,777 rows · **Live catalog:** 9,777 domains

**Last updated:** 2026-04-11  
**Canonical page:** `https://unique.domains/domains/tld/dad`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/dad?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./dad.csv">CSV</a> / <a href="./dad.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DAD search](https://unique.domains/domains/tld/dad?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DAD search](https://unique.domains/domains/tld/dad?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DAD one-word domain catalog.

### Files

- `dad.csv` — public CSV extract (9,777 rows)
- `dad.json` — public JSON extract (9,777 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/dad-oneword-domains/main/dad.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                   |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------- |
| converse.dad   | available | $16.98    | —             | 64             | 73     | 8      | namecheap                   |
| our.dad        | resell    | —         | —             | —              | 42     | 3      | Squarespace Domains II LLC. |
| easy.dad       | premium   | $623.75   | $623.75       | 128            | 68     | 4      | name.com                    |
| nationwide.dad | available | $16.98    | —             | 76             | 66     | 10     | namecheap                   |
| bagh.dad       | resell    | —         | —             | 60             | 13     | 7      | Spaceship, Inc.             |
| power.dad      | premium   | $648.70   | $648.70       | 98             | 62     | 5      | namecheap                   |
| ethereal.dad   | available | $16.98    | —             | 88             | 32     | 8      | namecheap                   |
| seventeen.dad  | premium   | $36.25    | $36.25        | 84             | 62     | 9      | name.com                    |
| adept.dad      | available | $16.98    | —             | 92             | 27     | 5      | namecheap                   |
| enterprise.dad | premium   | $648.70   | $648.70       | 68             | 61     | 10     | namecheap                   |
| curative.dad   | available | $16.98    | —             | 92             | 27     | 8      | namecheap                   |
| free.dad       | premium   | $623.75   | $623.75       | 88             | 59     | 4      | name.com                    |
| remedial.dad   | available | $16.98    | —             | 86             | 24     | 8      | namecheap                   |
| cloud.dad      | premium   | $1,298.70 | $1,298.70     | 70             | 59     | 5      | namecheap                   |
| critical.dad   | available | $16.98    | —             | 82             | 24     | 8      | namecheap                   |
| ace.dad        | premium   | $623.75   | $623.75       | 88             | 57     | 3      | name.com                    |
| abundant.dad   | available | $16.98    | —             | 80             | 21     | 8      | namecheap                   |
| data.dad       | premium   | $648.70   | $648.70       | 70             | 56     | 4      | namecheap                   |
| sincere.dad    | available | $16.98    | —             | 72             | 21     | 7      | namecheap                   |
| live.dad       | premium   | $623.75   | $623.75       | 108            | 55     | 4      | name.com                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,777-row public sample | 9,777 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/dad?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/dad?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DAD One-Word Domains*. Version 2026-04-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DAD page](https://unique.domains/domains/tld/dad?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
