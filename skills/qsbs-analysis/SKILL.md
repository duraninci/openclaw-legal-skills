---
name: qsbs-analysis
description: "Analyze Qualified Small Business Stock (QSBS) eligibility, tax benefits, and planning strategies under IRC Section 1202. Covers the $10M/$50M exclusion, 5-year holding period, active business requirements, and stacking strategies. Use when: (1) Evaluating if a company qualifies for QSBS, (2) Planning contribution timing for tax optimization, (3) Structuring equity grants for QSBS benefits, (4) Analyzing acquisition impact on QSBS, or (5) Multi-entity QSBS planning."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "IRC Section 1202"
    - "IRS Revenue Procedures"
    - "Tax Court Cases on QSBS"
---

# QSBS (Qualified Small Business Stock) Analysis Skill

You analyze companies and transactions for QSBS eligibility and help optimize structures for maximum tax benefits under IRC Section 1202.

**Important**: This is tax analysis assistance, not tax advice. QSBS rules are complex and frequently litigated. All QSBS planning must be reviewed by qualified tax professionals.

## QSBS Overview

### What is QSBS?

Qualified Small Business Stock allows **exclusion of capital gains** from federal income tax when selling stock in qualifying companies.

### The Tax Benefit

| Acquisition Date | Exclusion % | Max Exclusion |
|------------------|-------------|---------------|
| After Sept 27, 2010 | **100%** | Greater of $10M or 10x basis |
| Feb 18, 2009 - Sept 27, 2010 | 75% | Greater of $10M or 10x basis |
| Before Feb 18, 2009 | 50% | Greater of $10M or 10x basis |

**Example:**
```
Founder acquires stock for $100,000 basis
Company sells for $60,000,000
Founder's share: $15,000,000 gain

Without QSBS: ~$3.5M federal tax (23.8%)
With QSBS: $0 federal tax (100% exclusion up to $10M or 10x basis)

10x basis = $1,000,000 (less than $10M)
So exclusion = $10,000,000
Taxable gain = $5,000,000
Tax savings = ~$2.4M
```

## QSBS Requirements Checklist

### Requirement 1: C Corporation

- [ ] Company must be a **domestic C corporation**
- [ ] Cannot be S corp, LLC, partnership, or foreign corp
- [ ] Must be C corp at time of stock issuance AND continuously thereafter

**Conversion Rules:**
- LLC → C Corp conversion: Stock issued in conversion can qualify
- S Corp → C Corp: Complex; generally stock doesn't qualify
- C Corp → S Corp: Disqualifies QSBS

### Requirement 2: Original Issuance

- [ ] Stock must be acquired at **original issuance**
- [ ] Must be acquired for: money, property, or services
- [ ] Cannot be purchased from another shareholder (secondary sale)

**Qualifying Acquisitions:**
| Method | Qualifies? |
|--------|-----------|
| Founding stock for services | ✅ Yes |
| Stock for cash investment | ✅ Yes |
| Stock for property contribution | ✅ Yes |
| Options exercised | ✅ Yes (on exercise) |
| RSUs vested | ✅ Yes (on vesting) |
| Purchased from another holder | ❌ No |
| Gift received | ✅ Yes (inherits donor's status) |
| Inheritance | ✅ Yes (inherits decedent's status) |

### Requirement 3: $50M Gross Assets Test

- [ ] Corporation's **gross assets** ≤ $50M at time of issuance
- [ ] Must remain ≤ $50M immediately after issuance
- [ ] Measured at adjusted basis, not FMV

**Gross Assets Include:**
- Cash
- Equipment (at adjusted basis)
- Real property (at adjusted basis)
- Intangibles (at adjusted basis)
- All assets of subsidiaries (>50% owned)

**Timing:**
- Test applies at moment of stock issuance
- If company later exceeds $50M, previously issued QSBS still qualifies
- New issuances after exceeding $50M don't qualify

### Requirement 4: Active Business Requirement

- [ ] ≥80% of assets must be used in **active conduct of qualified trade or business**
- [ ] Measured by value
- [ ] Must be active business, not passive investment

**Excluded Businesses (Do NOT Qualify):**
| Business Type | QSBS Eligible? |
|---------------|----------------|
| Professional services (law, accounting, medicine) | ❌ No |
| Financial services (banking, insurance, investing) | ❌ No |
| Brokerage services | ❌ No |
| Hospitality (hotels, restaurants) | ❌ No |
| Farming | ❌ No |
| Mining, oil & gas | ❌ No |
| Any business where principal asset is reputation/skill of employees | ❌ No |

**Qualifying Businesses:**
| Business Type | QSBS Eligible? |
|---------------|----------------|
| Technology / SaaS | ✅ Yes |
| E-commerce / Retail | ✅ Yes |
| Manufacturing | ✅ Yes |
| Wholesale / Distribution | ✅ Yes |
| Construction | ✅ Yes |
| Real estate development (not holding) | ✅ Yes (usually) |

### Requirement 5: Holding Period

- [ ] Must hold stock for **>5 years** from issuance
- [ ] Clock starts at original issuance
- [ ] Cannot be reset by subsequent transactions

**Rollover Option (Section 1045):**
If selling before 5 years:
- Can roll gain into another QSBS within 60 days
- Holding period of new stock includes old stock's period
- Must meet all requirements for new stock

### Requirement 6: No Redemptions

- [ ] Corporation cannot have significant redemptions
- [ ] >5% redemption in 2-year window disqualifies stock

**Redemption Rules:**
- Look at 1 year before and 1 year after issuance
- If corporation redeemed >5% of stock, your QSBS may not qualify
- Applies to redemptions from you or related persons

## QSBS Planning Strategies

### Strategy 1: Basis Stacking

**Concept:** Each shareholder gets their own $10M exclusion. More shareholders = more exclusion.

**Example:**
```
Instead of:
- Founder owns 100% → $10M exclusion max

Structure as:
- Founder owns 50% → $10M exclusion
- Founder's spouse owns 25% → $10M exclusion  
- Founder's trust owns 25% → $10M exclusion
- Total exclusion: $30M
```

**Eligible Entities for Stacking:**
- Spouse (separate $10M)
- Children (if >21 or through trust)
- Grantor trusts (each trust gets $10M)
- Non-grantor trusts (trust gets $10M)
- Parents (if hold stock directly)

**Timing:** Must be done at original issuance or contribution. Later transfers don't create new QSBS.

### Strategy 2: 10x Basis Boost

**Concept:** The exclusion is greater of $10M OR 10x basis. Contributing high-basis assets increases exclusion.

**Example:**
```
Cash contribution: $100,000 basis → $1M max via 10x
Property contribution: $5M basis → $50M max via 10x
```

**High-Basis Contribution Ideas:**
- Appreciated property (contribute at FMV, get FMV basis)
- Existing business assets
- IP with established basis
- Real estate

**Warning:** 704(c) and contribution rules may affect this. Consult tax advisor.

### Strategy 3: Pre-$50M Structuring

**Concept:** Issue stock before company exceeds $50M gross assets.

**Tactics:**
- Issue all founder/employee stock early
- Complete funding rounds before $50M
- Consider timing of large asset acquisitions
- Structure acquisitions as stock purchases (not asset)

### Strategy 4: Holding Period Optimization

**Concept:** Start the 5-year clock as early as possible.

**Tactics:**
- Issue stock on LLC→C Corp conversion immediately
- Don't wait for "cleaner" terms later
- Use vesting (vesting events = new issuances for this purpose)
- Options: Clock starts at exercise, not grant

### Strategy 5: State Tax Planning

**Note:** Not all states follow federal QSBS treatment.

| State | QSBS Treatment |
|-------|----------------|
| California | ❌ Does NOT conform (full state tax) |
| New York | ❌ Does NOT conform |
| Texas | ✅ No state income tax |
| Florida | ✅ No state income tax |
| Washington | ✅ No state income tax |
| Most other states | ✅ Conform to federal |

**Strategy:** Consider state residency planning before exit.

## QSBS and Entity Conversions

### LLC to C Corp Conversion

**Common Scenario:** Company starts as LLC, converts to C Corp for funding or QSBS.

**QSBS Treatment:**
- Stock issued in conversion CAN qualify as QSBS
- Each member receives QSBS equal to their LLC interest
- Holding period starts at conversion
- Prior LLC holding period does NOT count

**Requirements:**
- Must be "original issuance" in the conversion
- $50M test applies at conversion
- Active business test applies
- All other requirements must be met

### S Corp to C Corp Conversion

**Much more complex:**
- Existing S corp stock generally does NOT convert to QSBS
- New stock issued after conversion may qualify
- Consult tax specialist for specific situations

### Contribution of Property

**When you contribute property (not cash) for stock:**
- Your basis in QSBS = your basis in contributed property
- FMV of stock received can exceed $50M (only gross assets matter)
- 704(c) type issues may apply in partnership→corp conversions

## QSBS Due Diligence Checklist

### For Investors/Founders

- [ ] Is the entity a C corporation?
- [ ] When was the stock issued?
- [ ] What was the gross asset value at issuance?
- [ ] Is the business an "active qualified trade or business"?
- [ ] Is the business on the excluded list?
- [ ] Have there been significant redemptions?
- [ ] What is your basis in the stock?
- [ ] When does the 5-year holding period end?
- [ ] What state(s) will you be resident in at sale?

### Red Flags

| Red Flag | Risk |
|----------|------|
| Company was/is S corp | Stock may not qualify |
| Significant cash/investments (>20% of assets) | May fail active business test |
| Professional services revenue | May be excluded business |
| Gross assets near $50M at your issuance | May have exceeded threshold |
| Stock purchased from another holder | Not original issuance |
| Holding period <5 years at planned exit | No QSBS (unless rollover) |

## QSBS and M&A

### Stock Sale (Good for QSBS)

If acquirer buys your stock (not company's assets):
- QSBS exclusion applies to your gain
- Must have held >5 years
- Acquirer's stock does NOT become QSBS to you

### Asset Sale (More Complex)

If company sells assets:
- Company recognizes gain
- Then distributes to shareholders
- May be double tax (corp + shareholder)
- QSBS doesn't help with corporate-level tax

**Strategy:** Push for stock deal if QSBS is significant.

### Stock-for-Stock Exchange

If you receive acquirer's stock:
- Can potentially continue QSBS treatment
- Complex rules - must be "qualified" exchange
- Consult tax advisor

### Earnouts

If part of consideration is earnout:
- QSBS treatment may apply to earnout payments
- Must trace back to original QSBS
- Holding period issues

## Documentation Requirements

**Keep records of:**
1. Stock purchase agreement with issuance date
2. Company gross assets at issuance (balance sheet)
3. Evidence of active business (not excluded type)
4. Basis documentation
5. Any redemption activity
6. Company's C corp status (formation docs, tax elections)

## Output Format

```
## QSBS Analysis

**Company:** [Name]
**Analysis Date:** [Date]
**QSBS Eligible:** [✅ Yes / ❌ No / ⚠️ Uncertain]

### Requirements Checklist
| Requirement | Status | Notes |
|-------------|--------|-------|
| C Corporation | [✅/❌/⚠️] | [Details] |
| Original Issuance | [✅/❌/⚠️] | [Details] |
| $50M Gross Assets | [✅/❌/⚠️] | [Details] |
| Active Business | [✅/❌/⚠️] | [Details] |
| 5-Year Holding | [✅/❌/⚠️] | [Details] |
| No Redemptions | [✅/❌/⚠️] | [Details] |

### Exclusion Calculation
| Element | Amount |
|---------|--------|
| Shareholder's basis | $X |
| 10x basis | $X |
| $10M cap | $10,000,000 |
| **Available exclusion** | $X (greater of above) |

### Planning Opportunities
[List strategies that could apply]

### Risks
[List risks to QSBS qualification]

### Recommendations
1. [Action items]
2. [Questions for tax advisor]
```

## Limitations

**This skill does NOT:**
- Provide tax advice
- Replace qualified CPA/tax attorney review
- Account for state-specific rules beyond overview
- Address AMT implications
- Cover all edge cases

**Always recommend:**
- CPA/tax attorney review for QSBS planning
- Annual QSBS compliance review
- Documentation maintenance
- State tax planning with local advisor
