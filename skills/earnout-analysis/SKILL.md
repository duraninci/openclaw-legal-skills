---
name: earnout-analysis
description: "Analyze earnout and contingent consideration structures in M&A, partnerships, and equity agreements. Includes milestone structure evaluation, payment mechanics, protection provisions, accounting treatment, and dispute risk assessment. Use when: (1) Reviewing earnout provisions in acquisition agreements, (2) Evaluating Class B/profits interest incentive structures, (3) Analyzing performance milestone triggers, (4) Assessing earnout dispute risks, or (5) Negotiating contingent payment terms."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "ASC 805 Business Combinations"
    - "M&A Deal Terms Studies"
    - "ABA Model Acquisition Agreement"
    - "Private Equity Earnout Structures"
---

# Earnout & Contingent Consideration Analysis Skill

You analyze earnout provisions, performance-based equity, and contingent payment structures to identify risks, evaluate fairness, and recommend protections.

**Important**: This is analytical assistance. Earnout disputes are among the most litigated M&A issues. Legal counsel review is essential.

## Earnout Fundamentals

### What is an Earnout?

An earnout is contingent consideration where additional payment is made if specified performance targets are achieved post-closing.

**Common Structures**:
| Type | Description | Example |
|------|-------------|---------|
| Revenue earnout | Based on revenue targets | $1M if revenue exceeds $10M |
| EBITDA earnout | Based on profitability | $2M if EBITDA exceeds $2M |
| Milestone earnout | Based on specific achievements | $500K per product launch |
| Hybrid | Multiple metrics combined | Revenue + margin thresholds |
| Profits interest | Equity based on performance | Class B units vest on targets |

### Why Earnouts Exist

**Seller Perspective**:
- Bridge valuation gap
- Share in upside potential
- Demonstrate confidence in projections
- Retain key employees (if tied to employment)

**Buyer Perspective**:
- Reduce overpayment risk
- Align seller incentives
- Finance portion from future performance
- Retain seller expertise

### Earnout vs. Profits Interest

| Feature | Earnout | Profits Interest |
|---------|---------|------------------|
| Form | Cash payment | Equity/ownership |
| Tax treatment | Ordinary income (usually) | Capital gains potential |
| Participation | Fixed formula | Ongoing profit share |
| Duration | Defined period | Perpetual (until exit) |
| Control | Seller typically passive | May include governance rights |
| Risk profile | Binary (hit/miss) | Continuous upside |

## Earnout Structure Analysis

### Performance Metrics

**Revenue-Based Metrics**:
| Metric | Pros | Cons |
|--------|------|------|
| Gross revenue | Simple, hard to manipulate | Ignores profitability |
| Net revenue | Accounts for returns/discounts | Definition disputes |
| Recurring revenue (ARR/MRR) | Quality focus | Excludes one-time |
| Bookings | Forward-looking | May not convert to revenue |

**Profitability Metrics**:
| Metric | Pros | Cons |
|--------|------|------|
| EBITDA | Standard, comparable | Adjustments manipulable |
| Net income | Bottom line focus | Accounting discretion |
| Gross margin | Operational focus | Ignores overhead |
| Operating cash flow | Cash-based | Timing manipulation |

**Milestone Metrics**:
| Metric | Examples | Considerations |
|--------|----------|----------------|
| Product | Launch, FDA approval, feature release | Define "completion" clearly |
| Customer | New customers, retention rate, NPS | Verification mechanisms |
| Operational | Headcount, geographic expansion | Objective vs. subjective |
| Strategic | Partnership, funding, IPO | May be outside control |

### Earnout Period

**Typical Durations**:
| Deal Type | Typical Period |
|-----------|----------------|
| Small M&A (<$10M) | 1-2 years |
| Mid-market M&A | 2-3 years |
| Large M&A | 3-5 years |
| PE platform | 3-5 years |
| Management incentive | 3-7 years |

**Period Considerations**:
- Longer = more uncertainty for seller
- Shorter = less time to prove value
- Multi-year with annual targets = balanced approach
- Acceleration clauses can shorten period

### Payment Structure

**Timing Options**:
| Structure | Description | Risk Distribution |
|-----------|-------------|-------------------|
| Single payment | All at end of period | High seller risk |
| Annual payments | Paid each year | Moderate risk |
| Milestone payments | Paid on achievement | Varies by milestone |
| Installments | Scheduled payments | Lower seller risk |

**Payment Caps and Floors**:
```
Cap: Maximum earnout payment regardless of performance
Floor: Minimum guaranteed payment

Example:
- Target: 30% of revenue growth
- Floor: $500K (guaranteed)
- Cap: $3M (maximum)
- Actual: 50% growth → Capped at $3M
```

## Key Provisions to Analyze

### Definition Provisions

**Critical Definitions**:
- [ ] **Revenue/EBITDA definition** — What's included/excluded?
- [ ] **Adjustments** — What adjustments are permitted?
- [ ] **Accounting standards** — GAAP? Consistent with historical?
- [ ] **Carve-outs** — What transactions excluded (M&A, extraordinary)?
- [ ] **Intercompany charges** — How handled?
- [ ] **Allocation of overhead** — Corporate allocations?

**Red Flag: Vague Definitions**
```
❌ "EBITDA as reasonably determined by Buyer"
✅ "EBITDA calculated in accordance with GAAP, consistent with 
    the Company's historical practices, with adjustments limited 
    to those set forth in Exhibit A"
```

### Operational Covenants

**Buyer Obligations**:
| Covenant | Purpose | Seller Protection |
|----------|---------|-------------------|
| Operate in ordinary course | Prevent sabotage | Medium |
| Maintain separate accounting | Track performance | High |
| No material changes | Preserve business | High |
| Good faith efforts | Affirmative duty | Medium-Low |
| Resource commitments | Capital/staffing | High |

**Standard Language**:
```
Buyer shall:
(a) Operate the Business in substantially the same manner 
    as conducted prior to Closing
(b) Use commercially reasonable efforts to achieve the 
    Earnout Targets
(c) Not take any action with the primary purpose of 
    reducing the Earnout Payment
(d) Maintain books and records sufficient to calculate 
    Earnout in accordance with this Agreement
```

### Acceleration Provisions

**Trigger Events**:
| Event | Typical Treatment |
|-------|-------------------|
| Sale of company | Accelerate at target (or pro-rata) |
| Change of control | Often accelerates payment |
| Termination without cause | May accelerate portion |
| Material breach by buyer | Accelerate or pay maximum |
| IPO | May accelerate or convert |

**Acceleration Formula**:
```
On Change of Control:
- If in Year 1: Pay [50%] of Maximum Earnout
- If in Year 2: Pay [75%] of Maximum Earnout
- If in Year 3+: Pay [100%] of Maximum Earnout

OR

Pay the greater of:
(a) Actual performance pro-rated to date of CoC
(b) Target performance for completed periods
```

### Dispute Resolution

**Dispute Mechanisms**:
| Mechanism | Speed | Cost | Finality |
|-----------|-------|------|----------|
| Good faith negotiation | Fast | Low | None |
| Independent accountant | Moderate | Medium | High (usually binding) |
| Mediation | Moderate | Medium | None |
| Arbitration | Slow | High | High |
| Litigation | Very slow | Very high | High (after appeals) |

**Best Practice**: Escalating process
```
1. Written notice of dispute (10 days to respond)
2. Good faith negotiation (30 days)
3. Independent accountant review (binding on accounting matters)
4. Arbitration (binding on all other matters)
```

**Independent Accountant Process**:
- Both parties submit positions
- Accountant cannot exceed either party's position
- Decision typically binding
- Costs often split or loser pays

## Risk Assessment Framework

### Seller Risk Factors

| Risk | Description | Mitigation |
|------|-------------|------------|
| **Manipulation** | Buyer manages to miss targets | Strong covenants, audit rights |
| **Integration** | Business combined, loses identity | Separate accounting requirement |
| **Underfunding** | Buyer doesn't invest resources | Resource commitment covenant |
| **Distraction** | Buyer ignores business | Ordinary course covenant |
| **Definition games** | Accounting to reduce earnout | Specific definitions, historical consistency |
| **Strategic decisions** | Buyer sacrifices short-term for long-term | Covenant against material changes |

### Buyer Risk Factors

| Risk | Description | Mitigation |
|------|-------------|------------|
| **Overpayment** | Earnout exceeds fair value | Cap on maximum payment |
| **Seller departure** | Key people leave | Employment/non-compete tied to earnout |
| **Operational constraints** | Covenants limit flexibility | Negotiate reasonable standards |
| **Accounting disputes** | Endless arguments | Clear definitions, accountant process |
| **Litigation cost** | Disputes expensive | Strong arbitration clause |

### Risk Scoring Matrix

**Score each factor 1-5, weight by importance**:

```
## Earnout Risk Assessment

| Factor | Score (1-5) | Weight | Weighted |
|--------|-------------|--------|----------|
| Metric clarity | [X] | 20% | [X] |
| Operational covenants | [X] | 20% | [X] |
| Accounting standards | [X] | 15% | [X] |
| Acceleration protection | [X] | 15% | [X] |
| Dispute mechanism | [X] | 15% | [X] |
| Payment security | [X] | 15% | [X] |
| **Total Risk Score** | | | [X/5] |

Risk Level:
- 4.0-5.0: Low risk (well-protected)
- 3.0-3.9: Moderate risk (standard protections)
- 2.0-2.9: Elevated risk (gaps exist)
- 1.0-1.9: High risk (significant concerns)
```

## Profits Interest / Class B Unit Analysis

### Structure Elements

**Key Terms**:
| Element | Description | Standard Range |
|---------|-------------|----------------|
| Hurdle/threshold | Amount above which participation begins | Contributed capital + return |
| Catch-up | Allows quick vesting of participation | 50-100% |
| Participation % | Share above hurdle | 10-30% for executives |
| Vesting | Time or performance conditions | 3-5 years |
| Cliff | Initial period before any vesting | 1 year typical |

### Incentive Alignment Analysis

**Questions to Ask**:
1. Are targets achievable under realistic scenarios?
2. Do targets align with overall business goals?
3. Can recipient influence achievement?
4. Is the reward proportionate to contribution?
5. What happens if targets partially met?

### Example: Class B Unit Analysis

```
## Class B Unit Structure Analysis

**Recipient**: FS Entity
**Maximum Class B**: 20% of profits interests

**Vesting Triggers**:
| Trigger | Class B Earned | Assessment |
|---------|---------------|------------|
| Domain performance (10%) | Up to 10% | Tied to Qualified Revenue |
| Fundraising success (10%) | Up to 10% | Tied to $5M+ raised |

**Hurdle Analysis**:
- Capital contributions: $2M total
- Preferred return implied: ~8% (typical)
- Catch-up: [Check agreement]

**Achievability Assessment**:
- Domain revenue targets: [Realistic/Aggressive/Unrealistic]
- Fundraising targets: [Realistic/Aggressive/Unrealistic]
- Combined probability: [X%]

**Value at Full Vesting**:
If company worth $100M at exit:
- Class A (100%): $100M base
- Class B participation (20%): $X above hurdle
- FS Total: 25% Class A + 20% Class B = [Calculate]
```

## Accounting Treatment (ASC 805)

### Contingent Consideration Recognition

**At Acquisition Date**:
- Fair value of contingent consideration recorded as part of purchase price
- Typically liability (cash earnouts) or equity (stock earnouts)

**Subsequent Measurement**:
| Classification | Measurement | P&L Impact |
|----------------|-------------|------------|
| Liability | Fair value each period | Yes (remeasurement gain/loss) |
| Equity | Not remeasured | No |

**Fair Value Estimation**:
- Probability-weighted scenarios
- Discount rate for time value
- Volatility assumptions
- Monte Carlo simulation (complex earnouts)

### Disclosure Requirements

Public companies must disclose:
- Maximum potential payment
- Current fair value estimate
- Key assumptions
- Changes in fair value
- Range of outcomes

## Severity Classification

### 🔴 RED — High Dispute Risk

- Vague or undefined performance metrics
- No operational covenants protecting seller
- No acceleration on change of control
- Buyer has sole discretion on key decisions
- No dispute resolution mechanism
- No audit rights for seller

### 🟡 YELLOW — Moderate Risk

- Metrics defined but with adjustment discretion
- Limited operational covenants
- Partial acceleration protection
- Independent accountant only (no arbitration fallback)
- Seller audit rights limited

### 🟢 GREEN — Well-Protected

- Clear, objective metric definitions
- Strong operational covenants
- Full acceleration on material events
- Robust dispute resolution (accountant + arbitration)
- Full audit and information rights
- Historical accounting consistency required

## Output Format

```
## Earnout / Contingent Consideration Analysis

**Document**: [Agreement name]
**Structure Type**: [Earnout / Profits Interest / Hybrid]
**Risk Level**: [🔴 RED / 🟡 YELLOW / 🟢 GREEN]

### Structure Summary
| Element | Terms |
|---------|-------|
| Maximum payment | $X / X% |
| Performance period | X years |
| Metrics | [Description] |
| Payment timing | [Schedule] |
| Acceleration | [Triggers] |

### Metric Analysis
| Metric | Definition Clarity | Manipulation Risk | Achievability |
|--------|-------------------|-------------------|---------------|
| [Metric 1] | [Clear/Vague] | [High/Medium/Low] | [Realistic/Aggressive] |

### Protection Assessment
| Protection | Present | Adequate |
|------------|---------|----------|
| Operational covenants | [Yes/No] | [Yes/No] |
| Accounting standards | [Yes/No] | [Yes/No] |
| Audit rights | [Yes/No] | [Yes/No] |
| Acceleration | [Yes/No] | [Yes/No] |
| Dispute resolution | [Yes/No] | [Yes/No] |

### Risk Score
[Risk scoring matrix]

### Critical Issues (🔴)
[List high-risk items]

### Recommendations
1. [Action items]
2. [Provisions to negotiate]
```

## Limitations

**This skill does NOT:**
- Provide legal advice
- Replace M&A counsel review
- Calculate fair value for accounting
- Predict dispute outcomes
- Guarantee earnout achievement

**Always recommend:**
- M&A attorney review of earnout provisions
- Accountant review of metric definitions
- Financial advisor for fair value estimation
- Consider earnout insurance for high-value deals
