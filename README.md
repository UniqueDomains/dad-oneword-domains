# Available .DAD One-Word Domains (14,223)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C223%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .dad one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,223 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,223 domains · **Median ask:** $87.17 · **High-demand under $2,500:** 26

**Last updated:** 2026-08-12
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

- `dad.csv`, public CSV extract (1,000 rows)
- `dad.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/dad-oneword-domains/main/dad.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| ague.dad | available | $12.98    | $16.98        | low            | low    | 4      | namecheap |
| act.dad  | premium   | $1,248.75 | —             | high           | low    | 3      | name.com  |
| ahuh.dad | available | $16.98    | —             | high           | low    | 4      | namecheap |
| arc.dad  | premium   | $623.75   | $623.75       | medium         | medium | 3      | name.com  |
| arum.dad | available | $12.98    | $16.98        | low            | low    | 4      | namecheap |
| bow.dad  | premium   | $161.25   | —             | high           | low    | 3      | name.com  |
| Audi.dad | available | $16.98    | —             | high           | high   | 4      | namecheap |
| buy.dad  | premium   | $1,248.75 | $1,248.75     | medium         | medium | 3      | name.com  |
| avon.dad | available | $16.98    | —             | high           | low    | 4      | namecheap |
| clv.dad  | premium   | $73.75    | $73.75        | low            | low    | 3      | name.com  |
| ecru.dad | available | $12.98    | $16.98        | low            | low    | 4      | namecheap |
| CNN.dad  | premium   | $73.75    | —             | high           | low    | 3      | name.com  |
| eyry.dad | available | $12.98    | $16.98        | low            | low    | 4      | namecheap |
| coy.dad  | premium   | $73.75    | $73.75        | medium         | low    | 3      | name.com  |
| flee.dad | available | $16.98    | —             | medium         | low    | 4      | namecheap |
| cue.dad  | premium   | $73.75    | —             | medium         | low    | 3      | name.com  |
| flew.dad | available | $16.98    | —             | high           | low    | 4      | namecheap |
| dip.dad  | premium   | $161.25   | $161.25       | high           | low    | 3      | name.com  |
| jolt.dad | available | $16.98    | —             | high           | low    | 4      | namecheap |
| don.dad  | premium   | $311.25   | —             | high           | low    | 3      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,223 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 26 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/dad?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/dad?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of one-word .dad domain names spans playful pop-culture references, personal and family-themed words, and short brandable terms. The median asking price across this selection is $109.99, giving a practical baseline for comparing individual listings. Because .dad carries a personal, approachable tone, these domains tend to suit consumer-facing brands, parenting content, and lifestyle projects rather than strictly technical products. When comparing names in this set, weigh asking price against renewal cost, spelling simplicity, and how easily the word reads as a standalone brand before committing to one.

- 12,754 one-word .dad domain names in this selection
- Median asking price: $109.99 per domain
- Mix of playful, personal, and brandable one-word names
- Compare price, spelling, and renewal before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DAD One-Word Domains*. Version 2026-08-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DAD page](https://unique.domains/domains/tld/dad?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dad_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
