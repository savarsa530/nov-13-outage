# Label analysis: what's load-bearing and what isn't

Nov 18, 2026. Counts come from the page's own data (index.html at v3.3). Nothing here changes a label. Each finding is a question for you to decide.

**Test used:** a label is load-bearing if removing it would force an item into a label that says something different about the evidence. A label used once can still be load-bearing. A label used zero times is either reserved (an end state items can move into) or dead.

## Summary

| Set | Labels defined | Used | Verdict |
|---|---|---|---|
| 1. Where things stand (status table, matrix) | 4 | 4 | All load-bearing |
| 2. Source tiers | 5 | 4 | Load-bearing; 1 compound, 1 unused in this set |
| 3. Dispute verdicts | 10 | 10 (7 used once) | Mostly load-bearing; 2 to check |
| 4. Intersections | 7 | 5 | Load-bearing; 2 reserved end states |
| 5. Facts vs. explanations grid | 5 | 5 | Load-bearing, but the visual merges two of them |
| 6. Claims on the record | 3 + 3 | 3 + 2 | Load-bearing; the empty "Specific" category is itself a finding |
| 7. Open questions | 3 | 3 | Fine |
| 8. Page's own read | 3 | 1 | Fine |

No label is clearly filler. The duplication you fought for holds up: the claims table and the dispute tracker look at the same statements on different axes (provenance vs. verdict). Cross-linking is right; merging would lose one axis.

## Set by set

### 1. Where things stand: Officially stated 8 · Reported 7 · Unknown 4 · Contested 2
All four carry distinct meanings. "Contested" is used only twice (Where it started, SMART's role), but those are the two places where officials or parties disagree with each other. Keep.

### 2. Source tiers: Confirmed 12 · Reported 9 · Hypothesized 2 · Confirmed / Reported 1 · Unverified 0
- **Confirmed (tier) vs. Officially stated (set 1)** is the most important distinction on the page. Confirmed means a document or record ("official record, FEC data or filings"). Officially stated means an official said it. **Check:** any Confirmed item that rests only on an official's spoken statement should probably be Officially stated. I haven't audited all 12.
- **Confirmed / Reported** (1, staffing) is a compound. Set 1 already shows two pills side by side for mixed cases ("FAA oversight on site"). Using two pills here would match. A display choice, not a loss.
- **Unverified** isn't used in this set. It appears once, in the dispute tracker and the quarantine box. Reserved, not dead.

### 3. Dispute verdicts (17 cards): Unresolved 5 · Partial 3 · Unproven 2 · then seven used once
Each single-use label encodes a different kind of verdict:
- **False as stated** (NWS radar outage) vs. **Contradicted by architecture** (NWS is unrelated): both say the record goes against the claim, but the first rests on an NWS statement and the second on this page's structural inference. Load-bearing: they differ in who is doing the contradicting.
- **Unproven** (2, a deliberate mirror pair: "SMART contributed" / "SMART could not have contributed") vs. **Unsupported** (orchestrated for funding) vs. **Unverified** ($5.8M donation): no evidence either way on a causal claim, vs. nothing for an inference about intent, vs. a checkable fact not found in the records. Load-bearing.
- **Officially stated** (not a cyberattack): borrowed from set 1 on purpose in v3.0. Load-bearing.
- **Check 1, "Unresolved" carries two senses.** On four cards it means competing named possibilities (installer, router, configuration, one site vs. two). On "ASI's PAC donation had no bearing" it means a number discrepancy ($2,500 vs. $12,500). The donation card might fit Unverified or a separate tag better.
- **Check 2, "Chronologically true" vs. "Partial."** The $50B card says the escalation came after the stop but the $30.1B request came before it. That reads close to Partial (true for part of the claim). It may be load-bearing because it names timing as the specific axis. Your call.
- **Check 3, "Under audit" (Peraton's oversight failed).** The only audit on the record in the page's data is the GAO audit of SMART (requested Oct 13). If no audit of Peraton is on the record, this label states something the record doesn't show. The card is also still marked "source not linked yet."

### 4. Intersections (9): open 4 · explained 2 · strong 1 · coincidence 1 · denied 1 · confirmed 0 · ruled out 0
"Confirmed" and "Ruled out" are unused, but they're where intersections end up when resolved. Reserved; keep.

### 5. Grid (40 cells): Cuts 13 · Fits 11 · Silent 10 · Not yet known 4 · Mixed 2
**Silent** (the fact doesn't bear on this explanation) and **Not yet known** (the information isn't public) are different claims. The cell text keeps them apart, but they share a color and the legend lumps them as "Silent or not yet known." **Possible fix:** a separate swatch for Not yet known. That changes display only.

### 6. Claims on the record (19): Named official 16 · Anonymous 4 · Interested party 1. Specificity: Partial 12 · No detail 7 · Specific 0
**Specific is defined but no claim on the record has earned it.** That's not filler; it's a finding worth surfacing: five days in, no claim has come with full supporting detail. Also, "Partial" here means something different from "Partial" in the dispute tracker; the label guide flags it. Renaming this one "Some detail" would remove the collision. That changes a word, so it's your call.

### 7–8. Questions (Open 17 · Partly answered 3 · Answered 1) and the page's own read (Moderate)
No issues.

## Cross-links this implies

**Claims ↔ disputes.** Same statements, different axes:

| Claim (claims table) | Dispute card |
|---|---|
| Not a cyberattack | It wasn't a cyberattack |
| Not SMART | "SMART isn't plugged in"; ASI's denial; SMART could not have contributed |
| "A single location" | It started at a single location |
| FAA monitored; FAA approved and signed off | The contractor caused it |
| Update / patches / routers overloaded / two places flooding | Installer error / faulty router / configuration error |

**Inconsistency:** the "single location" dispute card links q18, but the matching claim row links no question. Of the 17 dispute cards, 11 link no question; of the 19 claims, 5 link none.

**Questions in three places.** The register's "On-site oversight" group repeats q15, q16, q17 and q19 almost word for word, and its software group overlaps q11. Rows unique to the register, with no numbered question: SMART backoff and retry in both clouds; Peraton's change-control board; whether NWS traffic shared the affected router segments; NWS reconnects; the funding path. **Proposal:** each register row links its numbered question where one exists. The register keeps its own value (grouped by thread, "why it matters," "evidence needed"). "Also watching" is a watchlist of triggers, not questions; leave it separate.

## Decisions for you
1. Audit the 12 Confirmed tier items against "document vs. statement"?
2. "Unresolved" on the PAC donation card: keep, or another label?
3. "Chronologically true": keep as its own verdict?
4. "Under audit" on Peraton: is an audit of Peraton on the record?
5. Separate swatch for "Not yet known" in the grid?
6. Rename claims-table "Partial" to "Some detail"?
7. Build the claim ↔ dispute ↔ question cross-links as proposed?
