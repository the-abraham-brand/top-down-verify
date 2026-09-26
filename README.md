# Top-Down Verify

**By [Abraham](https://theabrahambrand.com)**

A Claude plugin that fact-checks any document before it goes out. Every claim, figure, date, name, quote, calculation and link is checked against trusted sources and against the document itself, and you get a clear verdict, the fixes, and a corrected version.

## Why it exists

AI makes writing fast. It also makes it easy to send out a statistic nobody checked, a figure that changed last year, a total that doesn't add up, or a quote nobody said. Top-Down Verify is the last step before *send* or *publish*.

## What's included

| Skill | How it runs | What it does |
|---|---|---|
| **top-down-verify** | Automatically, whenever you ask to fact-check, verify or source a document or claim | Claim extraction, risk rating, trusted-source verification, report format |
| **/top-down-verify:check** | You run it on a document (Word, PDF, slides, spreadsheet, web page or pasted text) | Verdict, priority fixes, claim-by-claim ledger, corrected version in the original format |
| **/top-down-verify:claim** | You run it on one statistic, statement or quote | True / Partly true / False / Outdated / Unverified, the original source, and a corrected sentence |

## How it checks

1. **Extracts every claim**: statistics, facts, dates, laws, names and titles, "first/only/largest" claims, quotes, calculations and links, plus leftovers like placeholders and tracked changes.
2. **Rates the risk**: headline figures and anything about health, law, money, safety or named people and companies are High risk and must be confirmed by two independent sources.
3. **Checks against trusted sources only**: each source must pass five tests: it produced the data or is an established publisher that verifies data and names its source (such as Statista or Reuters); its method is evident; it is independent of the claim; it is dated and current; and it fits the claim's geography, period and definition. Vendor blogs and statistics roundups are never cited.
4. **Checks the document against itself**: totals, percentages, growth rates, repeated figures, dates and weekdays, names, units and currencies.
5. **Reports back, answer first**: *Clear to send*, *Fix before sending*, or *Do not send yet*, with coverage stated honestly.

Every claim gets a status: Verified, Corroborated, Outdated, Mismatch, Unsupported, Unverified, Calculation error, Inconsistent, Author to confirm, Opinion/forecast, or Broken link.

## What it never does

- Cite a source it did not open, or attribute a figure to a source that doesn't contain it.
- Invent a number or a source to fill a gap. Unverifiable claims are reworded or marked `[needs source]`.
- Call an opinion or forecast "verified".

## Installation

In Claude Code:

```
/plugin marketplace add the-abraham-brand/top-down-verify
/plugin install top-down-verify@top-down-verify
```

In the Claude app, install it from the plugin directory once it's listed.

## Works well with

- [Top-Down Brief](https://github.com/the-abraham-brand/top-down-brief): answer-first, professional official communications.
- [Top-Down Startup Pitch Deck](https://github.com/the-abraham-brand/top-down-startup-pitch-deck): investor decks with research-backed, cited figures.

## Credits

Top-Down Verify is designed and maintained by Abraham ([theabrahambrand.com](https://theabrahambrand.com)).

## License

MIT © 2026 Abraham
