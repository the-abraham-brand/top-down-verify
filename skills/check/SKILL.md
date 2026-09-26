---
name: check
description: Top-Down Verify document check. Audit a whole document (report, proposal, article, website copy, deck, email, press release) before it goes out: every claim, figure, date, name, quote, calculation and link checked against trusted sources and the document itself; returns a verdict, priority fixes, a claim ledger and a corrected version. Use when the user runs /top-down-verify:check, or attaches or pastes a document and asks to fact-check it, verify it, or confirm it is accurate before sending or publishing.
---

# /top-down-verify:check

Audit a document before it goes out.

1. Load the `top-down-verify` skill from this plugin (via the Skill tool) and follow it in **Document check** mode. If it cannot be loaded, read `../top-down-verify/SKILL.md` and its `references/` folder directly.
2. Take the document from the attachment (.docx, .pdf, .pptx, .xlsx, .md, .txt), a URL, or pasted text. Read all of it, including tables, footnotes, speaker notes and image captions.
3. Establish audience, stakes, subject, geography and date; note which figures are the author's own.
4. Extract and number every claim with its location, type and risk level.
5. Verify every High and Medium claim against trusted sources (corroborating High ones), recompute every calculation, cross-check repeated figures, and test every link. State coverage honestly.
6. Deliver the verdict, priority fixes, claim ledger, corrected version in the original format, and the list for the author to confirm.
