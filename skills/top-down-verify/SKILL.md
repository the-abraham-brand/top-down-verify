---
name: top-down-verify
description: Check every claim, figure, date, name, quote and link in a document before it goes out, against trusted sources and against the document itself, and return a verdict, a claim-by-claim ledger, and corrected wording. Use this whenever the user asks to fact-check, verify, validate, source, "check the numbers", "is this accurate", "can I publish this", or wants a report, proposal, article, blog post, press release, website copy, marketing material, investor update, board paper, presentation or email checked before sending or publishing, even if they don't say "fact-check". Also use it when the user pastes a single statistic or statement and asks whether it is true or where it comes from. Do not use it for proofreading grammar only, or for checking code.
---

# Top-Down Verify

A single wrong number, outdated fact or unsourced claim can cost a sale, a funding round or a reputation. This skill checks a document the way a careful editor and a research analyst would together: every claim is extracted, weighed by risk, checked against trusted sources and against the rest of the document, and reported back with a clear verdict and fixes.

It never makes up a source and never "verifies" anything it has not actually read.

## Modes

- **Document check**: a whole document (file, pasted text, web page) to audit before sending or publishing.
- **Claim check**: one statement, statistic or quote to verify or trace to its origin.

## Step 1: Understand the document

Establish, from the document and the request:

- **Audience and stakes**: who will read it and what happens if it is wrong (investors, customers, regulators, the public, internal team). Stakes set how strict to be.
- **Subject, geography and date**: what the document is about, where, and as of when. A claim can be true in one country or year and false in another.
- **Author's own data**: which figures belong to the author's organisation (sales, costs, users, plans). These are checked for internal consistency and labelled for the author to confirm, not researched externally.

## Step 2: Extract the claims

Read `references/claim-extraction.md`. Pull out every checkable item:

- External facts: statistics, market figures, dates, events, laws and regulations, titles and roles of named people, company facts, scientific or health statements, prices, rankings, "first", "largest", "only", "leading".
- Quotes and attributions.
- Calculations: totals, percentages, growth rates, conversions, averages.
- Internal consistency: the same figure stated differently in two places, dates and weekdays that don't match, names spelled two ways, totals that don't add up, units or currencies that switch.
- Links and references: broken, wrong, or pointing to a page that does not say what the document claims.
- Leftovers: placeholders ([TBD], XX, lorem ipsum), tracked-change remnants, comments, wrong recipient names.

Give each claim a **risk level** (High, Medium, Low) using the rules in the reference file. Headline figures and claims about health, safety, law, money, or named people and companies are always High.

## Step 3: Verify

Read `references/sources-and-verification.md`. In short:

- **Plan from the subject.** For each claim, identify who produces authoritative data on it for this topic and geography. There is no fixed source list; choose the right sources per document.
- **Use only trusted sources.** Each source must pass the trust test: it produced the data or is an established publisher that verifies data and names its underlying source (such as Statista or Reuters); its method is evident; it is independent of the claim; it is dated and current; and it fits the claim's geography, segment, period and definition.
- **Open and match.** Open the page, find the figure, match number, unit, geography, period and definition exactly, and trace it to where the data originated.
- **Corroborate High-risk claims** with a second independent trusted source.
- **Recompute every calculation** and cross-check every repeated figure within the document.
- **Check every link** loads and supports the sentence it is attached to.

Verify every High and Medium claim. For long documents with many Low claims, verify as many as practical and state the coverage honestly (e.g. "42 of 57 claims checked; all High and Medium claims checked").

## Step 4: Report

Follow `references/report-format.md`. Deliver:

1. **Verdict**: *Clear to send*, *Fix before sending*, or *Do not send yet*, with the main reason and the coverage figure.
2. **Priority fixes**: the issues that matter, most serious first, each with the exact problem, the evidence, and replacement wording.
3. **Claim ledger**: every claim with its status, source, date and link.
4. **Corrected version**: the document with fixes applied, in the same format as the original where possible (for Word files, prefer tracked changes or comments so the author sees each edit). Mark any wording you changed to match a source.
5. **For the author to confirm**: their own figures, and any claim that could not be verified, marked `[needs source]`.

## Rules that do not bend

- Never cite a source you did not open, and never attribute a figure to a source that does not contain it.
- Never "fix" an unverifiable claim by inventing a plausible number or a source. Reword it, remove the figure, or mark it `[needs source]`.
- Quote sources exactly; paraphrase only to shorten, never to change meaning.
- Opinions, predictions and plans are labelled as such, not "verified".
- Claims that could damage a named person's or company's reputation, and statements on health, law or safety, are flagged for human review even when a source supports them.
- Separate what the sources say from your own judgment, and say which is which.
