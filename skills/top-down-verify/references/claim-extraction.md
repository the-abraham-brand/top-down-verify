# Claim extraction and risk

## What counts as a claim

Extract anything a reader could reasonably take as a statement of fact, plus anything that could embarrass the author if wrong.

| Type | Examples | How it is checked |
|---|---|---|
| **Statistic** | "63% of SMEs…", "the market will reach $4B by 2030" | Trusted external source |
| **Fact about the world** | dates, events, laws, deadlines, prices, product features, locations | Trusted external source |
| **Named person or organisation** | job titles, ownership, funding, awards, partnerships, customer names | Official source (company site, filing, registry, reputable news) |
| **Comparative or superlative** | "first", "only", "largest", "fastest", "leading", "#1", "award-winning" | Needs direct evidence; flag if unprovable |
| **Quote or attribution** | "As Jane Doe said…", "according to the WHO…" | Find the original statement and context |
| **Health, legal, financial or safety statement** | dosage, eligibility, tax rules, returns, compliance claims | Authoritative primary source; always High risk |
| **Calculation** | totals, percentages, growth, averages, conversions, ratios | Recompute from the document's own inputs |
| **Author's own data** | revenue, users, costs, plans, internal results | Internal consistency; author confirms |
| **Forward-looking statement** | forecasts, targets, plans | Label as forecast or plan; check any external basis |
| **Opinion** | "the best approach", "we believe" | Label as opinion; no verification status |
| **Link or reference** | URLs, footnotes, cited reports | Opens, is the right page, supports the sentence |

## Internal consistency checks

Run these on every document, whatever its subject:

- The same figure appears identically everywhere (headline, body, tables, charts, appendix).
- Totals equal the sum of their parts; percentages of a whole add to about 100%.
- Growth rates, averages and ratios recompute correctly from the stated inputs.
- Dates are valid, weekdays match dates, sequences are in order, deadlines are in the future where implied.
- Currency, units and number formats are consistent, and conversions state a rate and date.
- Names of people, companies and products are spelled the same way throughout.
- Timeframes agree ("last quarter" vs a stated date range).
- No leftovers: placeholders, template text, comments, tracked changes, another client's name.

## Risk levels

**High**: always verify, and corroborate with a second independent source.
- The claim is in the title, headline, summary, or a slide or section heading.
- The document's conclusion or recommendation depends on it.
- It concerns health, safety, law, regulation, tax, or financial returns.
- It is about a named person or company in a way that affects their reputation.
- It is a superlative ("first", "only", "largest") or a quote.
- The audience is investors, regulators, the press, or the public.

**Medium**: always verify.
- Supporting statistics and facts in the body.
- Competitor facts and prices.
- Dates and deadlines that readers may act on.

**Low**: verify as coverage allows; report coverage honestly.
- Background context the reader already accepts.
- Rounded, widely known facts where a small error would not change meaning.

## Extraction output

Number every claim in order of appearance, and record: location (page, section, slide or paragraph), the exact text, its type, and its risk level. Use this list as the backbone of the ledger.
