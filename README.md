# Available .BOT One-Word Domains (12,006)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C006%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bot one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,006 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,006 domains · **Median ask:** $249.20 · **High-demand under $2,500:** 15

**Last updated:** 2026-08-11
**Canonical page:** `https://unique.domains/domains/tld/bot`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/bot?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./bot.csv">CSV</a> / <a href="./bot.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .BOT search](https://unique.domains/domains/tld/bot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .BOT search](https://unique.domains/domains/tld/bot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .BOT one-word domain catalog.

### Files

- `bot.csv`, public CSV extract (1,000 rows)
- `bot.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bot-oneword-domains/main/bot.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar       |
| ------------ | --------- | ----------- | ------------- | -------------- | ------ | ------ | --------------- |
| acne.bot     | available | $64.99      | $64.99        | medium         | low    | 4      | namesilo        |
| size.bot     | resell    | $7,528.68   | —             | high           | low    | 4      | EnCirca, Inc.   |
| ago.bot      | premium   | $125        | $125          | medium         | low    | 3      | name.com        |
| also.bot     | available | $64.99      | $64.99        | high           | low    | 4      | namesilo        |
| water.bot    | resell    | $650        | $650          | high           | medium | 5      | GoDaddy.com LLC |
| ale.bot      | premium   | $116        | $116          | medium         | low    | 3      | namesilo        |
| camo.bot     | available | $64.99      | $64.99        | high           | low    | 4      | namesilo        |
| unveil.bot   | resell    | $78.98      | —             | high           | low    | 6      | Dynadot, LLC    |
| apt.bot      | premium   | $125        | —             | high           | low    | 3      | name.com        |
| dull.bot     | available | $64.99      | $64.99        | medium         | low    | 4      | namesilo        |
| standard.bot | resell    | $135,370.58 | —             | high           | medium | 8      | Dynadot, LLC    |
| box.bot      | premium   | $3,125      | —             | medium         | high   | 3      | name.com        |
| gone.bot     | available | $78.98      | —             | high           | low    | 4      | namecheap       |
| bit.bot      | resell    | —           | —             | high           | medium | 3      | Porkbun LLC     |
| cod.bot      | premium   | $116        | $116          | high           | low    | 3      | namesilo        |
| heel.bot     | available | $64.99      | $64.99        | medium         | low    | 4      | namesilo        |
| fog.bot      | resell    | —           | —             | high           | low    | 3      | NameCheap, Inc  |
| dye.bot      | premium   | $116        | $116          | medium         | low    | 3      | namesilo        |
| lick.bot     | available | $64.99      | $64.99        | medium         | low    | 4      | namesilo        |
| hub.bot      | resell    | —           | —             | high           | medium | 3      | Dynadot, LLC    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,006 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 15 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=related_pricing)

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

This is a set of one-word and short-phrase .bot domain names, useful for AI agents, chatbots, and automation-branded projects. The majority are available outright rather than premium or resale listings, and pricing skews low: most names fall under $500, with only a small tail reaching into five figures. Demand signals are modest across the set, with a small subset showing stronger interest.

- 8,758 of 10,304 domains are available now
- Median ask ~$279; 8,832 priced under $500
- 851 Premium, 695 Resell — most are standard listings
- Only 13 domains rank in the top 15% for demand

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOT One-Word Domains*. Version 2026-08-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOT page](https://unique.domains/domains/tld/bot?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
