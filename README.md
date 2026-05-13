# Available .AUTO One-Word Domains (12,857)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C857%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .auto one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,857 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,857 domains · **Median ask:** $2,770.65 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/auto`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/auto?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./auto.csv">CSV</a> / <a href="./auto.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .AUTO search](https://unique.domains/domains/tld/auto?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .AUTO search](https://unique.domains/domains/tld/auto?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .AUTO one-word domain catalog.

### Files

- `auto.csv` — public CSV extract (1,000 rows)
- `auto.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/auto-oneword-domains/main/auto.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Trex.auto          | available | $2,950    | —             | 80             | 24     | 5      | namecheap |
| girls.auto         | available | $2,950    | —             | 83             | 23     | 5      | namecheap |
| Chanel.auto        | available | $2,950    | —             | 80             | 77     | 6      | namecheap |
| geton.auto         | available | $2,950    | —             | 82             | 10     | 6      | namecheap |
| matcha.auto        | available | $2,950    | —             | 86             | 39     | 6      | namecheap |
| QandA.auto         | available | $2,950    | —             | 80             | 10     | 7      | namecheap |
| makeit.auto        | available | $2,950    | —             | 82             | 22     | 7      | namecheap |
| winners.auto       | available | $1,999.99 | $2,199        | 60             | 81     | 7      | namesilo  |
| makers.auto        | available | $1,999.99 | $2,199        | 62             | 67     | 6      | namesilo  |
| travelers.auto     | available | $1,999.99 | $2,199        | 58             | 61     | 9      | namesilo  |
| regions.auto       | available | $2,950    | —             | 64             | 59     | 7      | namecheap |
| keepthechange.auto | available | $2,950    | —             | 46             | 59     | 15     | namecheap |
| skills.auto        | available | $2,950    | —             | 58             | 47     | 6      | namecheap |
| prompts.auto       | available | $1,999.99 | $2,199        | 54             | 39     | 7      | namesilo  |
| tokens.auto        | available | $1,999.99 | $2,199        | 51             | 36     | 6      | namesilo  |
| aliens.auto        | available | $1,999.99 | $2,199        | 56             | 35     | 6      | namesilo  |
| teams.auto         | available | $2,950    | —             | 62             | 32     | 5      | namecheap |
| William.auto       | available | $2,950    | —             | 74             | 31     | 7      | namecheap |
| maps.auto          | available | $2,950    | —             | 56             | 31     | 4      | namecheap |
| solutions.auto     | available | $2,950    | —             | 56             | 31     | 9      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,857 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/auto?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/auto?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .auto domains. The set spans broad dictionary terms, category words, and sharper brand-style terms such as tips.auto, homes.auto, finals.auto, and jewels.auto. Median asking price is 2,770.65, so price discipline matters when comparing options. For founders, the best choices are clear, memorable words that fit an automotive use case without forcing the meaning. For investors, quality depends on how naturally the word pairs with .auto, how wide the buyer pool may be, and whether the ask leaves room versus likely end-user demand. Be cautious with terms that may create trademark exposure, such as obvious brand references.

- One-word .auto domains only
- 12,856 domains; median ask 2,770.65
- Best fits pair naturally with the .auto ending
- Watch for trademark risk in branded terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .AUTO One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .AUTO page](https://unique.domains/domains/tld/auto?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_auto_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
