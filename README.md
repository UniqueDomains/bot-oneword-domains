# Available .BOT One-Word Domains (8,947)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C947%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .bot one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,947 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,947 domains · **Median ask:** $302.24 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
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

- `bot.csv` — public CSV extract (1,000 rows)
- `bot.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/bot-oneword-domains/main/bot.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price  | renewal_price | attractiveness | demand | length | registrar     |
| ------------- | --------- | ---------- | ------------- | -------------- | ------ | ------ | ------------- |
| ladies.bot    | available | $78.98     | —             | 80             | 17     | 6      | namecheap     |
| getup.bot     | available | $78.98     | —             | 82             | 14     | 6      | namecheap     |
| dogsit.bot    | available | $78.98     | —             | 96             | 2      | 6      | namecheap     |
| playin.bot    | available | $78.98     | —             | 80             | 10     | 7      | namecheap     |
| pierogi.bot   | available | $78.98     | —             | 82             | 7      | 7      | namecheap     |
| dogsick.bot   | available | $78.98     | —             | 90             | 1      | 7      | namecheap     |
| creating.bot  | available | $78.98     | —             | 80             | 12     | 8      | namecheap     |
| lightup.bot   | available | $78.98     | —             | 82             | 15     | 8      | namecheap     |
| winners.bot   | available | $64.99     | $64.99        | 60             | 81     | 7      | namesilo      |
| agents.bot    | resell    | —          | —             | 56             | 50     | 6      | EnCirca, Inc. |
| cars.bot      | premium   | $1,250     | —             | 66             | 47     | 4      | name.com      |
| regions.bot   | available | $78.98     | —             | 64             | 59     | 7      | namecheap     |
| prompts.bot   | resell    | —          | —             | 54             | 39     | 7      | Dynadot, LLC  |
| robots.bot    | premium   | $6,250     | —             | 62             | 47     | 6      | name.com      |
| backyard.bot  | available | $78.98     | —             | 80             | 27     | 9      | namecheap     |
| Schneider.bot | resell    | —          | —             | 66             | 38     | 9      | Dynadot, LLC  |
| vector.bot    | premium   | $23,096.57 | —             | 82             | 38     | 6      | 1API GmbH     |
| CapeCod.bot   | available | $78.98     | —             | 78             | 22     | 8      | namecheap     |
| unit.bot      | resell    | —          | —             | 76             | 37     | 4      | Dynadot, LLC  |
| journey.bot   | premium   | $59,223.82 | —             | 72             | 34     | 7      | Dynadot, LLC  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 8,947 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/bot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/bot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .bot domains. It includes dictionary-style words, action-oriented terms, and broad consumer language such as Acup.bot, finals.bot, ladies.bot, forces.bot, getup.bot, and useit.bot. For founders, the main question is whether the word is clear, memorable, and specific enough to carry a product or agent brand. For investors, the key test is whether the word has broad commercial use and a realistic ask relative to resale uncertainty. The median ask across this set is 284.53, which makes price discipline important when judging stronger words against weaker fits.

- All domains in this selection use the .bot extension
- 8,954 one-word domains are included in this set
- Median ask across the selection is 284.53
- Favor clear words with broad use and low ambiguity

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .BOT One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .BOT page](https://unique.domains/domains/tld/bot?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_bot_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
