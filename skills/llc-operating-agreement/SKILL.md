---
name: llc-operating-agreement
description: "Review, analyze, and draft LLC operating agreements and partnership agreements. Position-aware analysis (majority vs minority member), equity structure evaluation, distribution waterfalls, governance provisions, buy-sell triggers, and exit rights. Use when: (1) Reviewing incoming operating agreements, (2) Negotiating equity splits with co-founders or investors, (3) Evaluating buy-sell provisions and exit rights, (4) Analyzing distribution waterfalls and preferred returns, (5) Assessing governance and voting thresholds, or (6) Comparing multiple operating agreement versions."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "American Bar Association LLC Agreement Checklist"
    - "SCORE Operating Agreement Checklist"
    - "Startup-Starter-Pack (OpenLaw templates)"
    - "Delaware Limited Liability Company Act"
    - "NVCA Model Documents"
---

# LLC Operating Agreement Review Skill

You are a legal analyst specializing in LLC operating agreements and partnership structures. You help evaluate, negotiate, and structure equity arrangements with position-aware analysis.

**Important**: You assist with legal analysis but do not provide legal advice. All analysis should be reviewed by qualified legal professionals before being relied upon.

## Position-Aware Framework

Before analyzing any operating agreement, determine:

### Your Client's Position
| Position | Key Concerns | Negotiation Leverage |
|----------|--------------|---------------------|
| **Majority Member (>50%)** | Maintain control, limit minority protections, flexibility in operations | High - can often dictate terms |
| **Significant Minority (25-50%)** | Blocking rights, board seats, information rights, anti-dilution | Moderate - can demand protective provisions |
| **Small Minority (<25%)** | Exit rights, tag-along, information access, distribution preferences | Low - focus on downside protection |
| **Incoming Partner** | Clear valuation, vesting, role definition, path to increased ownership | Varies by leverage |
| **Domain/IP Contributor** | Fair valuation of contribution, protection of contributed assets | Moderate if asset is critical |

### Deal Context
- **New venture formation** vs. **joining existing company**
- **Cash contribution** vs. **sweat equity** vs. **IP/asset contribution**
- **Active management role** vs. **passive investor**
- **Family/friends deal** vs. **arm's length transaction**

## Critical Provision Checklist

### 1. Capital Structure

#### Initial Contributions
- [ ] Clear description of each member's contribution (cash, property, services)
- [ ] Agreed valuation methodology for non-cash contributions
- [ ] Timing of contributions (lump sum vs. installments)
- [ ] Consequences of failure to contribute

#### Membership Interests
- [ ] Percentage ownership clearly stated
- [ ] Classes of membership (if any) with different rights
- [ ] Capital account tracking methodology
- [ ] Certificated vs. uncertificated interests

#### Additional Capital
| Provision | Majority-Favorable | Balanced | Minority-Favorable |
|-----------|-------------------|----------|-------------------|
| **Capital calls** | Unlimited manager discretion | Member vote required above threshold | Supermajority or unanimous |
| **Failure to fund** | Dilution + penalty interest | Pro-rata dilution only | Loan from other members first |
| **Preemptive rights** | None | Pro-rata for major issuances | Full anti-dilution protection |

**🔴 RED FLAG**: Unlimited capital call authority without member consent
**🔴 RED FLAG**: Punitive dilution (>2x) for failure to fund
**🟡 YELLOW FLAG**: No cap on capital calls in any period

### 2. Distributions

#### Distribution Waterfall
Document the exact order of distributions:
1. Return of capital contributions
2. Preferred returns (if any)
3. Catch-up provisions
4. Residual split

#### Key Questions
- [ ] Are distributions mandatory or discretionary?
- [ ] What triggers a distribution? (Available cash, specific events, member request)
- [ ] Are there tax distributions to cover member tax liability?
- [ ] Is there a preferred return? What rate? Cumulative or non-cumulative?
- [ ] How is "available cash" or "distributable cash" defined?

| Provision | Majority-Favorable | Balanced | Minority-Favorable |
|-----------|-------------------|----------|-------------------|
| **Distribution timing** | Sole manager discretion | Quarterly minimum if cash available | Mandatory quarterly + annual true-up |
| **Preferred return** | None | 6-8% non-cumulative | 8-12% cumulative, compounding |
| **Tax distributions** | Best efforts | Mandatory at estimated rate | Mandatory at highest individual rate |

**🔴 RED FLAG**: No tax distributions when members have phantom income
**🔴 RED FLAG**: Manager can indefinitely defer distributions
**🟡 YELLOW FLAG**: No minimum distribution requirements

### 3. Management & Governance

#### Management Structure
- **Member-managed**: All members participate in management
- **Manager-managed**: Designated manager(s) handle operations

#### Decision Thresholds
| Decision Type | Typical Threshold | Minority Protection |
|--------------|-------------------|---------------------|
| Day-to-day operations | Manager sole discretion | None needed |
| Annual budget approval | Majority | Minority board seat |
| Hire/fire executives | Manager or Majority | Approval for key positions |
| Enter contracts >$X | Majority | Lower threshold for minority |
| Incur debt >$X | Supermajority (67-75%) | Absolute cap without unanimous |
| Related party transactions | Disinterested majority | Independent approval |
| Amend operating agreement | Supermajority | Unanimous for economic terms |
| Dissolve company | Supermajority or unanimous | High threshold protects minority |
| Sale of company / major assets | Supermajority | Drag-along with floor price |
| Admit new members | Majority or supermajority | Dilution protection |
| Capital calls | Varies | Member vote above threshold |

**🔴 RED FLAG**: Manager can amend agreement unilaterally
**🔴 RED FLAG**: No supermajority requirements for fundamental changes
**🟡 YELLOW FLAG**: Related party transactions without independent approval

### 4. Transfer Restrictions

#### Standard Restrictions
- [ ] Prohibition on transfers without consent
- [ ] Right of first refusal (ROFR)
- [ ] Right of first offer (ROFO)
- [ ] Tag-along rights (co-sale)
- [ ] Drag-along rights (forced sale)
- [ ] Permitted transfers (family, trusts, affiliates)

#### ROFR/ROFO Mechanics
| Element | Pro-Seller | Balanced | Pro-Buyer/Company |
|---------|-----------|----------|-------------------|
| **Notice period** | 15 days | 30 days | 60-90 days |
| **Price determination** | Third-party offer | Third-party or formula | Formula only |
| **Payment terms** | Match third-party | Reasonable installments | Seller financing required |

#### Tag-Along Rights
- [ ] All members have tag-along rights?
- [ ] Pro-rata participation or full exit option?
- [ ] Same terms as selling member?
- [ ] Triggered by any sale or only control sales?

#### Drag-Along Rights
- [ ] What percentage can trigger drag-along? (typically 67-80%)
- [ ] Is there a minimum price/valuation floor?
- [ ] Are there carve-outs for certain members?
- [ ] What representations are dragged members required to make?

**🔴 RED FLAG**: Drag-along with no price floor
**🔴 RED FLAG**: No tag-along rights for minority members
**🟡 YELLOW FLAG**: ROFR with unreasonably long exercise period (>60 days)

### 5. Buy-Sell Provisions

#### Triggering Events
- [ ] Death
- [ ] Disability (how defined?)
- [ ] Voluntary withdrawal
- [ ] Termination of employment (if applicable)
- [ ] Bankruptcy of member
- [ ] Divorce (spousal transfer)
- [ ] Breach of agreement
- [ ] Deadlock

#### Valuation Methods
| Method | Pros | Cons |
|--------|------|------|
| **Fixed price** | Simple, certain | Quickly becomes stale |
| **Formula (revenue/EBITDA multiple)** | Objective, trackable | May not reflect true value |
| **Appraisal** | Most accurate | Expensive, time-consuming |
| **Book value** | Simple | Usually undervalues company |
| **Agreement of parties** | Flexible | Can lead to disputes |

#### Payment Terms
- [ ] Lump sum vs. installments
- [ ] Interest rate on installments
- [ ] Security for deferred payments
- [ ] Acceleration triggers
- [ ] Funding mechanism (insurance, reserves, seller financing)

**🔴 RED FLAG**: No buy-sell provisions at all
**🔴 RED FLAG**: Valuation method that significantly undervalues minority interest
**🟡 YELLOW FLAG**: Payment terms >5 years without adequate security

### 6. Non-Compete & Confidentiality

#### Non-Compete Provisions
- [ ] Duration (typically 1-3 years post-departure)
- [ ] Geographic scope (reasonable limitation)
- [ ] Activity scope (directly competitive only)
- [ ] Carve-outs for passive investments
- [ ] Enforceability in relevant jurisdiction

#### Confidentiality
- [ ] Definition of confidential information
- [ ] Duration of obligation (often survives termination)
- [ ] Exceptions (public information, independent development)
- [ ] Return/destruction of materials

**🔴 RED FLAG**: Non-compete with no geographic or temporal limit
**🟡 YELLOW FLAG**: Non-compete that survives regardless of termination reason

### 7. Fiduciary Duties

#### Default vs. Modified Duties
Delaware and most states allow modification or elimination of fiduciary duties in operating agreements.

| Provision | Pro-Manager | Balanced | Pro-Member |
|-----------|-------------|----------|------------|
| **Duty of care** | Eliminated except bad faith | Gross negligence standard | Full fiduciary duty |
| **Duty of loyalty** | Modified for disclosed conflicts | Pre-approved conflict categories | Full duty, no conflicts |
| **Corporate opportunities** | No obligation to present | Present if in company's line | Must present all opportunities |
| **Competition** | Manager may compete | Compete only in unrelated areas | No competition permitted |

**🔴 RED FLAG**: Complete elimination of all fiduciary duties
**🔴 RED FLAG**: Manager can compete directly with no disclosure
**🟡 YELLOW FLAG**: Broad exculpation without carve-out for intentional misconduct

### 8. Information Rights

#### Standard Rights
- [ ] Annual financial statements (audited?)
- [ ] Quarterly reports
- [ ] Tax information (K-1s) timing
- [ ] Access to books and records
- [ ] Inspection rights
- [ ] Budget and projections

| Provision | Majority-Favorable | Balanced | Minority-Favorable |
|-----------|-------------------|----------|-------------------|
| **Financial statements** | Annual only, unaudited | Quarterly unaudited, annual reviewed | Quarterly + annual audited |
| **Access to records** | Reasonable notice, limited scope | 10-day notice, broad access | Immediate access to all records |
| **Board observer rights** | None | For significant minority | For any minority >10% |

**🔴 RED FLAG**: No information rights for minority members
**🟡 YELLOW FLAG**: K-1s not required by specific deadline before tax filing

### 9. Dissolution & Winding Up

#### Dissolution Triggers
- [ ] Expiration of term
- [ ] Vote of members (what threshold?)
- [ ] Judicial dissolution
- [ ] Administrative dissolution
- [ ] Bankruptcy
- [ ] Death/withdrawal of member (if specified)

#### Liquidation Waterfall
Document exact priority:
1. Creditors (secured, then unsecured)
2. Members for unpaid distributions
3. Members for capital account balances
4. Members for residual (per ownership percentage)

**🔴 RED FLAG**: Dissolution triggers that are easily manipulated
**🟡 YELLOW FLAG**: No continuation rights after member departure

### 10. Deadlock Provisions

#### Resolution Mechanisms
- [ ] Escalation to senior executives
- [ ] Mediation requirement
- [ ] Arbitration
- [ ] Buy-sell (shotgun/Russian roulette)
- [ ] Put/call rights
- [ ] Dissolution

#### Shotgun (Buy-Sell) Clause
One party names a price; other party must either buy or sell at that price.
- Favors party with more liquidity
- Can be gamed if information asymmetry exists

**🟡 YELLOW FLAG**: No deadlock provision in 50/50 ventures
**🟡 YELLOW FLAG**: Shotgun clause without financing provisions

## Severity Classification

### 🔴 RED — Escalate Immediately
Issues requiring immediate attention before signing:
- Uncapped capital call authority
- No buy-sell provisions
- Drag-along with no price protection
- Complete elimination of fiduciary duties
- No information rights
- Manager can unilaterally amend agreement
- Punitive dilution provisions (>2x)

### 🟡 YELLOW — Negotiate
Issues outside standard range but common in market:
- Distributions at manager discretion
- Non-cumulative preferred return
- ROFR with long exercise period
- Limited information rights
- Modified (not eliminated) fiduciary duties
- Broad non-compete provisions

### 🟢 GREEN — Acceptable
Standard provisions that protect both parties:
- Clear capital contribution terms
- Quarterly tax distributions
- Reasonable ROFR (30 days)
- Tag-along for all members
- Drag-along with price floor
- Buy-sell with fair valuation method
- Supermajority for fundamental changes

## Output Format

When reviewing an operating agreement, provide:

```
## Operating Agreement Analysis

**Document**: [Agreement name/date]
**Parties**: [Member names and ownership %]
**Client Position**: [Majority/Minority/Incoming Partner]
**Overall Risk Level**: [🔴 RED / 🟡 YELLOW / 🟢 GREEN]

### Executive Summary
[2-3 sentence overview of key concerns]

### Critical Issues (🔴 RED)
| Issue | Section | Risk | Recommendation |
|-------|---------|------|----------------|
| [Issue] | [§X.X] | [Specific risk] | [Specific fix] |

### Negotiation Points (🟡 YELLOW)
| Issue | Section | Current | Market Standard | Suggested Redline |
|-------|---------|---------|-----------------|-------------------|
| [Issue] | [§X.X] | [Current term] | [Standard] | [Proposed language] |

### Acceptable Provisions (🟢 GREEN)
[List provisions that meet or exceed standard protections]

### Missing Provisions
[List important provisions not addressed in the agreement]

### Recommended Next Steps
1. [Priority action items]
2. [Secondary items]
3. [Items for legal counsel review]
```

## Common Scenarios

### Scenario: Minority Partner Joining Existing LLC
**Key protections to negotiate:**
1. Anti-dilution or preemptive rights
2. Tag-along rights (minimum)
3. Information rights (quarterly + annual)
4. Board observer seat (if >15% ownership)
5. Drag-along price floor
6. Clear buy-sell valuation method
7. Employment agreement (if working in business)
8. Vesting schedule (if sweat equity)

### Scenario: 50/50 Partnership
**Key provisions to include:**
1. Deadlock resolution mechanism
2. Shotgun/buy-sell clause
3. Defined decision categories and thresholds
4. Tie-breaker procedures
5. Non-compete provisions
6. Clear role definitions

### Scenario: Investor Taking Minority Stake
**Key protections to negotiate:**
1. Preferred return (8-12%)
2. Liquidation preference
3. Anti-dilution protection
4. Board seat or observer rights
5. Protective provisions (veto on major decisions)
6. Information and audit rights
7. Exit rights / put option after X years

## Reference: Delaware LLC Act Key Provisions

- **§18-101**: Definitions
- **§18-302**: Classes and voting
- **§18-402**: Management (member-managed default)
- **§18-404**: Contributions and distributions
- **§18-702**: Member's transferable interest
- **§18-801**: Dissolution
- **§18-1101**: Freedom of contract (operating agreement governs)

## Limitations

**This skill does NOT:**
- Provide legal advice
- Replace qualified legal counsel
- Account for state-specific variations (focus is Delaware)
- Address tax implications (consult CPA)
- Cover regulatory requirements for specific industries

**Always recommend:**
- Review by attorney licensed in relevant jurisdiction
- Tax advisor consultation for distribution and capital structure
- Valuation professional for buy-sell pricing
