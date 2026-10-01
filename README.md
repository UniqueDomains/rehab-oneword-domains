# Available .REHAB One-Word Domains (31,648)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-31%2C648%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .rehab one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **31,648 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 31,648 domains · **Median ask:** $40.94 · **High-demand under $2,500:** 5

**Last updated:** 2026-10-01
**Canonical page:** `https://unique.domains/domains/tld/rehab`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/rehab?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./rehab.csv">CSV</a> / <a href="./rehab.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REHAB search](https://unique.domains/domains/tld/rehab?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REHAB search](https://unique.domains/domains/tld/rehab?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REHAB one-word domain catalog.

### Files

- `rehab.csv`, public CSV extract (1,000 rows)
- `rehab.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/rehab-oneword-domains/main/rehab.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| aes.rehab    | available | $36.99    | $36.99        | high           | low    | 3      | namesilo         |
| brands.rehab | resell    | —         | —             | high           | low    | 6      | GoDaddy.com, LLC |
| hot.rehab    | premium   | $128.70   | $128.70       | high           | medium | 3      | namecheap        |
| ahn.rehab    | available | $8.24     | $30.18        | medium         | low    | 3      | dynadot          |
| remote.rehab | resell    | —         | —             | high           | medium | 6      | Sav.com, LLC - 7 |
| isp.rehab    | premium   | $72.60    | $72.60        | high           | low    | 3      | dynadot          |
| ane.rehab    | available | $14.99    | $52.99        | high           | low    | 3      | name.com         |
| area.rehab   | premium   | $128.70   | $128.70       | high           | low    | 4      | namecheap        |
| aum.rehab    | available | $38.48    | $47.48        | high           | low    | 3      | namecheap        |
| cure.rehab   | premium   | $260      | $260          | high           | low    | 4      | namecheap        |
| bap.rehab    | available | $38.48    | $47.48        | high           | low    | 3      | namecheap        |
| male.rehab   | premium   | $260      | $260          | high           | low    | 4      | namecheap        |
| bel.rehab    | available | $36.99    | $36.99        | high           | low    | 3      | namesilo         |
| shoe.rehab   | premium   | $250      | —             | high           | low    | 4      | name.com         |
| cfo.rehab    | available | $36.99    | $36.99        | high           | low    | 3      | namesilo         |
| town.rehab   | premium   | $85.80    | $85.80        | high           | low    | 4      | namecheap        |
| clx.rehab    | available | $14.99    | $52.99        | medium         | low    | 3      | name.com         |
| audio.rehab  | premium   | $207.20   | $207.20       | high           | low    | 5      | spaceship        |
| eeg.rehab    | available | $29.18    | $29.18        | high           | low    | 3      | spaceship        |
| farms.rehab  | premium   | $85.80    | $85.80        | medium         | low    | 5      | namecheap        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 31,648 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 5 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/rehab?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/rehab?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers 12,671 one-word .REHAB domain names, including short, memorable terms such as dogstail, matcha, getup, edamame, and keepfit. Pricing runs low, with a median ask near $36.47, making it easy to compare options and shortlist names for wellness, recovery, and health-focused brands. Because the .REHAB extension is niche, availability and renewal costs vary by registrar, so it pays to verify each domain before committing.

- 12,671 one-word .REHAB domain names in this selection
- Median ask near $36.47 across this list
- Includes short, brandable terms like matcha, getup, and keepfit
- Niche wellness TLD — verify renewal pricing before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REHAB One-Word Domains*. Version 2026-10-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REHAB page](https://unique.domains/domains/tld/rehab?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_rehab_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
