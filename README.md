# Available .MARKETS One-Word Domains (9,751)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C751%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .markets one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,751 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,751 domains · **Median ask:** $48.36 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
**Canonical page:** `https://unique.domains/domains/tld/markets`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/markets?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./markets.csv">CSV</a> / <a href="./markets.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MARKETS search](https://unique.domains/domains/tld/markets?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MARKETS search](https://unique.domains/domains/tld/markets?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MARKETS one-word domain catalog.

### Files

- `markets.csv` — public CSV extract (1,000 rows)
- `markets.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/markets-oneword-domains/main/markets.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| Trex.markets     | available | $26.98    | —             | 80             | 24     | 5      | namecheap         |
| Fanta.markets    | available | $26.98    | —             | 88             | 17     | 5      | namecheap         |
| jewels.markets   | available | $9.99     | —             | 80             | 15     | 6      | name.com          |
| carrie.markets   | available | $9.99     | —             | 82             | 11     | 6      | name.com          |
| matcha.markets   | available | $9.99     | —             | 86             | 39     | 6      | name.com          |
| sweets.markets   | available | $9.99     | —             | 90             | 18     | 6      | name.com          |
| useit.markets    | available | $9.99     | —             | 94             | 7      | 6      | name.com          |
| Phil.markets     | available | $26.98    | —             | 78             | 41     | 4      | namecheap         |
| whatnot.markets  | resell    | —         | —             | 58             | 33     | 8      | Spaceship, Inc.   |
| Books.markets    | premium   | $92.40    | $92.40        | 52             | 49     | 5      | namecheap         |
| baby.markets     | resell    | —         | —             | 78             | 31     | 4      | Sav.com, LLC - 30 |
| robots.markets   | premium   | $1,250    | —             | 62             | 47     | 6      | name.com          |
| dave.markets     | available | $9.99     | —             | 76             | 38     | 4      | name.com          |
| opinions.markets | resell    | —         | —             | 62             | 11     | 8      | Porkbun LLC       |
| ideas.markets    | premium   | $250      | —             | 62             | 37     | 5      | name.com          |
| Greg.markets     | available | $26.98    | —             | 66             | 35     | 4      | namecheap         |
| howto.markets    | premium   | $82.50    | —             | 76             | 35     | 6      | name.com          |
| theone.markets   | available | $9.99     | —             | 74             | 32     | 7      | name.com          |
| partners.markets | premium   | $250      | —             | 61             | 32     | 8      | name.com          |
| hashtag.markets  | available | $9.99     | —             | 82             | 30     | 7      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,751 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/markets?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/markets?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .markets domains. The set spans personal names, generic dictionary terms, acronyms, and more unusual words, with examples such as Liam.markets, feet.markets, finals.markets, and hahaha.markets. That range matters. Generic words can be clearer and easier to position, while invented or playful terms may be more distinctive but less intuitive. Personal names and well-known brand matches need extra caution. When comparing these domains, focus on whether the word fits a market-facing use case, whether it is easy to say and remember, and whether the asking price is justified by the term’s clarity and risk profile.

- Median ask across this set is 48.36
- Generic terms usually read clearer than playful words
- Personal names need stricter trademark review
- Match the word to a credible market-facing use

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MARKETS One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MARKETS page](https://unique.domains/domains/tld/markets?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
