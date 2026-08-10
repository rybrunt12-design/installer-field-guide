# Correction Log — 2026-08-10

> **Recommendation document addressed to Ryan.** Nothing in this file edits the
> field guide (`index.html`, `guide-corpus.txt`) — every entry is a finding for
> your review; the edits are yours to make (Rule 1). Entries carry session-local
> IDs **K-01…K-11**; assign real C-numbers in the master log on your machine
> (its counter lives there, not here).
>
> Produced by an adversarial audit of everything claimed in this session:
> 8 independent verification agents, 94 claims tested, refute-first posture.
> **Scoreboard: 68 verified · 17 partial · 8 unverifiable · 1 refuted (audit
> artifact — an agent checked the wrong file; no real claim broke).**
> Source grades throughout: **A** manufacturer/federal/primary · **B**
> trade/utility · **C** vendor marketing · **D** arithmetic (mine, shown).

---

## Part A — Claude over-claims this session (Rule 2 log)

### K-01 · Chloramine resin lifespan — retracted (the serious one)

**What was said:** "Resin in chloramine cities lasts 3–7 years vs 10–15 in
free-chlorine cities," leading to "the single tank in a chloramine city is likely
a 5-year system sold as a 10-year system."

**What the audit found:** The 3–7 vs 10–15 figures trace to exactly one source —
Felite, a Chinese resin vendor's marketing blog (grade C). No manufacturer or
trade body corroborates. Worse, manufacturer literature ranks the oxidants the
**opposite** way: DuPont/Dow describe free chlorine (HOCl) as the stronger,
faster-acting resin oxidant; monochloramine is a *weaker* oxidant whose attack is
slower — its problem is persistence and poor removal by standard carbon, not
greater aggression toward resin.

**What survives:** Oxidant exposure does shorten resin life; the undersized 0.5 ft³
carbon layer is still the structural weakness; the Purolite 50%-per-ppm halving
rule is genuine (grade A, Purolite's own softening-factors page) **but is stated
for free chlorine** and cannot be applied 1:1 to Cedar Rapids' chloraminated water.

**Corrected statement:** In chloramine cities the resin sees a slower oxidant than
in free-chlorine cities at equal residual; expect *some* life reduction when the
carbon barrier is inadequate, magnitude unquantified. No year figure is quotable.
This was the classic failure: a real mechanism generalized one step past its
evidence.

### K-02 · CG10 "rated up to 1 ppm chlorine" — retracted

The "1 ppm free chlorine" tolerance is **reseller marketing copy** (aquascience.net,
Clean Water Store — grade C), not a ResinTech specification. ResinTech's own CG10
spec sheet (grade A) is qualitative only: 10% crosslinked strong-acid cation,
"superior resistance to breakdown in chlorinated waters," no ppm figure. The
"running the resin 3× past its rating" framing is withdrawn.

**Canon vindicated:** your 0.3 ppm cation / 0.05 ppm anion tolerances **verified
against DuPont** (grade A — the 0.05 ppm anion limit verbatim: "Continuous exposure
of anion resins to >0.05 ppm free chlorine should therefore be avoided"; cation
guidance ~0.2–0.3 ppm). Where the canon and the reseller disagreed, the canon was
right. The "50% longer life than 8%" line is also vendor copy, not ResinTech's.

### K-03 · Study misattribution

The GAC/IX PFAS EBCT study cited as "Kempisty et al. 2021" is **Murray et al.
2021** — Murray, Marshall, Liu, Vatankhah, Bellona (Colorado School of Mines),
*Journal of Water Process Engineering* 44:102342. Kempisty authored a different
GAC/PFAS paper. All experimental details cited from it are correct as stated
(GAC at 3/6/9 min EBCT, IX at 1/2/3 min; six 91 cm × 2.5 cm downflow columns,
0.46 L). Bed-volume breakthrough numbers remain paywalled — unretrieved.

### K-04 · "EWG arithmetic sound throughout" — overstated

Recomputing all 74 exceedance-table rows: 65 reproduce exactly; 9 differ by
0.17–0.9% (Dubuque BDCM 175 vs stated 176; Dubuque PFOS+PFOA 947 vs 946; Waterloo
PFHxS 1750 vs 1,747, TTHMs 71 vs 70, radium 7.2 vs 7.3, uranium 2.7 vs 2.6;
Davenport HAA9 470 vs 471, DCAA 66.5 vs 66; DSM HAA9 212 vs 211). Pattern is
consistent with EWG computing multiples from unrounded detected values. No
equipment recommendation changes.

### K-05 · ECT2 "vendor marketing" flag — softened

The 6–8× IX-vs-GAC figure is from **Woodard, Berry & Newman 2017, Remediation
Journal** — peer-reviewed, hosted on the vendor's site. Vendor-affiliated (grade
B, disclose the affiliation), but not mere marketing as earlier implied.

---

## Part B — Uploaded-file claims that degraded (recommended edits, yours to make)

### K-06 · Arsenic dump "~3× per Purolite's own chart" (00-HANDOFF)

The chromatographic-peaking mechanism is real and documented (Clifford 1999:
arsenic breaks through before sulfate; effluent exceeds influent — ~1.35× observed
in pilots, ~2.2–3.2× in modeling). But the classic documentation is on
**conventional sulfate-selective** SBA resin; Purolite's public A520E
(nitrate-selective) guide documents **nitrate** peaking, not a 3× arsenate chart.
**Keep the rule** (test arsenic before quoting any nitrate tank — it protects
against a real failure mode) — **fix the citation** or obtain the actual
nitrate-selective-resin arsenic data from Purolite/ResinTech.

### K-07 · "Plain GAC <20% effective" on chloramine (01-EWG master map)

Direction verified (grade A/B: WQA — standard GAC needs ~10 min EBCT for
chloramine vs ~3 min for catalytic/surface-enhanced). The specific "<20%" figure
traces only to vendor blogs. Recommend rewording to the contact-time comparison,
which is stronger anyway.

### K-08 · RO nitrate "70–76% certified range" (00-HANDOFF, standing Rule 3)

**No source found for 70–76% as the common certified range.** NSF/ANSI 58's
nitrate pass criterion (reduce ~27 mg/L challenge to ≤10 mg/L) implies a ~63–67%
minimum; actual certified performance sheets located run **91–92%**; third-party
summaries of certified systems say 85–95%. The claim-discipline *principle* is
right — quote only a certified number — but 70–76 may not be our number.
**Action: pull our RO unit's actual NSF/ANSI 58 listing and quote that figure,
whatever it is.** Until then, don't quote 70–76 either.

### K-09 · DMWW nitrate facility "used only in extraordinary situations" (01-EWG)

Quote unsourced and now outdated. Facility and 1992 vintage verified (world's
largest IX nitrate facility, in service 1992). But it ran **60+ consecutive days
in summer 2025** (with DMWW's first-ever lawn-watering ban), again in **January
2026** (rare winter operation), with levels high into spring 2026. The Des Moines
nitrate story is *stronger* than the file implies — arguably a second lead for the
DSM pitch alongside DBPs.

### K-10 · Waterloo "16 exceed" / Davenport "14 exceed" counts — disputed

The only reachable EWG-derived source (echowater.com Iowa ranking) says **19** for
Waterloo and **15** for Davenport. EWG itself and every mirror carrying counts are
egress-blocked from this environment. Could be snapshot timing or PFAS grouping.
Verify on ewg.org from your machine before either count is used anywhere.

### K-11 · "Chlorite: RO; carbon partial" (01-EWG) — understates carbon

GAC is a **recognized chlorite reductant** (catalytically reduces ClO₂⁻ to
chloride; near-complete when fresh), listed alongside sulfite and ferrous iron as
one of the three established chlorite-removal methods. Its limitation is finite,
declining capacity — not weak removal. RO half of the claim verified. Recommended
rewording: "carbon: strong when fresh, capacity-limited; RO: continuous."

---

## Part C — What fully verified (so the log shows what survived)

- **Field guide text:** every quoted passage confirmed verbatim; peroxide appears
  14× (index.html) / 7× (guide-corpus.txt); the guide's only sulfur remedy is the
  retired peroxide build; zero mentions of nitrate/radium/uranium/arsenic/
  chromium/atrazine/VIQUA/Marion; the 95–99% RO claim covers "TDS, heavy metals,
  microplastics, PFAs, and bacteria/viruses" and does not name nitrate.
- **Cross-file conflict confirmed:** the chat script's WELL train contains no
  carbon stage while the handoff canon requires wells-carbon-LAST.
- **EBCT/bed-volume arithmetic:** all reproduced, including 3–5 gpm/ft³ ≡ 1.5–2.5
  min EBCT and the 22 s @ 10 gpm canon cross-check.
- **EPA regulatory (grade A, current to 2026-08-10):** 2024 final MCLs 4.0 ppt
  PFOA/PFOS, individually, being **kept**; May 2026 proposals — FR 2026-10085
  (rescind PFHxS/PFNA/GenX/Hazard-Index) and FR 2026-10086 (compliance extension
  2029→2031); comments closed 7/20/26, hearing 7/7/26; **both still proposed, not
  final**. PFHxS "10 ppt" describes the 2024 rule now under proposed rescission.
  EPA BAT for PFAS: GAC, anion exchange, NF/RO (Doc 815-R-24-011).
- **Utility facts (cities' own pages):** Cedar Rapids chloramine ("trace amount of
  ammonia"), softening 15.8 → 6.5–7 gpg; Davenport/Iowa American chloramine with
  CCR dialysis warning; Waterloo wellhead chlorine + orthophosphate, no central
  plant; DMWW free chlorine with Bondurant/Warren/Xenia chloramine (per DMWW's own
  brewers page). Dubuque chlorination-only near-certain; the word "free" not
  found in a reachable source.
- **Mechanisms (grade A):** softener removes radium ~90–95% (EPA-recognized BAT);
  softener removes zero nitrate/Cr-6/arsenate/PFAS; uranium travels as anionic
  carbonate complexes, RO >99% (anion exchange also works — the "RO only" framing
  slightly undersells options); chlorination converts As(III)→As(V), the
  RO-removable form; TTHM shower-inhalation exposure is peer-review-supported and
  GAC10 is EPA's listed BAT for TTHMs; 1,4-dioxane resists carbon and RO, AOP is
  the real technology (the file's honesty line stands); short-chain PFAS break
  through GAC first (Calgon RSSCT); Iowa pesticide degradates dominate parents
  (USGS: metolachlor ESA in ~83% of monitored wells); 25,000–70,000 BV PFOA/PFOS
  breakthrough at ~10 min EBCT (grade B, OCWD pilot/ITRC).
- **ResinTech products:** SIR-100-HP nitrate-selective, regenerable; SIR-110-HP
  PFAS/nitrate/perchlorate-selective, single-use (spec sheets). Dealer prices
  private, unverifiable, as expected.

## Part D — Pull these on your machine (egress-blocked here)

1. **EWG tapwater pages ×5** — settle the Waterloo 16-vs-19 and Davenport
   14-vs-15 counts; spot-check the headline levels.
2. **Cedar Rapids CCR** (cedar-rapids.org water quality report) — confirm the
   3.1 ppm avg / 1.7–3.8 total chlorine residual. Sole unverified number in the
   chloramine analysis.
3. **Aries/ResinTech catalytic carbon MEDIA datasheet** (not the cartridge line —
   reseller listings only cover AF-series cartridges at 0.75–2 gpm) — the
   chloramine flow-per-ft³ rating that settles the Dual-Tank City sizing question.
4. **Our RO unit's NSF/ANSI 58 listing** (info.nsf.org) — the actual certified
   nitrate figure to replace 70–76% (K-08).
5. **ResinTech configuration guidance ask** — nitrate-tank-before-PFAS-tank
   ordering, and whether chloride off the regenerated nitrate bed shortens
   SIR-110-HP life. Same bar as the Purolite arsenic question (K-06).

---

## R-01 · Ruling — carbon grade for the single-tank city build (2026-08-10)

Saved at Ryan's request from the in-chat walkthrough; post-audit corrected.

**Free-chlorine city (Dubuque, Waterloo, Des Moines proper): activated.**
Catalytic is wasted money — activated carbon handles free chlorine, and the
catalytic upcharge buys **zero** extra PFAS removal (PFAS capture is adsorption;
grade is irrelevant — contact time and cubic feet are what count).

**Chloramine city (Cedar Rapids, Davenport, chloramine DSM suburbs), single
tank: catalytic as harm reduction only.** Right chemistry, undersized container.
WQA (grade B): standard GAC needs ~10 min EBCT for chloramine vs ~3 min for
catalytic — but the single tank's 0.5 ft³ layer gives ~45 s at 5 gpm. Catalytic
turns "barely touches chloramine" into "knocks a real fraction down": slower
resin wear, less chlorine taste at the tap. **The single tank cannot claim
chloramine removal at any carbon grade.**

**Chloramine city, correct build: Dual-Tank City with catalytic media** —
2.5 ft³ gives 2–4 min EBCT at household flows. The chloramine claim belongs to
this build alone.

**Resin-life framing (per K-01/K-02):** dual-tank resin life is a design
guarantee — the resin never sees the oxidant. Single-tank resin life under
chloramine is unquantifiable from desk sources (no manufacturer publishes a
figure; the Purolite halving rule is for free chlorine). Narrow it with field
data: a total-chlorine test strip at the tap of an existing Cedar Rapids
single-tank install, and the softening performance of the oldest CR installs.

**Open dependencies:** (a) Anthony — is catalytic media orderable on city
builds, single-tank and Dual-Tank City; (b) the actual carbon media datasheet —
the ~3-min catalytic figure is trade-grade (B) until then.
