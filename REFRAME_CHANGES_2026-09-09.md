# Reframe 2026-09-09 — agm-case-study (branch `reframe-2026-09-09`, NOT pushed)

Brief: `docs/alden_briefs/2026-09-09_alden_website_messaging_update_handoff.md` (main repo). Category "Executive Intelligence Platform"; promise "Your software knows what happened yesterday. We tell you what to do tomorrow."; no implied formal Jobber support / marketplace listing / general connector availability. Texas Turf stays named (live customer, deployment-specific context). Heavenly Greens stays named with the operating relationship disclosed. Real Turf / Amazing Turf: not present in this repo (grep-verified).

Method: exact-string replacements, each asserted to occur exactly once; structure parity verified against `main` for all six pages (tag histogram, `id=` set, `href=` list, `class=` list, `<style>` and `<script>` blocks byte-identical). Only visible copy, `<title>`, and JSON label strings changed. No evidence deleted; no customer quotation altered (none exist in this repo).

## All six pages
- Nav: "Case Study #5: Jobber Bridge" → "Case Study #5: Texas Turf (Jobber deployment)" (href unchanged — the filename is a code reference).
- About block (index, #3, #4, #5): "enterprise integration platform for field service businesses…" → Executive Intelligence Platform definition; tagline → the brief's promise line. (#2 and #6 have no About block.)
- Footer (index, #3, #4, #5, #6): "Enterprise Integration for Field Service" → "Executive Intelligence for Home Services".

## index.html (Case Study #1, Heavenly Greens)
- "The Client": Heavenly Greens now introduced as "the contracting business our team operates" (relationship disclosed per brief §11/§12).

## case-study-2 (Heavenly Greens dashboards)
- Client intro: operating relationship disclosed.
- Universal vendor-wall claim ("Every contractor running Salesforce, ServiceTitan, Jobber, Housecall Pro, or Field Routes … has this exact problem") → "Any business running a field service platform alongside a separate CRM can end up with the same problem".

## case-study-3 (Heavenly Greens Zapier elimination)
- Client intro: operating relationship disclosed. Nothing else changed.

## case-study-4 (PestRoutes)
- Only the shared nav/About/footer. The three Jobber mentions in the body are technical API comparisons (webhooks vs polling, appointment CRUD) — deployment-specific evidence, left as-is.

## case-study-5 (Texas Turf)
- `<title>`: "The Jobber Bridge — Texas Turf Company" → "Texas Turf Company — Growth Automation Alongside Jobber".
- Subtitle → "a deployment-specific integration alongside Jobber, March 2026. Not a marketplace-listed or generally available connector." (this is the on-page context disclosure).
- "Jobber does not do growth automation" → "their Jobber setup did not cover growth automation".
- "the story we hear from almost every Jobber-based contractor" → pattern statement without the vendor generalisation.
- "where every Jobber contractor loses revenue" → "was where Texas Turf was losing revenue" (past tense, this deployment).
- "we built a bridge … zero disruption" → "a bridge specific to this deployment … without changing the crews' existing workflow".
- "Every contractor gets their own OAuth tokens…" (implied multi-tenant product) → "The deployment was built with its own OAuth tokens…".
- Cost comparison intro → dated "At the time of this deployment (March 2026), Jobber sold…"; AGM column detail "All growth automation included — fully managed, headless" → "As deployed for Texas Turf, March 2026 — managed by AGM".
- Closing: "You do not need to replace… no lead, no quote, and no customer falls through the cracks" (flawless-coverage claim) → Texas Turf–specific past-tense statement.
- H1 "How We Connected Jobber to a Full Growth Engine — Without Replacing Anything" left unchanged (it is the page's own headline; brief §SEO says align *future* titles). Troy may retitle.

## case-studies.json
- #5 `title`: "The Jobber Bridge" → "Texas Turf (Jobber deployment)"; `subtitle` → deployment-specific, dated.
- #1 `subtitle`: adds "(the contracting business our team operates)".
- `headline`, `file`, `url`, `number` keys untouched.

## Remaining "Jobber" mentions (copy vs code)
| file | copy | code (href/attr) |
|---|---|---|
| index.html | 1 (nav label) | 1 |
| case-study-2 | 1 (nav) | 1 |
| case-study-3 | 1 (nav) | 1 |
| case-study-4 | 4 (nav + 3 technical API comparisons) | 1 |
| case-study-5 | 28 (deployment narrative: API audit table, architecture table, "What did NOT change", cost comparison) | 2 (title/filename) |
| case-study-6 | 1 (nav) | 1 |
| case-studies.json | 2 (title + subtitle, deployment-labelled) | 2 (file + url) |

## Needs Troy (verification, not edits)
1. **Case study #5 metrics** — +$18K/mo, 47→120+ reviews, <2 min lead response, +28% quote conversion, 31% missed-call recovery, the $8,200/$6,100/$3,700 revenue-source split, and the month-1/2/3 review counts — kept as evidence per instruction; none has a cited source on the page. Confirm from the Texas Turf deployment records or add "as reported by the customer, [period]".
2. **Cost comparison block (#5)** — Jobber add-on prices ($199/$39/$29/$29/$99/$145) are March-2026 published prices; the AGM "$297/mo" column is the March deployment price, not the current $297 Contractor Automation Score tier. Rule on keeping or removing the whole block (structure cannot be removed under this brief — only relabelled).
3. **Texas Turf naming** — kept named per today's ruling; confirm the customer has approved the case-study page itself (no quote exists here, but the business is identified).
4. **#5 H1** — decide whether to retitle to the management problem + verified outcome.
5. **"Book a Free Strategy Call" → /booking** on every page — destination not verified in this pass.
