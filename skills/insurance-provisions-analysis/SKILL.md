---
name: insurance-provisions-analysis
description: "Analyze insurance provisions in operating agreements, M&A documents, and business contracts including key person life insurance, D&O coverage, E&O/professional liability, business interruption, and coverage adequacy assessment. Use when: (1) Reviewing insurance requirements in operating agreements, (2) Evaluating key person coverage amounts, (3) Assessing D&O policy adequacy, (4) Analyzing insurance covenants in loan or investment documents, or (5) Benchmarking coverage against industry standards."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "ACORD Forms and Standards"
    - "Insurance Industry Best Practices"
    - "Private Equity Insurance Requirements"
---

# Insurance Provisions Analysis Skill

You analyze insurance requirements and provisions in legal agreements to assess adequacy, identify gaps, and recommend improvements.

**Important**: This is analytical assistance, not insurance advice. Consult qualified insurance brokers and risk management professionals for coverage decisions.

## Key Insurance Types in Business Agreements

### Key Person Life Insurance

**Purpose**: Protect business against financial loss from death of critical individuals.

**Coverage Amount Benchmarks**:
| Basis | Typical Range | Notes |
|-------|---------------|-------|
| Revenue multiple | 1-2x annual revenue | For sales-driven businesses |
| Profit multiple | 5-10x annual profit | For established businesses |
| Replacement cost | 2-5x annual compensation | Cost to recruit and train replacement |
| Debt coverage | Outstanding debt + 1-2 years operations | Loan covenant requirement |
| Investor protection | Investment amount + expected returns | VC/PE requirement |
| Buy-sell funding | Buyout price per agreement | Fund partner buyout |

**Policy Structure**:
| Element | Options | Considerations |
|---------|---------|----------------|
| Owner | Company or Partners | Tax implications differ |
| Beneficiary | Company | Proceeds fund operations or buyout |
| Type | Term vs. Permanent | Term cheaper; permanent builds value |
| Term length | 10-20 years | Match to business planning horizon |
| Convertibility | Yes/No | Option to convert to permanent |

**Operating Agreement Review**:
- [ ] Coverage amount specified?
- [ ] Policy owner identified?
- [ ] Beneficiary designated?
- [ ] Premium payment responsibility?
- [ ] Coverage maintenance covenant?
- [ ] Proof of coverage requirement?
- [ ] What happens if uninsurable?

**Red Flags**:
| Issue | Risk |
|-------|------|
| Coverage below buyout price | Insufficient to fund buy-sell |
| No maintenance covenant | Coverage could lapse |
| Partner-owned (not company) | May not be available for business use |
| No proof requirement | No verification of compliance |
| Silent on uninsurability | Uncertainty if key person can't get coverage |

### Directors & Officers (D&O) Insurance

**Purpose**: Protect directors, officers, and the company from claims arising from management decisions.

**Coverage Components**:
| Side | What It Covers | Who Benefits |
|------|----------------|--------------|
| Side A | Individual D&O when company can't indemnify | Directors/Officers directly |
| Side B | Reimburses company for indemnifying D&Os | Company |
| Side C | Entity coverage for securities claims | Company |

**Coverage Amount Benchmarks**:
| Company Stage | Typical Coverage | Notes |
|---------------|------------------|-------|
| Pre-revenue startup | $1-2M | Minimum for institutional investors |
| Seed/Series A | $2-5M | Standard VC requirement |
| Series B+ | $5-10M | Increased exposure |
| Public company | $10-50M+ | Securities litigation risk |
| PE-backed | $10-25M | PE firm requirements |

**Key Policy Terms**:
| Term | What It Means | Watch For |
|------|---------------|-----------|
| Retention/Deductible | Amount paid before coverage | High retention = less protection |
| Claims-made | Covers claims made during policy period | Need tail coverage on exit |
| Prior acts | Coverage for acts before policy inception | Exclusion gaps |
| Defense costs | Inside vs. outside limits | Inside limits erode coverage |
| Severability | Whether one person's acts affect others | Non-severability is bad |
| Definition of claim | What triggers coverage | Narrow definitions limit coverage |

**Operating Agreement Review**:
- [ ] D&O coverage required?
- [ ] Minimum coverage amount specified?
- [ ] Coverage components specified (A/B/C)?
- [ ] Maintenance covenant?
- [ ] Run-off/tail coverage on exit?

### Errors & Omissions (E&O) / Professional Liability

**Purpose**: Cover claims arising from professional services, advice, or work product.

**When Required**:
- Professional services businesses (consulting, legal, accounting)
- Technology companies (software errors, data breaches)
- Any business providing advice or deliverables to clients

**Coverage Amount Benchmarks**:
| Revenue | Typical Coverage |
|---------|------------------|
| <$1M | $1M per occurrence / $2M aggregate |
| $1-10M | $2-5M per occurrence |
| $10-50M | $5-10M per occurrence |
| >$50M | $10M+ per occurrence |

**Key Considerations**:
- Per occurrence vs. aggregate limits
- Defense costs inside or outside limits
- Prior acts coverage
- Technology/cyber coverage overlap

### General Liability

**Purpose**: Cover third-party bodily injury, property damage, and personal injury claims.

**Standard Coverage**:
| Limit Type | Typical Amount |
|------------|----------------|
| Per occurrence | $1M |
| General aggregate | $2M |
| Products/completed operations | $2M |
| Personal/advertising injury | $1M |

**Operating Agreement Review**:
- [ ] Minimum limits specified?
- [ ] Additional insured requirements?
- [ ] Certificate of insurance required?

### Business Interruption / Business Income

**Purpose**: Cover lost income when business operations are disrupted.

**Coverage Calculation**:
```
Coverage Amount = (Annual Revenue - Non-continuing Expenses) × Recovery Period

Example:
Annual Revenue: $5,000,000
Non-continuing Expenses: $1,000,000
Recovery Period: 12 months
Coverage Needed: ($5M - $1M) × 1 = $4,000,000
```

**Key Terms**:
| Term | Meaning |
|------|---------|
| Waiting period | Days before coverage begins (typically 72 hours) |
| Period of restoration | Maximum coverage period |
| Actual loss sustained | Pays actual loss vs. stated amount |
| Extended period | Coverage after operations resume |
| Contingent BI | Coverage for supplier/customer disruption |

### Cyber Liability / Data Breach

**Purpose**: Cover costs from data breaches, cyber attacks, and privacy violations.

**Coverage Components**:
- Breach notification costs
- Credit monitoring for affected individuals
- Forensic investigation
- Legal defense and settlements
- Regulatory fines and penalties
- Business interruption from cyber events
- Ransomware payments (controversial)

**Coverage Benchmarks**:
| Data Records | Typical Coverage |
|--------------|------------------|
| <10,000 | $1-2M |
| 10,000-100,000 | $2-5M |
| 100,000-1M | $5-10M |
| >1M | $10M+ |

## Insurance Covenants in Agreements

### Standard Insurance Covenant Language

**Minimum Elements**:
1. Types of coverage required
2. Minimum limits
3. Carrier rating requirements (e.g., A.M. Best A- or better)
4. Additional insured requirements
5. Certificate of insurance delivery
6. Notice of cancellation
7. Waiver of subrogation

**Example Covenant**:
```
The Company shall maintain:
(a) Commercial General Liability with limits not less than $1,000,000 per occurrence
(b) Directors & Officers Liability with limits not less than $5,000,000
(c) Key Person Life Insurance on each Key Person in amount not less than $10,000,000
(d) All policies shall be with carriers rated A- or better by A.M. Best
(e) Company shall deliver certificates of insurance within 30 days of request
(f) Policies shall provide 30 days' notice of cancellation to [Beneficiary]
```

### Analyzing Insurance Requirements

**Questions to Ask**:
1. Are the coverage types appropriate for the business?
2. Are the limits adequate given the risks?
3. Are there gaps between required and actual coverage?
4. Who pays premiums?
5. What happens on breach of insurance covenant?
6. Is there a cure period for lapses?

## Coverage Adequacy Assessment

### Key Person Life Insurance Adequacy

**Formula Approaches**:

**Revenue Replacement Method**:
```
Coverage = Annual Revenue × Revenue Dependency Factor × Recovery Years

Revenue Dependency Factor:
- Highly dependent (sole founder): 0.8-1.0
- Moderately dependent: 0.5-0.7
- Somewhat dependent: 0.2-0.4
```

**Buyout Funding Method**:
```
Coverage = Partner's Equity Value + Premium for Disruption

Example:
Partner's 25% equity at $40M valuation = $10M
Premium for business disruption: 20% = $2M
Recommended Coverage: $12M
```

**Multiple of Compensation Method**:
```
Coverage = Annual Compensation × Multiple

Multiples by role:
- Founder/CEO: 10-15x
- Key technical founder: 8-12x
- Key executive: 5-10x
- Important employee: 3-5x
```

### D&O Coverage Adequacy

**Assessment Factors**:
| Factor | Higher Coverage Needed |
|--------|----------------------|
| Public vs. private | Public = much higher |
| Industry | Regulated industries = higher |
| Company size | Larger = higher |
| Litigation history | Prior claims = higher |
| Board composition | Outside directors = higher |
| Investor base | Institutional = higher |
| International operations | Global = higher |

### Coverage Gap Analysis Template

```
## Coverage Gap Analysis

| Coverage Type | Required | Current | Gap | Risk Level |
|---------------|----------|---------|-----|------------|
| Key Person Life | $10M | $5M | $5M | 🔴 |
| D&O | $5M | $5M | $0 | 🟢 |
| General Liability | $2M | $1M | $1M | 🟡 |
| Cyber | $2M | $0 | $2M | 🔴 |
```

## Operating Agreement Insurance Review

### Checklist

**Key Person Insurance**:
- [ ] Coverage amount specified and adequate
- [ ] Covered individuals identified
- [ ] Policy ownership structure defined
- [ ] Beneficiary designation clear
- [ ] Premium payment responsibility assigned
- [ ] Maintenance covenant present
- [ ] Proof of coverage required
- [ ] Uninsurability provisions included
- [ ] Use of proceeds specified (buyout, operations, etc.)

**D&O Insurance**:
- [ ] Coverage required
- [ ] Minimum limits specified
- [ ] Side A/B/C components addressed
- [ ] Tail/run-off coverage on exit
- [ ] Indemnification provisions align with coverage

**General Business Insurance**:
- [ ] Required coverage types listed
- [ ] Minimum limits specified
- [ ] Carrier rating requirements
- [ ] Certificate delivery requirements
- [ ] Cancellation notice requirements
- [ ] Additional insured provisions
- [ ] Waiver of subrogation

## Severity Classification

### 🔴 RED — Critical Gap

- Key person coverage below buyout obligation
- No D&O coverage with institutional investors
- No cyber coverage with significant data exposure
- No insurance covenant in agreement
- Coverage with non-rated carrier

### 🟡 YELLOW — Review Needed

- Coverage limits below industry benchmarks
- No tail/run-off provisions for D&O
- Ambiguous premium payment responsibility
- No cure period for coverage lapses
- Missing proof of coverage requirements

### 🟢 GREEN — Adequate

- Coverage meets or exceeds requirements
- Appropriate carrier ratings
- Clear covenant language
- Adequate limits for business size/risk
- Proper notice and certificate provisions

## Output Format

```
## Insurance Provisions Analysis

**Document**: [Agreement name]
**Analysis Date**: [Date]
**Overall Assessment**: [🔴 RED / 🟡 YELLOW / 🟢 GREEN]

### Coverage Summary
| Type | Required | Amount | Adequate? |
|------|----------|--------|-----------|
| Key Person Life | [Yes/No] | $X | [Yes/No] |
| D&O | [Yes/No] | $X | [Yes/No] |
| General Liability | [Yes/No] | $X | [Yes/No] |
| Cyber | [Yes/No] | $X | [Yes/No] |

### Key Person Insurance Analysis
- Covered individuals: [Names]
- Coverage amount: $X
- Adequacy assessment: [Analysis]
- Buyout funding: [Sufficient/Insufficient]

### D&O Insurance Analysis
- Coverage required: [Yes/No]
- Amount: $X
- Components: [Side A/B/C]
- Tail coverage: [Yes/No]

### Covenant Analysis
- Maintenance requirements: [Adequate/Inadequate]
- Proof requirements: [Present/Missing]
- Cure provisions: [Present/Missing]

### Critical Gaps (🔴)
[List critical issues]

### Recommendations
1. [Action items]
2. [Questions for insurance broker]
```

## Limitations

**This skill does NOT:**
- Provide insurance advice
- Replace qualified insurance broker consultation
- Assess policy terms and conditions (only agreement requirements)
- Evaluate carrier financial strength
- Price insurance coverage

**Always recommend:**
- Insurance broker review of actual policies
- Annual coverage adequacy review
- Coordination between legal and insurance advisors
