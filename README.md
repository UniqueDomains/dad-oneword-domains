# Available .DAD One-Word Domains (12,753)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C753%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .dad one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,753 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,753 domains · **Median ask:** $75.86 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `dad.csv` — public CSV extract (1,000 rows)
- `dad.json` — public JSON extract (1,000 rows)
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

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| RedSox.dad       | available | $16.98    | —             | 72             | 60     | 7      | namecheap |
| farmers.dad      | premium   | $73.75    | —             | 54             | 59     | 7      | name.com  |
| shortcuts.dad    | available | $16.98    | —             | 48             | 41     | 10     | namecheap |
| cars.dad         | premium   | $623.75   | —             | 66             | 47     | 4      | name.com  |
| prompts.dad      | available | $16.98    | —             | 54             | 39     | 7      | namecheap |
| jobs.dad         | premium   | $1,248.75 | —             | 79             | 42     | 4      | name.com  |
| commonground.dad | available | $16.98    | —             | 74             | 28     | 13     | namecheap |
| coins.dad        | premium   | $311.25   | —             | 56             | 41     | 5      | name.com  |
| lostandfound.dad | available | $16.98    | —             | 64             | 19     | 14     | namecheap |
| Tools.dad        | premium   | $698.60   | $698.60       | 56             | 40     | 5      | namecheap |
| gobeyond.dad     | available | $16.98    | —             | 76             | 18     | 9      | namecheap |
| lets.dad         | premium   | $161.25   | —             | 77             | 39     | 4      | name.com  |
| techsupport.dad  | available | $16.98    | —             | 76             | 18     | 12     | namecheap |
| whynot.dad       | premium   | $161.25   | —             | 74             | 39     | 7      | name.com  |
| goviral.dad      | available | $16.98    | —             | 76             | 17     | 8      | namecheap |
| WiFi.dad         | premium   | $698.60   | $698.60       | 83             | 37     | 5      | namecheap |
| jetlag.dad       | available | $16.98    | —             | 72             | 17     | 7      | namecheap |
| tokens.dad       | premium   | $73.75    | —             | 51             | 36     | 6      | name.com  |
| Sundays.dad      | available | $16.98    | —             | 61             | 17     | 7      | namecheap |
| tickets.dad      | premium   | $623.75   | —             | 64             | 34     | 7      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,753 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

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

This set is entirely made up of one-word .dad domains, which creates a very specific naming profile. Some names are literal and family-centered, such as father.dad, while others are broader dictionary words like true.dad, only.dad, nutrient.dad, and guarantee.dad. That mix matters. Founders should favor words that stay clear, easy to say, and relevant to a family, parenting, creator, or novelty concept. Investors should focus on whether the word has obvious end-user relevance inside the .dad extension, because extension-word fit will shape resale interest more than the word alone. With a median ask of 75.86, price discipline is straightforward, but semantic fit is the main filter.

- Prioritize word and extension fit: father.dad is clearer than abstract terms.
- Median ask is 75.86, so weak-fit names are easier to pass on.
- Literal family terms may read faster than broad dictionary words.
- Check trademark risk before valuing brandability or resale appeal.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DAD One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DAD page](https://unique.domains/domains/tld/dad?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
