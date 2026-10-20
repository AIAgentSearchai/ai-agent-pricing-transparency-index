# AI Agent Pricing Transparency Index, October 2026: Totals by Category

Publisher: AIAgentSearch.ai (Agentic Solutions LLC)
Author: AIAgentSearch.ai Editorial Team
Data collected: October 20, 2026
Edition: October 2026 (first edition; the index is re-read monthly on the same companies)
Page: https://aiagentsearch.ai/ai-agent-pricing-transparency-index.html
License: Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

## What this file set contains

| File | What it is |
|---|---|
| `Data_Study_01_Public_Totals_by_Category_2026-10-20.csv` | One row per category (20 rows) plus an "All" row: counts of companies read and of each measure below |
| `LICENSE` | The CC BY 4.0 license notice for this file set |
| `README.md` | This codebook |

## Method

**Question.** How many of the AI agent startups we track show a price to a buyer who has not yet spoken to sales?

**Sample.** 106 early-stage AI agent companies: every company in the AIAgentSearch.ai candidate pool (our working list of AI agent companies sourced for coverage, compiled August to September 2026) except those our editors had already rejected as outside our 20 categories or not agent products. The pool was sourced mainly from startup accelerator rosters, funding coverage and category round-ups, so it leans toward early-stage companies. It is not a random sample of the AI agent market. Results describe the startups we track, not AI agent companies as a whole.

**Collection.** On October 20, 2026 we located each company's official site, then read its pricing page, or its homepage where no pricing page exists, and in a few cases its documentation or its own blog where those were the only pages that stated a price. Pages were read with an AI-assisted page reader, and every extracted value was recorded with the URL it came from. Nothing was estimated or filled in.

**Readable companies.** 88 of the 106 could be read and still sell the product we sampled, across 19 of our 20 categories. Of the 18 not counted: 6 had changed product so far that the sampled product is no longer sold, 1 had been acquired and replaced its pricing page with an acquisition notice, and 11 could not be read (pages that loaded only scripts, redirects to another domain, a site that blocks automated reading, fetch errors, and 2 companies whose official site could not be identified with confidence). None of the 18 is counted as "no price". The Data Analysis and BI category has 0 readable companies this month.

## Codebook: `Data_Study_01_Public_Totals_by_Category_2026-10-20.csv`

Every count column counts companies among the `read_n` readable companies in that row. A company is counted once per column.

| Column | Type | Definition |
|---|---|---|
| `category` | text | AIAgentSearch.ai category, or `All` for the total row |
| `sampled_n` | integer | Companies sampled in the category (all statuses) |
| `read_n` | integer | Companies readable on October 20, 2026 (the denominator for every other column) |
| `pricing_page_Y` | integer | Has a page or homepage section labelled pricing or plans |
| `public_price_Y` | integer | At least one paid figure in a currency appears on a page we read. A free plan alone does not count |
| `quote_only_Y` | integer | At least one listed plan shows no price and is reached through sales, a demo, a call or a custom quote. A company with no price at all and a sales or demo route counts here |
| `enterprise_price_Y` | integer | A number is shown for the enterprise or top plan |
| `free_tier_or_trial_Y` | integer | Offers a free tier (a plan labelled free with no time limit), a free trial (a time-limited or credit-limited free start), or both. Paid trials are not counted |
| `soc2_named` | integer | SOC 2 is stated as held on a page we read. Statements marked "in progress" or "readiness" are not counted |
| `iso27001_named` | integer | ISO 27001 is stated as held on a page we read. Statements marked "in progress" are not counted |

Totals in the `All` row: read 88; pricing page 48; publish a price 37; quote-only plan 79; enterprise price 1; free tier or trial 36; SOC 2 named 35; ISO 27001 named 4.

**Reading small rows.** Eleven categories have fewer than five readable companies. A percentage on two or three companies would mislead; the published page groups them. Certification counts are a floor, not a census, because we read pricing pages and homepages, not every page on each site.

## Company-level data

Company-level data is withheld to avoid singling out individual companies. A public row reading "no price published" would name a company for a choice many companies make, on a single reading date. This file set publishes totals only. The chart is published on the study page, free to reuse with its credit line.

## How to cite

**APA (7th edition)**
AIAgentSearch.ai Editorial Team. (2026, October 20). *Most AI Agent Startups We Track Do Not Publish a Price*. AIAgentSearch.ai. https://aiagentsearch.ai/ai-agent-pricing-transparency-index.html

**MLA (9th edition)**
AIAgentSearch.ai Editorial Team. "Most AI Agent Startups We Track Do Not Publish a Price." *AIAgentSearch.ai*, 20 Oct. 2026, aiagentsearch.ai/ai-agent-pricing-transparency-index.html.

**Citing the data files (APA 7, data set)**
AIAgentSearch.ai Editorial Team. (2026). *AI Agent Pricing Transparency Index: Totals by category, October 2026* [Data set]. AIAgentSearch.ai. https://aiagentsearch.ai/ai-agent-pricing-transparency-index.html

Under CC BY 4.0 you may share and adapt these files for any purpose, including commercially, if you credit "AIAgentSearch.ai, AI Agent Pricing Transparency Index, October 2026" with a link to the page above and say whether you made changes.

## Independence

AIAgentSearch.ai takes no advertising, affiliate fees or sponsored content. No company in the study was told it was being studied or asked to review its data. Companies that buy a listing on AIAgentSearch.ai are treated the same as every other company in the data.
