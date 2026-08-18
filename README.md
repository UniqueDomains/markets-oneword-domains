# Available .MARKETS One-Word Domains (16,258)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C258%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .markets one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,258 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,258 domains · **Median ask:** $32.05 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-18
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

- `markets.csv`, public CSV extract (1,000 rows)
- `markets.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/markets-oneword-domains/main/markets.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| damn.markets    | available | $9.99     | $16.99        | high           | low    | 4      | name.com        |
| one.markets     | resell    | —         | —             | high           | medium | 3      | Spaceship, Inc. |
| flat.markets    | available | $9.99     | $16.99        | high           | low    | 4      | name.com        |
| tonic.markets   | available | $9.99     | $16.99        | high           | low    | 5      | name.com        |
| reverse.markets | available | $9.99     | $16.99        | high           | low    | 7      | name.com        |
| ago.markets     | available | $9.99     | $16.99        | medium         | low    | 3      | name.com        |
| fit.markets     | resell    | $9.99     | —             | high           | medium | 3      | Dynadot Inc     |
| bag.markets     | premium   | $500      | —             | high           | low    | 3      | name.com        |
| ala.markets     | available | $9.99     | —             | high           | low    | 3      | name.com        |
| per.markets     | resell    | $9.99     | —             | high           | low    | 3      | Dynadot Inc     |
| bid.markets     | premium   | $500      | —             | high           | low    | 3      | name.com        |
| ana.markets     | available | $9.99     | —             | high           | low    | 3      | name.com        |
| papa.markets    | resell    | $9.99     | —             | high           | low    | 4      | Dynadot Inc     |
| big.markets     | premium   | $500      | $500          | high           | medium | 3      | name.com        |
| bce.markets     | available | $9.99     | —             | medium         | low    | 3      | name.com        |
| fancy.markets   | resell    | $9.99     | —             | high           | low    | 5      | Dynadot Inc     |
| cup.markets     | premium   | $500      | —             | high           | low    | 3      | name.com        |
| bed.markets     | available | $9.99     | —             | high           | low    | 3      | name.com        |
| radar.markets   | resell    | $9.99     | —             | medium         | low    | 5      | Dynadot Inc     |
| dip.markets     | premium   | $500      | —             | high           | low    | 3      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,258 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/markets?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/markets?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=related_pricing)

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

This set includes one-word domain names on the .markets extension, spanning everyday verbs, foods, and plain-language phrases such as dogsit.markets and pierogi.markets. With 9,826 names and a median asking price near $47, the selection favors low-cost entry over premium four- and five-figure names. Because .markets is a newer, non-mainstream extension, buyers should weigh brandability and renewal cost alongside trademark and category fit before committing to a name.

- 9,826 one-word .markets domain names in this selection
- Median asking price near $47 — budget-friendly entry point
- Includes short, brandable names like makeit.markets, headout.markets
- Non-mainstream TLD: weigh renewal cost and category fit before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MARKETS One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MARKETS page](https://unique.domains/domains/tld/markets?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_markets_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
