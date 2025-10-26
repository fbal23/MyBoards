# Improving the McKinsey Negotiation Framework

**Purpose:** Enhance the McKinsey stakeholder analysis methodology for modern board negotiations

**Author:** BoardAI Strategy Team
**Date:** October 26, 2025

---

## Executive Summary

The McKinsey framework (Allas & Georgiades, 2001) is fundamentally sound but needs 7 key improvements for modern board contexts:

1. **Add a 4th dimension: "Flexibility"** (likelihood to change position)
2. **Include temporal dynamics** (how positions evolve over time)
3. **Add coalition analysis as Tool 6**
4. **Expand Tool 5 to include multi-party bargaining**
5. **Add confidence scoring to all assessments**
6. **Include issue interdependencies**
7. **Add "BATNA analysis" as Tool 7**

---

## Current McKinsey Framework (Review)

### Three Dimensions (0-100 scales)
1. **Position:** Where stakeholder stands on the issue
2. **Salience:** How important the issue is to them
3. **Clout:** How much power they have to influence the outcome

### Five Tools
1. **Outcome Continuum:** Predict weighted average outcome
2. **Stability Analysis:** Assess if outcome will stick
3. **Stakeholder Classification:** Map allies/enemies
4. **Negotiation Landscape:** Prioritize engagement (Shapers/Influencers/Followers)
5. **Relationship Analysis:** Find bargaining chips (dyadic)

---

## IMPROVEMENT 1: Add 4th Dimension - "Flexibility"

### The Gap

**Current framework assumes positions are fixed.**

In reality:
- Some stakeholders are "dug in" (position 20, will never move)
- Others are "persuadable" (position 45, could go to 60 or 30)
- Framework doesn't distinguish between these

### Example Problem

```
McKinsey shows:
  CFO: Position = 50, Salience = 80, Clout = 90
  Board Member X: Position = 50, Salience = 80, Clout = 90

They look identical, but:
  CFO: Data-driven, will shift position if shown compelling ROI model
  Board Member X: Ideological, will never move regardless of evidence

You should focus effort on CFO, not Board Member X.
Current framework doesn't tell you this.
```

### Proposed Solution: Add "Flexibility" Dimension

**Flexibility (0-100 scale):**
- **100 = Highly flexible:** "I could be convinced either way"
- **50 = Moderately flexible:** "I have a view but I'm open to discussion"
- **0 = Completely rigid:** "This is non-negotiable for me"

**Assessment criteria:**
1. **Historical behavior:** Has this person changed positions on past issues?
2. **Stated reasoning:** Is their position based on principles (rigid) or analysis (flexible)?
3. **Personality:** Are they pragmatic or ideological?
4. **Incentive structure:** Do they have room to maneuver (flexible) or are they constrained (rigid)?

### New Analysis: "Persuadability Matrix"

**Tool 1B: Persuadability Matrix**

```
2x2 Matrix:
  X-axis: Flexibility (0-100)
  Y-axis: Distance from your position (0-100)

Quadrants:

1. Far + Flexible (upper right):
   → "HIGH PRIORITY TARGETS"
   → They disagree but could be convinced
   → Worth heavy lobbying effort

2. Far + Rigid (upper left):
   → "LOST CAUSES"
   → They disagree and won't budge
   → Don't waste time, find ways to neutralize their clout

3. Near + Flexible (lower right):
   → "NATURAL ALLIES"
   → Already close to you and open-minded
   → Easy wins, bring them fully on board

4. Near + Rigid (lower left):
   → "LOCKED-IN SUPPORTERS"
   → Already agree and won't move
   → Use them to influence others
```

### Example Application

```
Issue: $10B AI Investment

Stakeholder Analysis with Flexibility:

CFO Amy Hood:
  Position: 50 (neutral)
  Salience: 85
  Clout: 90
  Flexibility: 75 ← NEW
  Assessment: "Data-driven, responds to financial modeling"
  Strategy: HIGH PRIORITY - Worth 10 hours of prep on ROI model

Audit Committee Chair:
  Position: 30 (opposed)
  Salience: 70
  Clout: 75
  Flexibility: 25 ← NEW
  Assessment: "Risk-averse by personality, rarely changes view"
  Strategy: LOW PRIORITY - Instead, reduce their clout by building coalition without them

Board Member (Tech Background):
  Position: 85 (supportive)
  Salience: 90
  Clout: 60
  Flexibility: 80 ← NEW
  Assessment: "Pro-AI but wants to see governance"
  Strategy: EASY WIN - Add governance provisions, lock in support

Old McKinsey: All three look different, but no guidance on where to focus
New McKinsey: Clear prioritization - Focus on CFO (far but flexible)
```

### Integration with Existing Tools

**Updated Tool 2: Stability Analysis**
```
Add flexibility dimension to quadrants:

Far from outcome + High power + LOW FLEXIBILITY = "Immovable obstacles"
Far from outcome + High power + HIGH FLEXIBILITY = "Solvable challenges"

Different strategies for each.
```

---

## IMPROVEMENT 2: Add Temporal Dynamics

### The Gap

**Current framework is a single snapshot in time.**

Board negotiations unfold over weeks/months:
- Positions shift as new information emerges
- Salience changes based on other events
- Coalitions form and dissolve

McKinsey 2001 article doesn't account for this.

### Example Problem

```
Month 1 Analysis:
  CFO: Position = 40 (opposed)
  Strategy: Unlikely to win this negotiation

Month 3 Reality:
  CFO: Position = 60 (supportive)
  Why? Competitor announced major AI investment, changed her view

McKinsey framework didn't capture:
  - What could change her mind
  - When to push vs. wait
  - Momentum indicators
```

### Proposed Solution: Temporal Tracking

**New Tool 1C: Position Trajectory Analysis**

For each key stakeholder, track:

1. **Current position** (standard McKinsey)
2. **Position 3 months ago** (historical)
3. **Trend direction:** ⬆️ Moving toward you, ➡️ Stable, ⬇️ Moving away
4. **Velocity:** How fast are they moving? (points per month)
5. **Predicted position in 3 months** (extrapolation + scenario analysis)

**Visualization:**

```
Position Trajectory: CFO Amy Hood on AI Investment

100 |                                              ╱ Predicted (if momentum continues)
    |                                          ╱
 80 |                                      ╱
    |                                  ╱
 60 |                              ● Current (Month 3)
    |                          ╱
 40 |                  ● Month 2
    |              ╱
 20 |      ● Month 1
    |  ╱
  0 |●  Start (6 months ago)
    +----------------------------------------------------
      Jul    Aug    Sep    Oct    Nov    Dec    Jan

Velocity: +10 points/month
Trigger events:
  - Month 1→2: Saw competitor AI revenue growth (+15 points)
  - Month 2→3: OpenAI demo convinced her of tech viability (+5 points)

Insight: Momentum is positive. Wait 1 more month for better position.
Action: Don't force vote now. Let trend continue.
```

**New Metrics:**

- **Momentum Score:** Σ(position change × recency weight)
  - Positive = Moving toward you
  - Negative = Moving away
  - Zero = Stable

- **Tipping Point Proximity:** How close is stakeholder to changing sides?
  - Near tipping point (position 45-55) → Small push could flip them
  - Far from tipping (position 20 or 80) → Requires major event

### Example Application

```
Issue: Executive Compensation Increase

Stakeholder: Independent Director #3
  Current position: 48 (slightly opposed)
  3 months ago: 55 (slightly supportive)
  Trajectory: ⬇️ -7 points (moving away from approval)
  Trigger: News article about CEO pay inequality

Strategy Decision:
  Old McKinsey: "Position = 48, close to neutral, lobby them"
  New McKinsey: "Negative momentum, they're hardening. Address root cause (inequality concerns) before lobbying"

Action:
  1. Don't lobby yet (will backfire)
  2. First: Add equity/performance components to address inequality optics
  3. Then: Approach when position stabilizes
```

### Integration Point

**Updated Tool 2: Stability Analysis**
- Add vector arrows showing trajectory direction
- Unstable outcomes show which stakeholders are in motion
- Predict stability not just today, but in 1-2 months

---

## IMPROVEMENT 3: Add Coalition Analysis (Tool 6)

### The Gap

**Current Tool 5 (Relationship Analysis) only does pairwise (1-on-1) analysis.**

Board negotiations involve coalitions:
- "Progressive bloc" (3 board members who always vote together)
- "Financial conservatives" (CFO + institutional investors + audit committee)
- "Management team" (CEO + executives)

McKinsey doesn't have a tool to map these groups.

### Example Problem

```
You lobby CFO individually (Tool 5: Relationship Analysis)
CFO says: "I'm personally supportive, but my audit committee allies won't go for it"

You didn't know:
  - CFO is part of a 4-person coalition
  - Coalition has internal consensus rule
  - Getting CFO alone isn't enough

Result: Wasted effort lobbying wrong person in wrong way
```

### Proposed Solution: Tool 6 - Coalition Mapping

**Tool 6: Coalition Analysis**

**Step 1: Identify coalitions**

Methods:
1. **Voting history:** Who votes together consistently?
2. **Meeting behavior:** Who sits together, defers to each other, uses "we" language?
3. **Background alignment:** Similar backgrounds/incentives/values
4. **Explicit alliances:** Publicly stated partnerships

**Step 2: Characterize each coalition**

For each coalition, assess:
- **Members:** Who's in it?
- **Leader:** Who speaks for the group?
- **Cohesion (0-100):** How tightly do they vote together?
- **Collective clout:** Sum of individual clout scores
- **Core issue:** What binds them together?
- **Voting power:** % of total votes
- **Decision rule:** Unanimous? Majority? Leader decides?

**Step 3: Map coalition positions**

```
Coalition Landscape:

Coalition 1: "AI Maximalists"
  Members: CEO Satya Nadella, Board Member Reid Hoffman, CTO Kevin Scott
  Leader: Satya Nadella
  Cohesion: 95 (almost always vote together)
  Position on AI Investment: 90 (strongly supportive)
  Voting power: 25% of board
  Core issue: "Technology leadership"

Coalition 2: "Financial Discipline"
  Members: CFO Amy Hood, Audit Chair, Institutional Investor Rep, Treasury
  Leader: CFO Amy Hood
  Cohesion: 75 (usually align, occasionally split)
  Position on AI Investment: 45 (cautious)
  Voting power: 33% of board
  Core issue: "ROI and risk management"

Coalition 3: "Swing Voters"
  Members: Board Chair John Thompson, 2 independent directors, ESG committee
  Leader: Board Chair (but loose coalition)
  Cohesion: 40 (often split, case-by-case)
  Position on AI Investment: 55 (slight lean toward approval)
  Voting power: 42% of board
  Core issue: "Balanced growth"
```

**Step 4: Coalition Strategy Matrix**

```
2x2 Matrix:
  X-axis: Coalition's position (supportive vs. opposed)
  Y-axis: Coalition cohesion (tight vs. loose)

Quadrants:

1. Supportive + Tight Cohesion:
   → "LOCKED-IN ALLIES"
   → Don't need to convince, use them to recruit others
   → Strategy: Activate them to lobby swing voters

2. Opposed + Tight Cohesion:
   → "UNIFIED OPPOSITION"
   → Can't split them apart, must neutralize collectively
   → Strategy: Find issues to trade or reduce their clout

3. Supportive + Loose Cohesion:
   → "POTENTIAL ALLIES"
   → Reinforce their unity, prevent defections
   → Strategy: Give them reasons to stay together

4. Opposed + Loose Cohesion:
   → "SPLITTABLE BLOC"
   → Target the most persuadable member to break coalition
   → Strategy: Peel off 1-2 members, fracture the group
```

### Example Application

```
Issue: $10B AI Investment

Coalition Analysis:

AI Maximalists:
  Position: 90, Cohesion: 95, Voting power: 25%
  Strategy: LOCKED-IN ALLIES
    - Have CEO Satya lobby swing voters
    - Use Reid Hoffman (tech credibility) to speak to financial coalition

Financial Discipline:
  Position: 45, Cohesion: 75, Voting power: 33%
  Strategy: SPLITTABLE BLOC
    - Target CFO Amy Hood (coalition leader, but Flexibility = 75)
    - If we flip CFO, 1-2 others will follow
    - Cohesion of 75 means not all members are rigid
    - Focus: Build ROI case that CFO can sell to her coalition

Swing Voters:
  Position: 55, Cohesion: 40, Voting power: 42%
  Strategy: REINFORCE LEAN TOWARD SUPPORT
    - They're already leaning our way (55)
    - Low cohesion means individual outreach works
    - Prevent "Financial Discipline" from pulling them away
    - Assign: Each AI Maximalist adopts 1-2 swing voters for 1-on-1s

Winning Path:
  1. Lock in AI Maximalists (25%) ✓ Already done
  2. Convert Financial Discipline leader (CFO) → Brings 15-20% more
  3. Hold Swing Voters (42%) → Already leaning supportive
  4. Total: 25% + 18% + 42% = 85% approval (landslide)

Old McKinsey: Treat each of 12 board members individually
New McKinsey: Treat 3 coalitions strategically, focus on coalition leaders
```

### Advanced: Coalition Stability Prediction

**When will a coalition split?**

Indicators:
- **Internal position variance:** Members have different positions on this issue
- **External pressure:** Events that pull members in different directions
- **Leadership change:** Coalition leader leaves/weakens

```
Financial Discipline Coalition Stability:

Current cohesion: 75

Stress test scenarios:
  1. If CFO flips position: Cohesion drops to 45 (likely splits)
  2. If Audit Chair exits board: Cohesion drops to 60 (weakens but holds)
  3. If AI investment shows strong early ROI: Cohesion drops to 50 (fractures)

Strategy: Create conditions for scenario #3
  - Phase investment: Get small approval now
  - Show quick wins (6 months)
  - Return for larger approval when coalition has fractured
```

---

## IMPROVEMENT 4: Expand Tool 5 to Multi-Party Bargaining

### The Gap

**Current Tool 5 only does dyadic (you vs. one other stakeholder) bargaining chip analysis.**

Board negotiations often involve 3+ party trades:
- "I'll support your cybersecurity budget if you support my AI investment, and we'll both support Board Member X's ESG initiative"

McKinsey doesn't model these multi-party deals.

### Example Problem

```
Dyadic bargaining (McKinsey Tool 5):
  You ↔ CFO:
    - You have "Green subsidies" (low salience for you, high for CFO)
    - Trade: You give up green subsidies, CFO supports higher tariffs

But you miss:
  Three-way trade:
    - You give CFO: Green subsidies
    - CFO gives Regulator: Enhanced audits
    - Regulator gives You: Higher tariffs

  Result: Everyone wins, but you'd never find this with pairwise analysis
```

### Proposed Solution: Multi-Party Bargaining Matrix

**Enhanced Tool 5: Multi-Party Relationship Analysis**

**Step 1: Build "Issue Trading Matrix"**

```
Matrix: Who values what?

                   Your    CFO    Regulator   Board     Union
                 Salience Salience Salience  Chair   Salience
Issue A: Tariffs    90      40        85       30       60
Issue B: Green $    20      85        60       70       40
Issue C: Audits     30      55        90       60       20
Issue D: Jobs       25      30        20       40       95
Issue E: Timeline   70      60        50       80       35
```

**Step 2: Find Multi-Party Trades (Cycles)**

Look for "trading cycles":
```
Cycle 1: Three-way trade
  You give up:  Issue B (Green $) → CFO receives (high value to her)
  CFO gives up: Issue C (Audits) → Regulator receives (high value to them)
  Regulator gives up: Issue A (Tariff flexibility) → You receive (high value to you)

  Net: Everyone trades something they don't care about for something they do
  Win-win-win
```

**Step 3: Optimization Algorithm**

Find the trade that maximizes total value created:

```
Maximize: Σ(Value received - Value given up) across all parties

Subject to:
  - No party can be net negative (everyone must win)
  - Trades must be feasible (stakeholders must agree)
  - Consider clout (high-clout players can demand more)

Algorithm finds: "What's the Pareto-optimal deal?"
```

### Example Application

```
Issue: Utility Privatization Negotiation

Stakeholders:
  - Power Company (you)
  - Regulator
  - Treasury
  - Labor Union
  - Environmental Group

Issues:
  A. End-user tariffs
  B. Wholesale market structure
  C. Forced divestitures
  D. Green subsidies
  E. Job protections
  F. Timeline

Dyadic analysis (old McKinsey):
  You ↔ Regulator:
    Best trade: You accept tariff cuts (-20 value to you)
                Regulator eases divestitures (+25 value to you)
    Net: +5 value

Multi-party analysis (improved McKinsey):
  Four-way trade:
    1. You → Regulator: Accept enhanced oversight on Issue B (-10 value)
    2. Regulator → Treasury: Support faster timeline on Issue F (-5 value)
    3. Treasury → Union: Fund job transition program on Issue E (-15 value)
    4. Union → You: Accept market structure on Issue B (+30 value)

  Net value to you: -10 + 30 = +20 value (4x better than dyadic)

  All parties net positive:
    You: +20
    Regulator: +10 (got oversight)
    Treasury: +5 (faster timeline)
    Union: +15 (job protections)

  Old approach: Missed this opportunity entirely
```

### Implementation

**Tool 5B: Multi-Party Bargaining Optimizer**

Inputs:
- Stakeholders (list)
- Issues (list)
- Salience matrix (stakeholder × issue)
- Position matrix (stakeholder × issue)
- Clout scores (stakeholder)

Algorithm:
1. Identify all possible 2-party trades
2. Identify all possible 3-party cycles
3. Identify all possible 4+ party cycles
4. Rank by total value created
5. Filter for feasibility (will all parties agree?)
6. Present top 5 trading packages

Output:
```
TOP TRADING PACKAGES:

Package 1: Four-party cycle (You, CFO, Regulator, Union)
  Total value created: +50
  Your net: +20
  Feasibility: 85% (all parties likely to agree)

  Trades:
    - You give CFO: Green subsidies (salience 20) → CFO receives (salience 85)
    - CFO gives Regulator: Enhanced audits (sal 55) → Reg receives (sal 90)
    - Regulator gives Union: Job protections (sal 20) → Union receives (sal 95)
    - Union gives You: Market structure support (sal 40) → You receive (sal 90)

  How to execute:
    1. Approach CFO first (she's pivot point)
    2. Frame as "package deal" (all-or-nothing)
    3. Get tentative agreement from all four before formalizing
    4. Present to board as unified recommendation

Package 2: Three-party trade (You, Treasury, Regulator)
  Total value created: +35
  Your net: +15
  Feasibility: 70%

  [Details...]
```

---

## IMPROVEMENT 5: Add Confidence Scoring

### The Gap

**All McKinsey numbers (Position, Salience, Clout) are treated as certain.**

In reality, you have different levels of confidence:
- CFO's position: 90% confident (she stated it clearly in meeting)
- Board Member X's position: 40% confident (we're guessing based on past behavior)

Framework doesn't distinguish, leading to false precision.

### Example Problem

```
McKinsey Analysis shows:
  Predicted outcome: 62.5

But this is computed from:
  CFO position: 55 (confidence: 90%)
  Board Member position: 70 (confidence: 30% - total guess)

Is 62.5 a reliable prediction? Framework doesn't tell you.
```

### Proposed Solution: Bayesian Confidence Intervals

**Every assessment includes confidence score:**

```
CFO Position on AI Investment:
  Point estimate: 55
  Confidence: 85%
  Evidence:
    - Stated in board meeting: "I'm cautiously supportive" (weight: 0.5)
    - Allocated budget for due diligence (weight: 0.3)
    - Historical pattern on large investments (weight: 0.2)
  Confidence interval: [48, 62] (90% confidence)

Board Member X Position:
  Point estimate: 70
  Confidence: 35%
  Evidence:
    - No public statement (weight: 0.0)
    - Background suggests tech-friendly (weight: 0.5)
    - Voted yes on similar issue 2 years ago (weight: 0.5)
  Confidence interval: [50, 90] (90% confidence) ← Wide range!
```

**Updated Tool 1: Outcome Continuum with Uncertainty**

```
Old output:
  Predicted outcome: 62.5

New output:
  Predicted outcome: 62.5
  Confidence interval: [55, 70] (80% confidence)

  Interpretation:
    - Most likely outcome: 62-63
    - Possible range: 55-70 (if low-confidence estimates are wrong)
    - Uncertainty driven by: Board Member X (need more intel)

  Action:
    - HIGH PRIORITY: Gather more data on Board Member X
    - Don't rely on 62.5 as certain - plan for range of 55-70
```

**Confidence-Weighted Decisions:**

```
Decision: Should we push for a vote now or wait?

Old McKinsey:
  Predicted outcome: 62.5
  Your target: 70
  Gap: -7.5
  Decision: Wait, not close enough

New McKinsey with confidence:
  Expected outcome: 62.5
  80% confidence interval: [55, 70]
  20% chance outcome is ≥70

  Monte Carlo simulation (1000 runs):
    - 18% of scenarios: Outcome ≥70 (you win)
    - 65% of scenarios: Outcome 58-68 (close loss)
    - 17% of scenarios: Outcome ≤55 (bad loss)

  Expected value analysis:
    - Vote now: 18% chance of win × $10M value = $1.8M expected
    - Wait 1 month: Gather more intel, reduce uncertainty
                    Predicted: 25% chance of win × $10M = $2.5M expected

  Decision: WAIT - value of information is high
```

### Confidence Sources

**How to assign confidence:**

High confidence (80-100%):
- Direct quotes from stakeholder
- Recent voting record on this exact issue
- Formal written position

Medium confidence (50-79%):
- Inferred from public statements
- Historical pattern on similar issues
- Second-hand reports ("I heard they think...")

Low confidence (20-49%):
- Extrapolation from background
- Analogies to other stakeholders
- Educated guessing

Very low confidence (0-19%):
- Pure speculation
- No data

**Rule: Flag any analysis where >30% of stakeholders have <60% confidence**
→ Tells you: "Go gather more data before making decisions"

---

## IMPROVEMENT 6: Model Issue Interdependencies

### The Gap

**McKinsey treats each issue independently.**

Board issues are often linked:
- "I'll support AI investment IF you support cybersecurity budget"
- "Compensation increase makes sense IF we hit revenue targets"
- "I can't support tariff cuts AND job reductions simultaneously"

Current framework misses these conditional relationships.

### Example Problem

```
Issue A: AI Investment
  CFO position: 50

Issue B: Cost Cutting Program
  CFO position: 80

Looks like CFO is neutral on AI, supportive on cost cutting.

But reality:
  CFO position: "I support AI investment ONLY IF we also cut costs elsewhere"

  These aren't independent:
    - If cost cutting passes: CFO moves to 75 on AI (now supportive)
    - If cost cutting fails: CFO moves to 30 on AI (now opposed)

McKinsey framework misses this conditional logic.
```

### Proposed Solution: Issue Dependency Graph

**Map how issues affect each other:**

```
Issue Dependencies:

AI Investment → depends on → Cost Cutting
  Relationship: "Conditional support"
  CFO: "I'll approve AI IF we cut costs"
  Effect: Cost cutting approval shifts CFO +25 points on AI

Compensation Increase → depends on → Revenue Targets
  Relationship: "Performance-based"
  Comp Committee: "CEO gets raise IF we hit $200B revenue"
  Effect: Meeting targets shifts committee +40 points on comp

Green Investment ← conflicts with → Cost Cutting
  Relationship: "Budget competition"
  Treasury: "Can't afford both"
  Effect: Green approval shifts Treasury -20 points on cost cutting
```

**Dependency Matrix:**

```
                 Affects →
               AI  Comp  Green  Costs  Jobs
            ┌────┬─────┬──────┬──────┬─────┐
AI          │  0 │  +5 │  -10 │  -15 │  +10│
Comp        │  0 │   0 │   +5 │  -20 │   0 │
Green       │-10 │   0 │    0 │  -30 │  +5 │
Costs       │+25 │ -20 │  -30 │    0 │ -40 │
Jobs        │+10 │   0 │   +5 │  -40 │   0 │
            └────┴─────┴──────┴──────┴─────┘

Reading: "If Costs passes, AI position shifts +25 points"
```

**Sequencing Strategy:**

```
Old McKinsey: Negotiate each issue independently
  - AI investment: Predicted outcome = 55
  - Cost cutting: Predicted outcome = 70

New McKinsey: Optimize issue sequence
  - Sequence 1: Vote on AI first, then Costs
    → AI likely fails (55 < 60 threshold)
    → Costs passes (70)
    → Total value: $5B (just cost savings)

  - Sequence 2: Vote on Costs first, then AI
    → Costs passes (70)
    → Cost passage shifts AI outcome: 55 + 25 = 80
    → AI now passes (80 > 60 threshold)
    → Total value: $15B (cost savings + AI upside)

Insight: Sequence matters! Vote on Costs first.
```

**Bundle Strategy:**

```
Issue Bundling Analysis:

Bundle A: "Growth Package"
  - AI Investment
  - Green Subsidies
  - Job Protections

  Effects:
    - Green + Jobs addresses social concerns
    - Makes AI more palatable to ESG committee
    - CFO: Shifts from 50 → 65 on AI (in bundle context)

  Predicted outcome: 68 (passes as bundle)
  vs. separate votes: AI = 55 (fails), Green = 60, Jobs = 75

Bundle B: "Efficiency Package"
  - AI Investment
  - Cost Cutting
  - Tariff Reductions

  Effects:
    - Cost cutting + Tariffs fund AI
    - Fiscally responsible narrative
    - CFO: Shifts from 50 → 75 on AI (in bundle)

  Predicted outcome: 72 (strong passage)

Recommendation: Pursue Bundle B (better outcome)
```

### Implementation

**Enhanced Tool 1: Multi-Issue Outcome Prediction**

Input:
- Issues (list)
- Dependency matrix (issue × issue effects)
- Stakeholder positions on each issue
- Proposed voting sequence or bundle

Algorithm:
1. Compute baseline outcome for each issue (standard McKinsey)
2. Apply dependency effects based on sequence/bundle
3. Recalculate outcomes with effects
4. Iterate until stable (some effects are circular)
5. Compare different sequences/bundles

Output:
```
SCENARIO ANALYSIS: AI Investment

Scenario 1: AI voted alone (current plan)
  Outcome: 55 (fails)

Scenario 2: AI voted after cost cutting passes
  Cost cutting outcome: 70 (passes)
  AI outcome: 55 + 25 (cost cutting effect) = 80 (passes)
  Recommendation: CHANGE SEQUENCE

Scenario 3: AI bundled with green subsidies
  Bundle outcome: 68 (passes)
  But: Compromises AI scope to accommodate green concerns
  Recommendation: VIABLE BUT SUBOPTIMAL

Best strategy: Scenario 2 (sequence change)
  - Pass cost cutting first (likely anyway)
  - Then propose AI (now supported by fiscal responsibility)
```

---

## IMPROVEMENT 7: Add BATNA Analysis (Tool 7)

### The Gap

**McKinsey focuses on reaching a deal but doesn't analyze your fallback options.**

Negotiation theory (Fisher & Ury) emphasizes:
- **BATNA:** Best Alternative to a Negotiated Agreement
- "What happens if this negotiation fails?"
- Strong BATNA = More negotiating power

McKinsey doesn't have a tool for this.

### Example Problem

```
Issue: Board approving CEO compensation increase

McKinsey analysis: Predicted outcome = 55 (marginal failure)

But what's your BATNA if board votes NO?

Option A: CEO stays at current comp (weak BATNA)
  - CEO is unhappy but won't leave
  - Your negotiating power: LOW
  - Should accept any deal >55

Option B: CEO has competing offer, will leave if no raise (strong BATNA for CEO)
  - CEO replacement cost: $50M+
  - Your negotiating power: HIGH
  - Can push harder, board will cave

McKinsey doesn't tell you which situation you're in.
```

### Proposed Solution: Tool 7 - BATNA Matrix

**For each key decision-maker, assess:**

1. **Your BATNA if deal fails**
   - What's your fallback plan?
   - How valuable is it? (0-100 scale)
   - How credible is it? (can you actually execute?)

2. **Their BATNA if deal fails**
   - What's their fallback?
   - How valuable to them?
   - How credible?

3. **Relative BATNA strength**
   - If your BATNA is stronger: You have leverage (can walk away)
   - If their BATNA is stronger: They have leverage (you need deal more)

**BATNA Comparison Matrix:**

```
Issue: $10B AI Investment

Your BATNA if board rejects:
  Option A: Smaller $5B investment (can do without board approval)
    Value: 60 (half the impact)
    Credibility: 90% (definitely feasible)

  Option B: Partnership instead of ownership
    Value: 40 (less strategic control)
    Credibility: 70%

  Best BATNA: Option A (value 60, credibility 90%)

CFO's BATNA if she blocks the deal:
  Option A: Status quo (no AI investment)
    Value to her: 50 (avoids risk, but misses upside)
    Credibility: 100%

  Option B: Smaller pilot program
    Value to her: 55 (reduces risk, tests concept)
    Credibility: 80%

  CFO's Best BATNA: Option B (value 55, credibility 80%)

Relative Power Analysis:
  Your BATNA value: 60
  CFO's BATNA value: 55

  You have slight advantage: You're less desperate for deal

  Negotiating implication:
    - You can credibly threaten: "If board won't approve $10B, I'll do $5B myself"
    - This raises CFO's perceived risk: "If we say no, he does it anyway without oversight"
    - Strategy: Emphasize your $5B BATNA to increase her fear of loss of control
    - Makes her more likely to approve $10B with governance (better than $5B without)
```

**BATNA Power Matrix:**

```
2x2 Matrix:
  X-axis: Your BATNA strength (weak to strong)
  Y-axis: Their BATNA strength (weak to strong)

Quadrants:

1. You weak, They weak:
   → "MUTUAL DEPENDENCE"
   → Both need the deal
   → Focus on creating value (expand pie)
   → Negotiation style: Collaborative

2. You strong, They weak:
   → "YOUR LEVERAGE"
   → You can walk away, they can't
   → Push for favorable terms
   → Negotiation style: Assertive

3. You weak, They strong:
   → "THEIR LEVERAGE"
   → They can walk away, you can't
   → Accept reasonable offer
   → Negotiation style: Accommodating

4. You strong, They strong:
   → "STALEMATE RISK"
   → Both can walk away
   → Either creative solution or no deal
   → Negotiation style: Problem-solving
```

### Advanced: BATNA Improvement Strategy

**Don't just analyze BATNA - improve it:**

```
Current situation:
  Your BATNA: 60 (do $5B investment alone)
  CFO's BATNA: 55 (status quo or pilot)
  Power balance: Slight advantage to you

BATNA improvement moves:

Option 1: Strengthen your BATNA
  - Secure external funding for $5B (no board approval needed)
  - Announce this publicly: "We're doing AI either way"
  - New BATNA value: 65 (more credible threat)
  - Effect: Increases board urgency to approve and maintain oversight

Option 2: Weaken their BATNA
  - Show that "status quo" is actually declining position
  - Present data: "Competitors are pulling ahead, status quo = falling behind"
  - Reframe: Status quo value from 50 → 30 (in their mind)
  - Effect: Makes $10B investment look better by comparison

Option 3: Create mutual BATNA (best outcome)
  - Propose: "We could do this as industry consortium"
  - New shared BATNA: Value 70 (better than either party alone)
  - Effect: Changes negotiation from competitive to collaborative

Recommended: Option 3 (collaborative BATNA)
  - Present to CFO: "Together we can do $10B well"
  - "Apart, we each have weaker options"
  - "Let's align on governance and do this right"
```

### Integration with Other Tools

**Tool 1 (Outcome Continuum) + Tool 7 (BATNA):**
```
Predicted outcome: 55 (marginal failure)
Your BATNA: 60 (better than predicted deal!)

Decision: DON'T NEGOTIATE
  - Predicted deal (55) is worse than your fallback (60)
  - Either:
    a) Improve predicted outcome to >60, or
    b) Walk away and execute BATNA

Old McKinsey: "Outcome is 55, let's negotiate to improve it"
New McKinsey: "Outcome is 55, BATNA is 60, reject deal and walk away"
```

**Tool 5 (Relationship Analysis) + Tool 7 (BATNA):**
```
Bargaining chips to trade with CFO:
  - Issue X (low salience to you, high to CFO)

But first check BATNA:
  - If your BATNA is strong, DON'T trade Issue X
  - You can get deal without concessions
  - Only trade if you need the deal (weak BATNA)

Old McKinsey: Trade Issue X to get CFO support
New McKinsey: Don't trade (you have strong BATNA, she has weak BATNA)
```

---

## Summary: Complete Improved Framework

### NEW McKinsey Framework (Enhanced)

**Four Dimensions (not three):**
1. **Position** (0-100): Where stakeholder stands
2. **Salience** (0-100): Importance of issue to them
3. **Clout** (0-100): Power to influence outcome
4. **Flexibility** (0-100): ← NEW - Likelihood to change position

**Seven Tools (not five):**
1. **Outcome Continuum:** Predict weighted average outcome
   - Enhanced: Include confidence intervals
   - Enhanced: Account for issue dependencies
2. **Stability Analysis:** Assess if outcome will stick
   - Enhanced: Add position trajectories (temporal dynamics)
   - Enhanced: Factor in flexibility dimension
3. **Stakeholder Classification:** Map allies/enemies
   - Enhanced: Include confidence scores on classifications
4. **Negotiation Landscape:** Prioritize engagement
   - Enhanced: Add "Persuadability Matrix" (flexibility-based)
5. **Relationship Analysis:** Find bargaining chips
   - Enhanced: Multi-party bargaining (not just dyadic)
   - Enhanced: Issue bundling optimization
6. **Coalition Mapping:** ← NEW - Identify and analyze voting blocs
7. **BATNA Analysis:** ← NEW - Assess alternatives to agreement

---

## Implementation Checklist

**To implement improved McKinsey framework:**

Phase 1: Data Collection (Enhanced)
- [ ] Gather Position, Salience, Clout (original)
- [ ] **NEW:** Assess Flexibility for each stakeholder
- [ ] **NEW:** Assign confidence scores to each assessment
- [ ] **NEW:** Track position history (last 3-6 months)
- [ ] **NEW:** Map issue dependencies
- [ ] **NEW:** Identify coalitions (voting patterns, backgrounds)
- [ ] **NEW:** Document BATNAs (yours and theirs)

Phase 2: Analysis (Enhanced Tools)
- [ ] Tool 1: Outcome Continuum with confidence intervals
- [ ] Tool 1B: Position Trajectory Analysis (temporal)
- [ ] Tool 1C: Multi-Issue Scenario Analysis (dependencies)
- [ ] Tool 2: Stability Analysis (enhanced with flexibility)
- [ ] Tool 3: Stakeholder Classification (with confidence)
- [ ] Tool 4: Negotiation Landscape + Persuadability Matrix
- [ ] Tool 5: Multi-Party Bargaining Optimization
- [ ] **NEW Tool 6:** Coalition Mapping and Strategy
- [ ] **NEW Tool 7:** BATNA Comparison Matrix

Phase 3: Strategy (Enhanced Decision-Making)
- [ ] Prioritize: Focus on high-flexibility, high-clout stakeholders
- [ ] Sequence: Optimize issue voting order (dependency analysis)
- [ ] Bundle: Group issues for strategic effect
- [ ] Coalition: Target coalition leaders (not individuals)
- [ ] Multi-party trades: Find 3-4 party trading cycles
- [ ] Timing: Use trajectory analysis to know when to push
- [ ] BATNA: Improve yours, weaken theirs, or create mutual

Phase 4: Execution
- [ ] Monitor position changes in real-time
- [ ] Update confidence scores as new data arrives
- [ ] Track coalition cohesion (watch for fracturing)
- [ ] Re-run analysis if major changes occur
- [ ] Document outcomes for organizational learning

---

## Comparison: Old vs. New McKinsey

| Aspect | Original McKinsey | Improved McKinsey | Impact |
|--------|------------------|-------------------|---------|
| **Dimensions** | 3 (Position, Salience, Clout) | 4 (+Flexibility) | Focus effort on persuadable stakeholders |
| **Temporal** | Static snapshot | Dynamic trajectories | Know when to push vs. wait |
| **Relationships** | Dyadic (pairwise) | Multi-party + coalitions | Find 3-4 party win-win trades |
| **Uncertainty** | False precision | Confidence intervals | Know where to gather more intel |
| **Issues** | Independent | Interdependent (bundling/sequencing) | Optimize voting order and packages |
| **Alternatives** | Not considered | BATNA analysis | Know when to walk away |
| **Tools** | 5 tools | 7 tools | More complete strategic view |
| **Time required** | 2.5 days | 3.5 days (manual) OR 3 hours (with GraphRAG automation) | Higher upfront cost, better outcomes |

---

## Conclusion

The original McKinsey framework is solid but was designed for 2001-era negotiations.

Modern board negotiations require these seven enhancements:

1. **Flexibility dimension** → Focus on persuadable stakeholders
2. **Temporal dynamics** → Time your moves strategically
3. **Coalition analysis** → Target group leaders, not individuals
4. **Multi-party bargaining** → Find creative 3-4 way trades
5. **Confidence scoring** → Know what you don't know
6. **Issue dependencies** → Bundle and sequence strategically
7. **BATNA analysis** → Know when to walk away

**These improvements are complementary with the GraphRAG/Neo4j hybrid approach.**

In fact, GraphRAG makes the improved framework practical:
- Flexibility: LLM analyzes historical behavior patterns
- Temporal: Graph stores position history automatically
- Coalitions: Graph algorithms detect voting blocs
- Multi-party: Optimization algorithms find trading cycles
- Confidence: LLM provides confidence scores on extractions
- Dependencies: Graph models issue relationships
- BATNA: LLM searches for historical alternatives that worked

**Together: Best strategic framework (improved McKinsey) + Best automation platform (GraphRAG) = Optimal negotiation planning system for boards.**
