# Financial & Operational Dashboard Analysis

Apply CRO-style analytical rigor to financial and operational dashboards. The same principles that govern conversion optimization — don't guess, discover from data; find the structural root cause; prioritize by evidence — apply directly to P&L analysis, cost structure review, and business strategy.

## The Core Shift

| Website CRO | Financial Dashboard CRO |
|-------------|------------------------|
| "Why don't visitors convert?" | "What does the data reveal that contradicts our assumptions?" |
| Exit survey, chat logs, analytics | P&L table, cost breakdown, margin distribution |
| O/CO for visitor objections | O/CO for strategic barriers |
| Hypothesis → A/B test | Hypothesis → business initiative |
| Conversion rate | Profit margin / revenue per unit |

The discipline is identical. The domain changes. The "customer" becomes the business unit, route, or product line.

---

## The 6-Step Dashboard Analysis Flow

### Step 1: Read Everything Before Concluding

Resist the urge to react to the first number you see. Map all available data first:

- **KPI cards** (header metrics): current state, simulated state, delta
- **Charts**: what comparison is being made? current vs. simulated, segment A vs. B, distribution shapes
- **Tables**: row-level detail that aggregates into charts
- **Annotations**: subtitle text, axis labels, and legends often contain the hypothesis being tested

**Critical check:** Is there a simulation or scenario in the data? (e.g., "値上げシミュレーション — price increase simulation") If so, identify what assumption the simulation tests and treat simulated values separately from current-state values.

### Step 2: Find the Structural Surprise

Every dashboard contains at least one finding that contradicts the team's operating assumptions. This is the most valuable discovery.

**Pattern to look for:**
- A segment that should be profitable is actually losing money
- A segment assumed to be low-value is actually the highest-margin
- A cost category is far larger than mentally estimated
- The simulation shows the intervention barely helps the root problem

**Example (KAM transportation dashboard):**
> Conventional assumption: "Our own vehicles are our core business."
> Data reality: Own vehicles = -1.9% margin (loss). Partner companies = +24.2% margin.
> Structural surprise: The "core business" is the loss center. The "support" business is the profit center.

This single discovery invalidates entire strategies that were built on the wrong premise. Do not skip this step.

### Step 3: Build the O/CO Table for Strategic Barriers

Use the same Objection/Counter-Objection framework, but reframe "objections" as **strategic barriers** — the reasons the business will resist the necessary change.

**Format:**

| # | Objection (Barrier) | Counter-Objection (Evidence-Based Response) | ICE Score |
|---|--------------------|--------------------------------------------|-----------|
| O1 | "We can't raise prices — customers will leave" | Margin distribution shows 4 vehicles remain unprofitable even after 7% raise → some customer loss is acceptable and profitable | I:10 C:9 E:7 = **8.7** |
| O2 | "We should grow by adding more own vehicles" | Own vehicles run at -1.9% margin. Adding vehicles scales the loss. | I:10 C:9 E:6 = **8.3** |

**ICE scoring for business initiatives:**
- **Impact** (1–10): How much does this move the target metric (profit, revenue, margin)?
- **Confidence** (1–10): How strong is the data backing? Is it measured or estimated?
- **Ease** (1–10): How achievable is implementation given organizational constraints?

Score = average of I, C, E. Prioritize top scores first.

### Step 4: Write Business Hypotheses

Same format as CRO hypotheses, applied to business changes:

> "If we [specific action], then [metric] will improve because [evidence from dashboard]."

**Examples:**
- "If we implement the 7% freight / 10% collection price increase for all customers, annual profit will increase from ¥31M to ¥80.6M because the simulation shows ¥49.5M incremental revenue flowing directly to profit."
- "If we grow partner-company revenue from ¥170M to ¥350M instead of adding own vehicles, margin on incremental revenue will be ~24% because partner-company cost structure is proven and fixed."
- "If we identify and exit or renegotiate the 4 unprofitable vehicles (which remain unprofitable even post-price-increase), fixed cost will decrease without revenue loss."

Each hypothesis must specify:
1. The action (what changes)
2. The metric (what you measure)
3. The evidence (why you expect this result)

### Step 5: Build a Quantified Roadmap

Translate hypotheses into a year-by-year plan with specific, measurable targets. Do not use vague language ("improve efficiency", "grow the business"). Every milestone must be a number.

**Roadmap structure:**

```
Year 0 (Current)   → Year 1             → Year 2             → Year 3
¥680M / 4.6%       → ¥800M / 12%        → ¥920M / 16%        → ¥1.05B / 20%
Own 44 / Partner   → Own 44 / Partner↑  → Own 40 / Partner↑↑ → Own 35 / Partner↑↑↑
```

For each year, specify:
- Revenue target
- Margin target
- The 2–3 initiatives required to hit those targets (from Step 3/4 hypotheses)
- What structural change is underway (e.g., asset-light shift, pricing model change)

### Step 6: Revise the Strategy When Data Contradicts the Premise

If analysis reveals that the original strategic direction was wrong (e.g., "expand own fleet" was the plan, but own fleet is losing money), explicitly state the reversal. Do not soften the finding.

**Template:**
> "Original direction: [what was assumed]. Data finding: [what the dashboard shows]. Revised direction: [the corrected strategy]."

Strategies built on wrong premises compound losses over time. The sooner the revision, the better.

---

## Common Mistakes in Dashboard Analysis

| Mistake | Why It Fails | Fix |
|---------|-------------|-----|
| **Reacting to the first big number** | You miss the structural insight hidden in segment-level data | Read the full dashboard before forming any conclusion |
| **Treating simulation as current reality** | Confuses aspirational scenario with actual performance | Clearly label current-state vs. simulated values throughout analysis |
| **Averaging over segments** | A profitable segment can hide a loss-making one | Always break down by segment, vehicle, route, or customer |
| **"Grow revenue" without checking margin** | Scaling a loss-making segment scales the loss | Confirm margin at the segment level before recommending growth |
| **Accepting the team's framing** | "Our core business" framing may be legacy assumption, not data | Let the margin data define what the real core business is |
| **Proposing solutions before naming the structural surprise** | Team debates tactics while missing the root cause | Always lead with the structural finding before recommendations |

---

## Dashboard Reading Checklist

Before generating any recommendations:

- [ ] Have you identified every KPI card and what it measures?
- [ ] Have you distinguished current-state data from simulated/projected data?
- [ ] Have you broken performance down by segment (own vs. partner, by vehicle, by route)?
- [ ] Have you identified the structural surprise — the finding that contradicts the operating assumption?
- [ ] Have you checked cost composition (what % is fixed vs. variable? what is the largest cost category)?
- [ ] Have you confirmed which segment is most profitable and which is least?
- [ ] Have you checked whether the proposed intervention (price increase, cost cut, etc.) addresses the root cause or just the symptom?

---

## Applied Example: KAM Transportation Cost Dashboard (2026)

**Dashboard:** 神奈川エアーメッセンジャー株式会社 — 運送原価ダッシュボード 2026年度試算（協力会社含む）

**Structural surprise discovered:**
- Own vehicles (44 units): revenue ¥510M, cost ¥520M → **margin -1.9% (loss)**
- Partner companies: revenue ¥170M, cost ¥130M → **margin +24.2% (profit)**
- All current profit (¥31M) comes entirely from partner companies
- Own vehicles are net negative

**Strategic revision:**
> Original assumption: grow own fleet → scale revenue.
> Data reality: growing own fleet scales losses. Growing partner-company volume grows profit at 24%.

**Top hypotheses (ICE-ranked):**

| Hypothesis | ICE |
|-----------|-----|
| Implement full price increase (7% freight / 10% collection) | 9.3 |
| Shift growth model from own-fleet expansion to partner-company network expansion | 8.7 |
| Identify and exit/renegotiate the 4 vehicles that remain unprofitable post-price-increase | 7.7 |
| Grow partner-company revenue from ¥170M to ¥350M | 8.0 |

**Cost structure finding:**
- Labor = 56% of own-vehicle cost (largest fixed cost; revenue growth required, not headcount cuts)
- Fuel = 13%, Lease = 10% (semi-variable; manageable)

**10-billion-yen roadmap (revised):**

| Year | Revenue | Margin | Key Initiative |
|------|---------|--------|----------------|
| 2026 | ¥680M | 4.6% | Baseline |
| 2027 | ¥800M | 12% | Price increase + exit 4 unprofitable vehicles |
| 2028 | ¥920M | 16% | Partner company revenue ¥400M |
| 2029 | ¥1.05B | 20% | Partner company revenue ¥500M+ / own fleet specialized to high-margin routes |
