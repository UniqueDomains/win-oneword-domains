# Available .WIN One-Word Domains (11,453)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C453%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .win one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,453 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,453 domains

**Last updated:** 2026-04-26  
**Canonical page:** `https://unique.domains/domains/tld/win`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/win?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./win.csv">CSV</a> / <a href="./win.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WIN search](https://unique.domains/domains/tld/win?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WIN search](https://unique.domains/domains/tld/win?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WIN one-word domain catalog.

### Files

- `win.csv` — public CSV extract (1,000 rows)
- `win.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/win-oneword-domains/main/win.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| products.win      | available | $9.98     | —             | 60             | 23     | 8      | namecheap       |
| today.win         | resell    | —         | —             | 82             | 35     | 5      | Spaceship, Inc. |
| travelers.win     | premium   | $437.50   | —             | 58             | 61     | 9      | name.com        |
| resources.win     | available | $9.98     | —             | 58             | 21     | 9      | namecheap       |
| bros.win          | resell    | —         | —             | 58             | 19     | 4      | Porkbun         |
| RedSox.win        | premium   | $490      | $70           | 72             | 60     | 7      | namecheap       |
| ratings.win       | available | $9.98     | —             | 53             | 19     | 7      | namecheap       |
| fruits.win        | resell    | —         | —             | 74             | 17     | 6      | Dynadot Inc     |
| keepthechange.win | premium   | $437.50   | —             | 46             | 59     | 15     | name.com        |
| weddings.win      | available | $5.25     | $6.25         | 64             | 18     | 8      | namesilo        |
| Tools.win         | premium   | $490      | $70           | 56             | 40     | 5      | namecheap       |
| prints.win        | available | $9.98     | —             | 54             | 18     | 6      | namecheap       |
| homes.win         | premium   | $437.50   | —             | 86             | 34     | 5      | name.com        |
| makes.win         | available | $9.98     | —             | 66             | 17     | 5      | namecheap       |
| teams.win         | premium   | $437.50   | —             | 62             | 32     | 5      | name.com        |
| oaks.win          | available | $5.25     | $6.25         | 53             | 16     | 4      | namesilo        |
| solutions.win     | premium   | $437.50   | —             | 56             | 31     | 9      | name.com        |
| underwater.win    | available | $9.98     | —             | 64             | 15     | 11     | namecheap       |
| videos.win        | premium   | $437.50   | —             | 52             | 30     | 6      | name.com        |
| dates.win         | available | $9.98     | —             | 56             | 15     | 5      | namecheap       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 11,453 live domains                              |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/win?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/win?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=related_pricing)

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

> Unique Domains. *Available .WIN One-Word Domains*. Version 2026-04-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WIN page](https://unique.domains/domains/tld/win?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_win_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
