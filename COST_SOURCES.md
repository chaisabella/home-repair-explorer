# Cost sources and review

This document records where the repair and replacement prices in the home repair explorer come from, how they were checked, and how much weight they can bear. It is written so another person could repeat the check.

Review date: 2026-11-09. All sources were accessed on that date unless noted.

## 1. Summary

- The explorer contains 274 repair and replacement ranges across 137 parts, plus hover ranges for 9 rooms and areas.
- The first build did not store a citation for any figure. Each range carried only a flag: "guide-based" (28 ranges) or "ballpark" (246 ranges). The guide-based flag was never tied to a specific page, so it is treated here as unverified.
- This review checked 20 of the largest or most common figures against 41 published sources (Section 5). The results:
  - 11 are consistent with published ranges.
  - 3 are partly consistent (the sources disagree with each other, or the figure fits one case but not another).
  - 5 are higher than published ranges.
  - 1 is lower than published ranges.
- Everything else (the large majority of the 274 ranges) is still an unreviewed ballpark. Appendix A lists every figure and marks which were checked.
- No figure on the page has been changed because of this review. Suggested revisions are listed in Section 5 for the five "higher" and one "lower" cases.

## 2. What the figures mean

| Term | Meaning in this project |
|---|---|
| Repair | Fixing the existing part. Parts and labor, no permit. |
| Replace | Removing the part and installing a new one. Parts and labor, usually no permit or collateral work such as drywall repair. |
| Remodel | Used only for room-level hover ranges (kitchen, bathroom). Scope varies by source. |
| Range | A low-to-high span meant to cover most jobs in the US, not the minimum or maximum ever charged. |
| `~` on the page | The range is a ballpark that was not checked against a source at build time. |

Geography is national. No adjustment has been made for Cleveland or any other market. Dollar years are 2026 unless a source is marked otherwise.

## 3. Source hierarchy

Sources were ranked by how much confidence the underlying data deserves.

1. **Government or academic cost data** (for example BLS price indexes, Census American Housing Survey, university extension publications). None was used for individual line items in this review. These sources give indexes and surveys of spending, not per-job price ranges for most parts.
2. **Cost publishers that disclose a method** (a stated number of projects, a survey, or contractor data): Angi, HomeAdvisor, This Old House (homeowner survey), Fixr (editorial method page), Thumbtack (platform data).
3. **Secondary pages that cite a Tier 2 publisher** (NerdWallet, SoFi, HomeLight). They are used only as a convenient place where a Tier 2 figure is stated, and are labeled as such. They are not counted as independent confirmation.
4. **Single-publisher estimators with no disclosed method** (Homeyou, Inch Calculator, Modernize). Used only where nothing in Tier 2 was found, and flagged.

Excluded without citation: contractor marketing pages, pages with no author or method, auto-generated pages that repeat other sites' numbers, and non-US figures.

Two independence notes:

- Angi and HomeAdvisor are owned by the same company and publish overlapping data. Where both give a number, it is treated as roughly one source.
- NerdWallet, SoFi and HomeLight pages here quote Angi or HomeAdvisor, so they do not add independent evidence.

## 4. How figures were compared

For each part, the explorer's range was compared with the central range each source reports (the "typical" or "most homeowners pay" span, not the extreme low and high).

- **Consistent:** the explorer's range overlaps most of the sources' typical ranges, and neither end is outside them by more than about a third.
- **Partly consistent:** it fits some sources but not others, or fits one scope (for example vinyl siding) but not the one the explorer shows (brick).
- **Higher / lower:** the explorer's range sits above or below the sources' typical range.

This is a judgment rule, not a statistical test. No attempt was made to weight sources by sample size, and most publishers do not disclose enough to do so.

## 5. Benchmark results

Source IDs (S1, S2, …) refer to the register in Section 6. Figures are the national ranges each source states.

| ID | Part and action | Explorer range | Published ranges (source) | Result | Suggested range if adopted |
|---|---|---|---|---|---|
| B1 | Roof, replace | $6,000–$16,000 | $7,500–$14,000 (S2); $6,885–$23,993, avg $15,439 (S3); avg $9,610 (S1); $5,800–$46,000 incl. premium materials (S4) | Consistent | none |
| B2 | Foundation, repair | $500–$10,000 | $2,224–$8,134 (S5); $2,200–$8,200 (S6); about $2,200–$8,100 (S7). Crack sealing alone $200–$1,000 (S6) | Consistent. The explorer's range is wider at both ends because it includes minor cracks and larger structural work | none |
| B3 | Furnace, replace | $4,000–$8,000 | $2,823–$6,888, avg about $4,800 (S8, citing Angi) | Higher. The explorer's low end sits at the national average | $2,800–$6,900 |
| B4 | Water heater, replace | $1,200–$3,500 | $1,000–$2,700 gas (S9); $900–$3,000 (S10); $1,487–$3,873 (S11) | Consistent | none |
| B5 | Electrical panel, replace | $1,500–$4,000 | $2,185–$6,185 (S12); 200-amp $1,618–$2,704 (S13); $800–$2,500, 200-amp $1,800–$3,000 (S14) | Partly consistent. Sources diverge and none is Tier 2 | none, pending a better source |
| B6 | Windows, replace (whole house) | $3,000–$15,000 | $4,500–$20,000 for most whole-house jobs, avg $750 per window (S15); $450–$1,200 per window (S16); avg $477 per window (S17) | Consistent. The result depends on window count, which the explorer does not state | none |
| B7 | Gutters, replace | $1,000–$3,000 | $724–$2,055 (S18); $626–$1,718 (S19); avg $2,593 (S20) | Higher | $700–$2,100 |
| B8 | Gutters, repair | $150–$500 | $188–$623, avg $381 (S20) | Consistent (one source) | none |
| B9 | Chimney, repair | $200–$3,000 | Masonry repair $300–$1,500; cap about $300; liner $625–$7,000 (S21, citing HomeAdvisor); tuckpointing $500–$2,500, 2022 data (S22) | Consistent for masonry work. Liner work can exceed the range | none |
| B10 | Siding, replace | $8,000–$25,000 | $5,567–$17,651, avg $11,536 (S23); $8,500–$20,000 (S24); $8,000–$30,000 (S25). Brick or stone, 2,000 sq ft: $18,000–$100,000 (S23) | Partly consistent. Fits vinyl and fiber cement. The house drawn in the explorer is brick, which costs more | brick/stone: see S23 |
| B11 | Plumbing, replace (whole-house repipe) | $4,000–$15,000 | $3,600 at 800 sq ft to $13,500 at 3,000 sq ft (S26). The same page's headline range ($372–$2,131) contradicts its own table | Consistent with the table. Only one source, and it is internally inconsistent | none, pending a second source |
| B12 | Attic insulation, replace | $1,500–$5,000 | $1,500–$4,500 (S27) | Consistent (one source) | none |
| B13 | Bathroom, full remodel (hover range) | $8,000–$25,000 | $6,639–$17,620, avg $12,122 (S28); $6,000–$18,000, avg $12,000 (S29) | Higher | $6,000–$18,000 |
| B14 | Kitchen, full remodel (hover range) | $10,000–$40,000 | $14,589–$41,534, avg $26,944 (S30, S31); $15,000–$45,000 (S32) | Lower. The explorer's low end is below the published range | $15,000–$45,000 |
| B15 | Handrail, repair | $75–$400 | $300–$700 (S33); $100–$500 (S34) | Partly consistent. Low end is below published figures | $100–$700 |
| B16 | Handrail, replace | $300–$1,500 | $500–$1,300, avg $900 (S34); indoor install $725–$2,263 (S36) | Consistent | none |
| B17 | Stairs, rebuild (hover range) | $3,000–$10,000 | $953–$3,236, avg $2,047 (S35); straight stairs $1,900–$5,000 (S41) | Higher. Curved or custom stairs can exceed these | $1,000–$5,000 for straight stairs |
| B18 | Porch, repair | $500–$3,000 | $250–$1,500, avg $850 (S37) | Higher | $250–$1,500 |
| B19 | Porch, replace | $5,000–$20,000 | Build a new porch $4,600–$22,000, 2024 data (S38) | Consistent. Source is for new construction, not rebuilds | none |
| B20 | AC, replace | $3,000–$8,000 | $3,900–$7,900 (S39); $3,000–$7,500 (S40) | Consistent | none |

### What was not verified

The first build flagged some ranges as guide-based. This review could not confirm these, either because no adequate source turned up or because the part was not searched:

- Roof repair ($300–$1,500). The only figure found came from a source with no disclosed method.
- Chimney flashing, foundation replacement, chimney replacement, siding paint, whole electrical system, furnace repair, AC repair, driveway replacement.
- All room-level rows (walls, ceiling, floor, doors, lighting, outlets, pests, mold, etc.) and every other part not in the table above.

These remain labeled as ballpark in the explorer's footer and in Appendix A.

## 6. Source register

Quoted figures are paraphrased from the pages' stated ranges. URLs are as returned by search on the review date. Some publisher URLs have slugs that do not match the page topic (for example a Fixr roof page at a "mansard-roof" path), so the page title is given as well.

| ID | Publisher | Page title (as shown) | URL | Date on page | Tier |
|---|---|---|---|---|---|
| S1 | Angi | Roof replacement cost, based on 32,999 verified projects | https://www.angi.com/articles/real-cost-new-roof.htm | 2026 | 2 |
| S2 | Fixr | How Much Does a Roof Replacement Cost? [2026 Data] | https://www.fixr.com/costs/mansard-roof | 2026 | 2 |
| S3 | This Old House | New roof cost | https://www.thisoldhouse.com/roofing/new-roof-cost | updated 2026-05-19 | 2 |
| S4 | NerdWallet | Roof Replacement Cost in 2026 (cites Angi) | https://www.nerdwallet.com/home-ownership/home-improvement/learn/roof-replacement-cost | 2026 | 3 |
| S5 | This Old House | How Much Does Foundation Repair Cost? (2026 Pricing) | https://www.thisoldhouse.com/foundations/foundation-repair-cost | updated 2026-03-06 | 2 |
| S6 | Fixr | How Much Does Foundation Repair Cost? [2026 Data] | https://www.fixr.com/costs/repair-foundation | updated 2026-01-27 | 2 |
| S7 | NerdWallet | Foundation Repair Cost in 2026 | https://www.nerdwallet.com/article/mortgages/foundation-repair-cost | 2026 | 3 |
| S8 | NerdWallet | Cost to Replace a Furnace (cites Angi 2026 data) | https://www.nerdwallet.com/home-ownership/home-improvement/learn/cost-to-replace-a-furnace | 2026 | 3 |
| S9 | Fixr | Cost to install a gas water heater [2026 Data] | https://www.fixr.com/costs/gas-water-heater | updated 2026-01-30 | 2 |
| S10 | Fixr | Cost to install a water heater [2026 Data] | https://origin-2.fixr.com/costs/install-water-heater | updated 2026-01-27 | 2 |
| S11 | Homeyou | Water heater replacement cost | https://www.homeyou.com/water-heater-replacement-cost | updated 2026-04-17 | 4 |
| S12 | Homeyou | Electrical panel upgrade cost | https://www.homeyou.com/electrical-panel-upgrade-cost | 2026 | 4 |
| S13 | Homeyou | Electrical cost | https://www.homeyou.com/electrical-cost | 2026 | 4 |
| S14 | Inch Calculator | Cost to Upgrade Electrical Panel, 2026 Price Guide | https://inchcalculator.com/electrical-panel-upgrade-cost-guide | 2026 | 4 |
| S15 | Angi | How Much Does Window Replacement Cost? [2026 Data] | https://www.angi.com/articles/repurpose-old-windows-these-diy-projects.htm | 2026 | 2 |
| S16 | Fixr | How Much Does Window Replacement Cost? [2026 Data] | https://www.fixr.com/costs/window-replacement | updated 2026-01-21 | 2 |
| S17 | This Old House | Window Replacement Cost (2026 Guide) | https://www.thisoldhouse.com/windows/window-replacement-cost | 2026 | 2 |
| S18 | Thumbtack | How much does it cost to replace gutters? | https://thumbtack.com/p/gutter-installation-cost | updated 2026-07-01 | 2 |
| S19 | HomeAdvisor | How Much Does Gutter Replacement Cost? | https://www.homeadvisor.com/cost/gutters/install-gutters-and-downspouts | page dated 2025 | 2 |
| S20 | Homeyou | Gutters cost | https://www.homeyou.com/gutters-cost | updated 2026-04-17 | 4 |
| S21 | SoFi | Chimney Repair Costs 2026 (cites HomeAdvisor) | https://www.sofi.com/learn/content/cost-to-replace-chimney/ | 2026-04-08 | 3 |
| S22 | HomeAdvisor | How Much Do Tuckpointing and Repointing Cost? | https://www.homeadvisor.com/cost/heating-and-cooling/repoint-or-tuckpoint/ | updated 2022-08-08 | 2 (dated) |
| S23 | Angi | How Much Does It Cost to Replace or Install Siding? | https://www.angi.com/articles/how-much-does-siding-cost-replace.htm | 2025 data | 2 |
| S24 | Fixr | How Much Does It Cost to Replace Siding? [2026 Data] | https://www.fixr.com/costs/liquid-siding-installation | updated 2026-01-23 | 2 |
| S25 | This Old House | Siding Replacement Cost (2026 Pricing) | https://www.thisoldhouse.com/siding/siding-replacement-cost | 2026 | 2 |
| S26 | HomeAdvisor | How Much Does It Cost to Repipe a House? | https://www.homeadvisor.com/cost/plumbing/install-new-plumbing-pipes | page dated 2025 | 2 |
| S27 | Modernize | How Much Does Attic Insulation Cost in 2026? | https://modernize.com/insulation/attic-insulation-cost | 2026 | 4 |
| S28 | Angi | How Much Does a Bathroom Remodel Cost? [2026 Data] | https://www.angi.com/articles/how-much-does-bathroom-remodel-cost.htm | 2026 | 2 |
| S29 | Fixr | How Much Does It Cost to Remodel a Bathroom? [2026 Data] | https://www.fixr.com/costs/bathroom-design | 2026 | 2 |
| S30 | Angi | Kitchen remodel, 2026 average from 13,100 verified projects | https://www.angi.com/articles/5-errors-can-derail-your-kitchen-remodel.htm | 2026 | 2 |
| S31 | HomeLight | How Much Does It Cost to Remodel a Kitchen in 2026? (compares Angi, Fixr and others) | https://www.homelight.com/blog/how-much-to-remodel-a-kitchen/ | 2026 | 3 |
| S32 | Fixr | How Much Does a Kitchen Remodel Cost? [2026 Data] | https://www.fixr.com/costs/built-in-seating | 2026 | 2 |
| S33 | Angi | How Much Does Stair Railing Repair Cost? | https://www.angi.com/articles/stair-railing-repair-cost.htm | 2025 data | 2 |
| S34 | Angi | How Much Does It Cost to Install Stair Railings? | https://angi.com/articles/approximately-how-much-should-it-cost-install-stair-railing-has-5-stairs-railing-needed.htm | 2025 data | 2 |
| S35 | HomeAdvisor | How Much Does Stair Replacement Cost? | https://www.homeadvisor.com/cost/stairs-and-railings/build-stairs-or-railings | page dated 2025 | 2 |
| S36 | Thumbtack | How much does it cost to install a stair railing? | https://www.thumbtack.com/p/stair-banister-installation-cost | updated 2026-06-22 | 2 |
| S37 | Fixr | How much does it cost to repair a porch? | https://www.fixr.com/costs/porch-repair | 2026 | 2 |
| S38 | HomeAdvisor (via Angi match page) | How Much Does It Cost to Build a Porch? | https://match.angi.com/cost/outdoor-living/build-a-porch | updated 2024-01-31 | 2 (dated) |
| S39 | Angi | How Much Does HVAC Replacement Cost? [2026 Data] | https://angi.com/articles/insider-s-price-guide-new-heating-and-cooling-system.htm | 2026 | 2 |
| S40 | Sears Home Services | How Much Does It Cost to Replace an Air Conditioner in 2026? | https://www.searshomeservices.com/blog/how-much-does-it-cost-to-replace-an-air-conditioner-in-2026 | 2026 | 4 |
| S41 | Bob Vila | How Much Does It Cost to Replace Stair Railings? (straight stairs figure) | https://bobvila.com/articles/cost-to-replace-stair-railing | n/a | 4 |

## 7. Known limits

- **National, not local.** Costs in Cleveland may differ. No regional factor was applied.
- **Old homes cost more.** Hidden damage, lead paint, asbestos and non-standard sizes raise prices in pre-1978 housing, and most published ranges are for typical conditions.
- **Scope drift.** "Repair" and "replace" mean different things across publishers. For example, the Fixr foundation range spans crack injection to pier work.
- **Dated sources.** S22 (2022), S38 (2024) and several 2025-labeled pages are older than the rest.
- **Publisher incentives.** Angi, HomeAdvisor, Thumbtack, Fixr and Modernize earn money from contractor leads. Their ranges are widely used but not independently audited.
- **No bid data.** No actual contractor quotes were collected. The strongest next step would be written quotes from local contractors for the largest items.
- **Mixed vintages.** Some pages show a 2026 label but may have been refreshed only in part.
- **One pass.** A single person searched and compared once. Nothing was double-coded or independently checked.

## 8. Next steps for a research-grade version

1. Store a source record with every figure: publisher, URL, access date, low, high, what the number measures (average, typical range, extremes), and scope (repair, replace, remodel).
2. Show the citation for each figure in the explorer's hover and detail views.
3. Require at least two independent Tier 2 sources before any range loses the `~`.
4. Replace the national ranges with a documented local adjustment, using a published cost-location index or written bids from Cleveland contractors.
5. Define repair, replace and remodel for each part so ranges are comparable.
6. Apply the Section 5 suggestions or document why a different range was kept.
7. Keep a change log of every figure edit with a date and reason.

## Appendix A. Every figure in the explorer

Flag key: **G** = flagged guide-based in the first build and not individually verified. **E** = ballpark. "Checked" lists the Section 5 rows that cover the part.


### The yard and property

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Trees | $300–$1,500 | $500–$3,000 | E / E |  |
| Landscaping & lawn | $200–$1,500 | $1,000–$6,000 | E / E |  |
| Grading / drainage | $500–$4,000 | $3,000–$15,000 | E / E |  |
| Driveway | $300–$1,500 | $1,500–$8,000 | E / G |  |
| Garage / ADU | $300–$3,000 | $8,000–$40,000 | E / E |  |
| Sidewalk | $200–$1,500 | $1,500–$5,000 | E / E |  |
| Pests / wildlife | $150–$800 | $500–$4,000 | E / E |  |
| Other / obstructions | $100–$1,000 | $500–$3,000 | E / E |  |

### Roof

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Roof | $300–$1,500 | $6,000–$16,000 | G / G | B1 |

### Chimney

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Chimney(s) | $200–$3,000 | $3,000–$12,000 | G / E | B9 |
| Chimney flashing | $200–$500 | $500–$1,500 | G / E |  |

### Gutters and roofline

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Fascia | $200–$1,000 | $1,000–$4,000 | E / E |  |
| Soffit | $150–$800 | $800–$3,000 | E / E |  |
| Gutters | $150–$500 | $1,000–$3,000 | E / E | B7, B8 |
| Downspouts | $50–$300 | $150–$800 | E / E |  |
| Downspout – sewer connection | $150–$800 | $500–$2,500 | E / E |  |

### Walls: brick, siding and paint

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Siding – material | $300–$2,500 | $8,000–$25,000 | E / E | B10 |
| Siding – paint | $3,000–$10,000 | $5,000–$15,000 | G / E |  |

### Foundation

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Foundation | $500–$10,000 | $15,000–$40,000 | E / E | B2 |

### Porch and outside steps

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Porch | $500–$3,000 | $5,000–$20,000 | E / E | B18, B19 |
| Entry stairs (exterior) | $300–$2,000 | $1,500–$6,000 | E / E |  |

### Front door

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Entry door | $100–$400 | $500–$2,500 | E / E |  |

### Windows

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Windows | $150–$600 | $3,000–$15,000 | E / G | B6 |
| Emergency egress | $100–$600 | $800–$5,000 | E / E |  |

### Furnace

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Furnace / heat | $125–$500 | $4,000–$8,000 | G / G | B3 |

### Heating ducts

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Ducts / HVAC condition | $200–$1,000 | $1,500–$5,000 | E / E |  |

### Water heater

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Water heater | $150–$600 | $1,200–$3,500 | E / E | B4 |

### Plumbing

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Plumbing system | $150–$800 | $4,000–$15,000 | E / E | B11 |
| Water main | $200–$1,000 | $1,500–$5,000 | E / E |  |
| Drain line / cleanout | $150–$600 | $3,000–$10,000 | E / E |  |

### Electrical

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Electrical system | $100–$350 | $8,000–$15,000 | G / G |  |
| Electric panel | $150–$500 | $1,500–$4,000 | E / G | B5 |

### Gas connection

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Gas connection | $150–$600 | $500–$3,000 | E / E |  |

### Laundry

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Laundry | $100–$400 | $500–$2,500 | E / E |  |

### Air conditioner

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| AC / cooling | $150–$650 | $3,000–$8,000 | G / E | B20 |

### Basement

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Basement: Interior walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Basement: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Basement: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Basement: Doors | $50–$300 | $200–$800 | E / E |  |
| Basement: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Basement: Lighting | $75–$300 | $150–$600 | E / E |  |
| Basement: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Basement: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Basement: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Basement: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Basement: Supports / beam | $500–$3,000 | $2,000–$10,000 | E / E |  |

### Kitchen

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Kitchen: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Kitchen: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Kitchen: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Kitchen: Doors | $50–$300 | $200–$800 | E / E |  |
| Kitchen: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Kitchen: Lighting | $75–$300 | $150–$600 | E / E |  |
| Kitchen: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Kitchen: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Kitchen: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Kitchen: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Kitchen: Cabinets | $150–$1,000 | $3,000–$15,000 | E / E |  |
| Kitchen: Countertop | $100–$600 | $1,500–$6,000 | E / E |  |
| Kitchen: Pantry | $100–$500 | $500–$3,000 | E / E |  |
| Kitchen: Refrigerator | $100–$400 | $800–$2,500 | E / E |  |
| Kitchen: Stove / oven | $100–$400 | $600–$2,500 | E / E |  |
| Kitchen: Vent fan | $75–$300 | $200–$800 | E / E |  |
| Kitchen: Sink | $100–$400 | $300–$1,500 | E / E |  |
| Kitchen: Plumbing | $150–$800 | $500–$3,000 | E / E |  |

### Dining room

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Dining room: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Dining room: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Dining room: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Dining room: Doors | $50–$300 | $200–$800 | E / E |  |
| Dining room: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Dining room: Lighting | $75–$300 | $150–$600 | E / E |  |
| Dining room: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Dining room: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Dining room: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Dining room: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Dining room: Built-ins / cabinetry | $100–$600 | $500–$4,000 | E / E |  |

### Living room

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Living room: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Living room: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Living room: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Living room: Doors | $50–$300 | $200–$800 | E / E |  |
| Living room: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Living room: Lighting | $75–$300 | $150–$600 | E / E |  |
| Living room: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Living room: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Living room: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Living room: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Living room: Closet / built-ins | $100–$500 | $300–$3,000 | E / E |  |

### Bedroom

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Bedroom: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Bedroom: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Bedroom: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Bedroom: Doors | $50–$300 | $200–$800 | E / E |  |
| Bedroom: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Bedroom: Lighting | $75–$300 | $150–$600 | E / E |  |
| Bedroom: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Bedroom: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Bedroom: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Bedroom: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Bedroom: Closet | $100–$500 | $300–$2,000 | E / E |  |

### Bathroom

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Bathroom: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Bathroom: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Bathroom: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Bathroom: Doors | $50–$300 | $200–$800 | E / E |  |
| Bathroom: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Bathroom: Lighting | $75–$300 | $150–$600 | E / E |  |
| Bathroom: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Bathroom: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Bathroom: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Bathroom: Cabinets | $150–$1,000 | $500–$3,000 | E / E |  |
| Bathroom: Countertop | $100–$600 | $500–$2,500 | E / E |  |
| Bathroom: Vent fan | $75–$300 | $150–$700 | E / E |  |
| Bathroom: Toilet | $75–$300 | $300–$900 | E / E |  |
| Bathroom: Sink | $100–$400 | $250–$1,000 | E / E |  |
| Bathroom: Shower / bath | $150–$1,500 | $2,500–$10,000 | E / E |  |
| Bathroom: Plumbing | $150–$800 | $500–$3,000 | E / E |  |

### Attic

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Attic: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Attic: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Attic: Floor | $200–$1,500 | $1,500–$6,000 | E / E |  |
| Attic: Doors | $50–$300 | $200–$800 | E / E |  |
| Attic: Windows | $150–$600 | $300–$1,000 | E / G |  |
| Attic: Lighting | $75–$300 | $150–$600 | E / E |  |
| Attic: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Attic: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Attic: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Attic: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Attic: Stairwell / access | $100–$600 | $500–$3,000 | E / E |  |
| Attic: Built-ins / cabinetry | $100–$500 | $500–$3,000 | E / E |  |
| Attic: Insulation | $300–$1,500 | $1,500–$5,000 | E / E | B12 |

### Stairs

| Part | Repair | Replace | Flags (repair / replace) | Checked |
|---|---|---|---|---|
| Stairs: Walls | $150–$1,500 | $2,000–$10,000 | E / E |  |
| Stairs: Ceiling | $150–$1,500 | $1,500–$6,000 | E / E |  |
| Stairs: Lighting | $75–$300 | $150–$600 | E / E |  |
| Stairs: Electrical | $100–$350 | $300–$1,500 | G / E |  |
| Stairs: Water intrusion / moisture | $300–$3,000 | $2,000–$10,000 | E / E |  |
| Stairs: Pests | $150–$600 | $500–$3,000 | E / E |  |
| Stairs: Smoke / CO detector | $20–$100 | $100–$400 | E / E |  |
| Stairs: Handrails | $75–$400 | $300–$1,500 | E / E | B15, B16 |
| Stairs: Steps | $150–$1,500 | $3,000–$10,000 | E / E |  |
| Stairs: Treads | $100–$600 | $300–$2,000 | E / E |  |
| Stairs: Risers | $100–$500 | $300–$1,500 | E / E |  |

### Hover ranges for rooms and areas

All are ballpark (E).

| Area | Ranges shown | Checked |
|---|---|---|
| The yard and property | Typical fixes $200–$1,500; Major work $1,000–$8,000 |  |
| Basement | Typical fixes $300–$3,000; Major work $3,000–$15,000 |  |
| Kitchen | Typical fixes $150–$1,000; Full remodel $10,000–$40,000 | B14 |
| Dining room | Typical fixes $100–$1,000; Major work $1,500–$8,000 |  |
| Living room | Typical fixes $100–$1,000; Major work $1,500–$8,000 |  |
| Bedroom | Typical fixes $100–$1,000; Major work $1,500–$8,000 |  |
| Bathroom | Typical fixes $150–$1,500; Full remodel $8,000–$25,000 | B13 |
| Attic | Typical fixes $300–$1,500; Major work $1,500–$5,000 |  |
| Stairs | Typical fixes $150–$1,500; Rebuild $3,000–$10,000 | B17 |

