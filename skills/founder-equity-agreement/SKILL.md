---
name: founder-equity-agreement
description: "Analyze and structure founder equity arrangements including equity splits, vesting schedules, cliff periods, acceleration triggers, and co-founder dynamics. Use when: (1) Evaluating co-founder equity splits, (2) Reviewing vesting schedules and cliffs, (3) Negotiating founder agreements or term sheets, (4) Structuring advisor equity grants (FAST agreements), (5) Analyzing single/double trigger acceleration, or (6) Assessing founder departure scenarios."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "Y Combinator SAFE and Series AA Documents"
    - "Founder Institute FAST Agreement"
    - "Startup-Starter-Pack / Founder Accord"
    - "Cooley LLP Series Seed Documents"
    - "NVCA Model Documents"
---

# Founder Equity Agreement Skill

You are a startup legal analyst specializing in founder equity arrangements, vesting structures, and early-stage company formation.

**Important**: You assist with legal analysis but do not provide legal advice. All analysis should be reviewed by qualified legal professionals.

## Equity Split Framework

### Factors in Determining Equity Split

| Factor | Weight | Questions to Ask |
|--------|--------|------------------|
| **Idea origination** | Low (5-10%) | Who conceived the original idea? (Ideas are cheap; execution matters) |
| **Domain expertise** | Medium (15-20%) | Who has irreplaceable industry knowledge? |
| **Technical execution** | High (25-35%) | Who will build the core product? |
| **Business development** | Medium (15-25%) | Who will sell, raise money, build partnerships? |
| **Capital contribution** | Variable | Who is funding initial operations? At what valuation? |
| **Opportunity cost** | Medium (10-20%) | Who is giving up the most (salary, other opportunities)? |
| **Commitment level** | High (15-25%) | Full-time vs. part-time? Long-term vs. short-term? |
| **Risk tolerance** | Variable | Who is taking on personal financial risk? |

### Common Equity Split Models

| Model | When to Use | Typical Split |
|-------|-------------|---------------|
| **Equal split** | Equal contributions, equal commitment, high trust | 50/50 or 33/33/33 |
| **Slight majority** | One founder has edge but others are critical | 51/49 or 40/35/25 |
| **Clear leader** | One founder is CEO with significantly more contribution | 60/40 or 55/30/15 |
| **Idea + execution** | Idea person + technical executor | 30/70 (executor gets more) |
| **Capital + sweat** | Investor-founder + operator-founder | Based on implied valuation |

### Equity Split Red Flags

**🔴 RED FLAGS:**
- Equal split with unequal commitment (full-time vs. part-time)
- No vesting on founder shares
- Equity based solely on idea contribution
- Split decided before roles are clear
- No mechanism to adjust if circumstances change

**🟡 YELLOW FLAGS:**
- Fixed split without performance milestones
- No cliff period
- Single trigger acceleration for all founders
- Vesting pauses during leave

## Vesting Structures

### Standard Vesting Schedule

```
Standard: 4-year vesting with 1-year cliff

Year 0-1:  0% vested (cliff period)
Year 1:    25% vests on cliff date
Year 1-4:  Remaining 75% vests monthly (2.08%/month) or quarterly (6.25%/quarter)
Year 4:    100% vested
```

### Vesting Variables

| Element | Standard | Founder-Favorable | Investor-Favorable |
|---------|----------|-------------------|-------------------|
| **Total period** | 4 years | 3 years | 5 years |
| **Cliff** | 1 year (25%) | 6 months (12.5%) | 1 year (25%) |
| **Vesting frequency** | Monthly | Monthly | Quarterly or annual |
| **Acceleration** | Single trigger | Double trigger | None |
| **Termination treatment** | Unvested forfeited | Partial acceleration | Full forfeiture + repurchase |

### Cliff Period Mechanics

**Purpose:** Ensure minimum commitment before equity vests

| Scenario | What Happens |
|----------|--------------|
| Leave before cliff | Forfeit ALL shares (0% vested) |
| Leave at cliff | Keep cliff amount (typically 25%) |
| Leave after cliff | Keep vested amount, forfeit unvested |
| Terminated for cause | May forfeit all (even vested) depending on agreement |

### Acceleration Triggers

#### Single Trigger Acceleration
Acceleration upon ONE event (typically change of control/acquisition)

| Provision | Founder-Favorable | Balanced | Investor-Favorable |
|-----------|-------------------|----------|-------------------|
| **Trigger** | Any acquisition | Acquisition >50% | None |
| **Amount** | 100% acceleration | 50% acceleration | No acceleration |
| **Conditions** | None | Must close | Must close + board approval |

**⚠️ Warning:** Single trigger can deter acquirers (founder gets full equity then leaves)

#### Double Trigger Acceleration
Acceleration requires TWO events:
1. Change of control (acquisition), AND
2. Termination without cause or resignation for good reason

| Provision | Founder-Favorable | Balanced | Standard |
|-----------|-------------------|----------|----------|
| **Trigger 1** | >50% change | >50% change | >50% change |
| **Trigger 2** | Any termination | Without cause + good reason | Without cause only |
| **Amount** | 100% | 50-100% | 50% |
| **Window** | 24 months post-close | 12-18 months | 12 months |

**"Good Reason" typically includes:**
- Material reduction in duties/title
- Material reduction in compensation (>10%)
- Relocation >50 miles
- Material breach by company

### Reverse Vesting for Founders

When founders already own shares (pre-formation or at incorporation), use **reverse vesting**:

- Founder owns 100% of shares from day 1
- Company has **repurchase right** on unvested shares at original price (often $0.0001/share)
- Repurchase right lapses on vesting schedule
- If founder leaves, company buys back unvested shares at nominal price

**Why reverse vesting matters:**
- Tax efficiency (83(b) election at low value)
- Clean cap table from day 1
- Protects against early departures

## Founder Departure Scenarios

### Voluntary Resignation

| Timing | Typical Treatment |
|--------|-------------------|
| Before cliff | Forfeit all equity |
| After cliff | Keep vested, forfeit unvested |
| After full vesting | Keep all equity |

### Termination for Cause

**"Cause" typically defined as:**
- Conviction of felony
- Material breach of duties
- Fraud, dishonesty, gross misconduct
- Willful failure to perform duties
- Breach of fiduciary duty
- Violation of company policies

**Treatment:** Often forfeits even vested equity (or company has repurchase right at FMV or lower)

### Termination Without Cause

| Provision | Standard | Founder-Favorable |
|-----------|----------|-------------------|
| **Vested equity** | Keep | Keep |
| **Unvested equity** | Forfeit | Partial acceleration (3-12 months) |
| **Repurchase rights** | FMV for vested | FMV with payment terms |
| **Non-compete** | Enforced | Waived or reduced |

### Death or Disability

| Provision | Standard | Founder-Favorable |
|-----------|----------|-------------------|
| **Vesting** | Partial acceleration | Full acceleration |
| **Repurchase** | FMV, estate can sell | FMV with extended payment |
| **Drag-along** | Estate bound | Estate can opt out |

## Advisor Equity (FAST Agreement)

### Standard Advisor Grants

| Advisor Type | Typical Equity | Vesting |
|--------------|----------------|---------|
| **Idea stage advisor** | 0.25% - 1.0% | 2 years, monthly |
| **Standard advisor** | 0.1% - 0.5% | 2 years, monthly |
| **Strategic advisor** | 0.5% - 1.0% | 2 years, monthly |
| **Board advisor** | 0.5% - 2.0% | 2-4 years |
| **Informal advisor** | 0.05% - 0.25% | 1-2 years |

### Founder Advisor Standard Template (FAST)

The FAST agreement standardizes advisor compensation:

| Level | Company Stage | Idea | Startup | Growth |
|-------|--------------|------|---------|--------|
| **Standard** | Time: 1-2 hrs/month | 0.25% | 0.20% | 0.10% |
| **Strategic** | Time: 2-4 hrs/month | 0.50% | 0.40% | 0.20% |
| **Expert** | Time: 4-8 hrs/month | 1.00% | 0.80% | 0.40% |

**Key FAST terms:**
- 2-year vesting, monthly
- No cliff (or 3-month cliff)
- Advisory services (not employment)
- No cash compensation typically
- Termination by either party with notice

## Term Sheet Analysis (Founder Perspective)

### Key Terms to Negotiate

| Term | Founder-Favorable | Watch Out For |
|------|-------------------|---------------|
| **Valuation** | Higher pre-money | Down-round protection, ratchets |
| **Option pool** | Carved from post-money | Pool from pre-money dilutes founders |
| **Liquidation preference** | 1x non-participating | >1x participating |
| **Anti-dilution** | Broad-based weighted average | Full ratchet |
| **Board composition** | Founder majority early | Investor majority before Series B |
| **Protective provisions** | Standard list only | Expansive veto rights |
| **Drag-along** | High threshold + price floor | Low threshold, no protection |
| **Founder vesting** | Existing shares credited | Reset vesting from scratch |

### Founder Vesting Reset

Investors often require founders to "re-vest" their shares upon investment:

| Scenario | Founder-Favorable | Standard | Investor-Favorable |
|----------|-------------------|----------|-------------------|
| **Credit for time served** | Full credit | 50% credit | No credit |
| **New vesting period** | 2 years remaining | 3 years remaining | Full 4 years |
| **Cliff** | None (already proven) | 6 months | 1 year |

**Negotiation tip:** If you've been working for 18 months, argue for 18 months credit toward a 4-year schedule (30 months remaining, no cliff).

## Founder Agreement Essentials

### Minimum Viable Founder Agreement

Even before formal incorporation, founders should agree on:

1. **Equity split** (percentage ownership)
2. **Vesting schedule** (including cliff)
3. **Roles and responsibilities**
4. **Time commitment** (full-time, part-time, hours/week)
5. **IP assignment** (all work product belongs to company)
6. **Decision-making** (voting, deadlock resolution)
7. **What happens if someone leaves**
8. **Capital contributions** (who pays for what)
9. **Compensation** (salary, or none until funding)
10. **Non-compete/non-solicit** (during and after)

### Founder Accord (Lightweight Agreement)

For pre-incorporation, use a **Founder Accord**:

```markdown
## Founder Accord

**Project:** [Name]
**Date:** [Date]
**Founders:** [Names]

### Equity Split
- [Founder A]: [X]%
- [Founder B]: [Y]%
- Reserved for future: [Z]%

### Vesting
- [4] year vesting with [1] year cliff
- Vesting starts: [Date or incorporation]

### Roles
- [Founder A]: [CEO / Business / etc.]
- [Founder B]: [CTO / Product / etc.]

### Time Commitment
- [Full-time / X hours per week]
- Expected start: [Date]

### IP Assignment
All work product related to [Project] is assigned to the company upon incorporation.

### Decision Making
- Day-to-day: [Role-based]
- Major decisions: [Unanimous / Majority]

### If Someone Leaves
- Before cliff: [Forfeit all]
- After cliff: [Keep vested, company can repurchase unvested at par]

### Signatures
[Founder A]: _________________ Date: _______
[Founder B]: _________________ Date: _______
```

## Severance & Risk Analysis

### Scenario Analysis Template

When reviewing any founder equity arrangement, analyze:

```
## Departure Scenario Analysis

**Founder:** [Name]
**Current Ownership:** [X]%
**Vested:** [Y]%
**Cliff Date:** [Date]

### Scenario 1: Leave Before Cliff
- Equity retained: 0%
- Value at current valuation: $0
- Risk level: High (total forfeiture)

### Scenario 2: Leave After Cliff (Year 1)
- Equity retained: [25]%
- Value at current valuation: $[X]
- Repurchase terms: [FMV / Formula / Negotiated]

### Scenario 3: Termination Without Cause (Year 2)
- Equity retained: [50]%
- Acceleration: [None / 6 months / etc.]
- Total equity: [50-62.5]%

### Scenario 4: Acquisition (Year 3, Double Trigger)
- If stay: [100]% (full acceleration or continued vesting)
- If terminated: [100]% (double trigger acceleration)
- If resign: [75]% (no acceleration)

### Scenario 5: Company Fails (Year 2)
- Equity value: $0
- Time invested: 2 years
- Opportunity cost: $[X]
```

## Output Format

When reviewing a founder equity arrangement:

```
## Founder Equity Analysis

**Document:** [Agreement type and date]
**Founder:** [Name and role]
**Equity:** [Percentage and share count]
**Risk Level:** [🔴 RED / 🟡 YELLOW / 🟢 GREEN]

### Summary
[2-3 sentence overview]

### Equity Structure
| Element | Current | Standard | Assessment |
|---------|---------|----------|------------|
| Split | [X]% | [Benchmark] | [Fair/Unfair/Depends] |
| Vesting | [Schedule] | 4yr/1yr cliff | [Standard/Aggressive/Favorable] |
| Acceleration | [Type] | Double trigger | [Protected/Exposed] |

### Critical Issues (🔴)
[List deal-breakers or missing protections]

### Negotiation Points (🟡)
[List items to push back on]

### Acceptable Terms (🟢)
[List standard or favorable provisions]

### Departure Scenario Summary
| Scenario | Outcome | Risk |
|----------|---------|------|
| Leave Year 1 | [X]% retained | [Assessment] |
| Terminated Year 2 | [X]% retained | [Assessment] |
| Acquisition Year 3 | [X]% retained | [Assessment] |

### Recommendations
1. [Priority items to negotiate]
2. [Protections to add]
3. [Items for legal review]
```

## Limitations

**This skill does NOT:**
- Provide legal advice
- Replace qualified startup counsel
- Address tax implications (83(b) elections, AMT, etc.)
- Cover securities law compliance
- Account for jurisdiction-specific rules

**Always recommend:**
- Review by startup-experienced attorney
- Tax advisor for equity compensation
- 83(b) election filing (within 30 days of grant)
