---
name: claim
description: Top-Down Verify single-claim check. Verify one statistic, statement or quote and trace it to its original source using only trusted sources; returns True / Partly true / False / Outdated / Unverified, what the sources say, and a corrected sentence. Use when the user runs /top-down-verify:claim, or asks "is this true", "where does this stat come from", or "can I use this figure".
---

# /top-down-verify:claim

Verify a single claim and trace it to its origin.

1. Load the `top-down-verify` skill from this plugin (via the Skill tool) and follow it in **Claim check** mode. If it cannot be loaded, read `../top-down-verify/SKILL.md` and its `references/` folder directly.
2. Restate the claim precisely: the number or statement, its unit, geography, period and definition. If any of these are missing, note that the claim is ambiguous and check the most likely reading, saying which one you checked.
3. Plan who would hold authoritative data on it, search, and open the sources. Apply the trust test; trace the figure back to where it originated, including through any roundup pages that repeat it.
4. Deliver: the verdict (True / Partly true / False / Outdated / Unverified), what the trusted sources say with publisher, date and link, where the claim most likely came from, and a corrected sentence ready to use. If no trusted source exists, say so plainly and suggest how to reword the claim.
