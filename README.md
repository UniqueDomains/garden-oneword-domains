# Available .GARDEN One-Word Domains (12,154)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C154%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .garden one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,154 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,154 domains · **Median ask:** $78.44 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/garden`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/garden?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./garden.csv">CSV</a> / <a href="./garden.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GARDEN search](https://unique.domains/domains/tld/garden?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GARDEN search](https://unique.domains/domains/tld/garden?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GARDEN one-word domain catalog.

### Files

- `garden.csv` — public CSV extract (1,000 rows)
- `garden.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/garden-oneword-domains/main/garden.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| geton.garden         | available | $43.98    | —             | 82             | 10     | 6      | namecheap        |
| getup.garden         | available | $43.98    | —             | 82             | 14     | 6      | namecheap        |
| playon.garden        | available | $43.98    | —             | 80             | 14     | 7      | namecheap        |
| QandA.garden         | available | $43.98    | —             | 80             | 10     | 7      | namecheap        |
| hangon.garden        | available | $43.98    | —             | 82             | 6      | 7      | namecheap        |
| makeit.garden        | available | $43.98    | —             | 82             | 22     | 7      | namecheap        |
| dogsick.garden       | available | $43.98    | —             | 90             | 1      | 7      | namecheap        |
| Snickers.garden      | available | $43.98    | —             | 80             | 10     | 8      | namecheap        |
| FabFour.garden       | available | $2.19     | $32.49        | 82             | 3      | 8      | namesilo         |
| headout.garden       | available | $43.98    | —             | 82             | 6      | 8      | namecheap        |
| keepthechange.garden | available | $43.98    | —             | 46             | 59     | 15     | namecheap        |
| vertical.garden      | resell    | —         | —             | 70             | 33     | 8      | Name.com, Inc.   |
| robots.garden        | premium   | $500      | —             | 62             | 47     | 6      | name.com         |
| neuroscience.garden  | available | $43.98    | —             | 80             | 37     | 12     | namecheap        |
| letsgo.garden        | resell    | —         | —             | 57             | 31     | 7      | GoDaddy.com, LLC |
| justin.garden        | premium   | $50       | —             | 58             | 38     | 7      | name.com         |
| heroes.garden        | available | $43.98    | —             | 68             | 29     | 6      | namecheap        |
| gogreen.garden       | resell    | —         | —             | 56             | 28     | 8      | Spaceship, Inc.  |
| aliens.garden        | premium   | $500      | —             | 56             | 35     | 6      | name.com         |
| Keith.garden         | available | $43.98    | —             | 66             | 25     | 5      | namecheap        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,154 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/garden?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/garden?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names in the .garden extension, which makes the set specific and easy to assess. The strongest candidates read cleanly as a full phrase with the extension, feel memorable at a glance, and avoid awkward joins between the word and .garden. In this selection, examples such as edamame.garden or dogsit.garden are concrete, while names like getup.garden or forces.garden are broader and may depend more on positioning. With a median ask of 78.44, price is often accessible, so the main decision is whether the word is distinctive, easy to say, and credible enough to carry a brand or resale thesis in a niche extension.

- Prefer words that read naturally with .garden
- Check whether the word is clear, memorable, and easy to say
- Use price discipline when several names feel equally strong
- Be careful with terms that may raise trademark concerns

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GARDEN One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GARDEN page](https://unique.domains/domains/tld/garden?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_garden_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
