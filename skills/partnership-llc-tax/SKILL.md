---
name: partnership-llc-tax
description: "Analyze partnership and LLC tax implications including Section 721 contributions, 704(b) capital accounts, 704(c) allocations, 83(b) elections for profits interests, substantial economic effect, and tax distributions. Use when: (1) Reviewing operating agreements for tax provisions, (2) Evaluating capital contribution structures, (3) Analyzing profits interest grants (Class B units), (4) Assessing tax distribution adequacy, (5) Reviewing allocation provisions for substantial economic effect, or (6) Planning 83(b) elections."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "IRC Section 721, 704, 83"
    - "Treasury Regulations 1.704-1, 1.704-2, 1.721-1"
    - "IRS Revenue Procedure 93-27, 2001-43"
    - "IRS Notice 2005-43 (Profits Interests)"
---

# Partnership/LLC Tax Analysis Skill

You are a tax analyst specializing in partnership and LLC taxation. You help evaluate operating agreements for tax compliance, efficiency, and risk.

**Important**: This is tax analysis assistance, not tax advice. All tax matters should be reviewed by qualified CPAs and tax attorneys. Tax law changes frequently; verify current requirements with professionals.

## Core Tax Concepts

### Section 721: Nonrecognition on Contributions

**General Rule**: No gain or loss is recognized when property is contributed to a partnership in exchange for a partnership interest.

**Key Requirements**:
- Must be a contribution (not a sale or loan)
- Must be in exchange for a partnership interest
- Partnership must be treated as a partnership for tax purposes

**Exceptions (Gain Recognition)**:
| Scenario | Treatment |
|----------|-----------|
| Services contributed | Taxable compensation to contributor |
| Liabilities exceed basis | Gain recognized to extent of excess |
| Investment company | Gain recognized on diversification |
| Disguised sale | Treated as sale, not contribution |

**Basis Rules**:
- Contributor's basis in partnership interest = basis in contributed property
- Partnership's basis in contributed property = contributor's basis (carryover basis)
- Holding period tacks

### Section 704(b): Capital Accounts

**Capital Account Maintenance**:
Partners' capital accounts must be maintained according to Treasury Regulations for allocations to have "substantial economic effect."

**Capital Account Adjustments**:
| Event | Adjustment |
|-------|------------|
| Cash contribution | + Amount contributed |
| Property contribution | + FMV of property |
| Allocation of income/gain | + Allocated amount |
| Allocation of loss/deduction | - Allocated amount |
| Cash distribution | - Amount distributed |
| Property distribution | - FMV of property |

**Book-Tax Differences**:
- "Book" capital accounts use FMV
- "Tax" capital accounts use adjusted basis
- Difference creates Section 704(c) issues

### Section 704(c): Built-In Gain/Loss Allocations

**Purpose**: Prevent shifting of pre-contribution gain/loss between partners.

**When It Applies**:
Property contributed with FMV ≠ adjusted basis creates "built-in gain" or "built-in loss."

**Example**:
```
Partner A contributes property:
- FMV: $1,000,000
- Basis: $400,000
- Built-in gain: $600,000

If partnership sells for $1,000,000:
- Book gain: $0 (sold at book value)
- Tax gain: $600,000 (sold above tax basis)
- All $600,000 tax gain allocated to Partner A (704(c))
```

**Allocation Methods**:
| Method | Description | Best For |
|--------|-------------|----------|
| **Traditional** | Allocate built-in gain/loss to contributor; ceiling rule limits | Simple situations |
| **Traditional with Curative** | Use other items to cure ceiling rule distortions | Moderate complexity |
| **Remedial** | Create notional tax items to eliminate distortions | Complex, high-value contributions |

**Operating Agreement Review**:
- [ ] Does agreement specify 704(c) allocation method?
- [ ] Is the method appropriate for the contributed property?
- [ ] Are there anti-abuse provisions?

### Substantial Economic Effect

**Two-Part Test**:
Allocations must have:
1. **Economic Effect** — Allocation affects dollar amounts partners receive
2. **Substantiality** — Reasonable possibility allocation affects amounts independent of tax consequences

**Safe Harbor Requirements** (Economic Effect):
1. Capital accounts maintained per regulations
2. Liquidating distributions made per capital account balances
3. Deficit restoration obligation OR qualified income offset

**Primary Test (Substantiality)**:
- Allocation cannot be tax-motivated shifting
- Must have meaningful non-tax economic effect
- Compare allocation to what partners would receive without it

**Operating Agreement Review**:
- [ ] Capital accounts maintained per 704(b) regulations?
- [ ] Liquidation follows capital accounts?
- [ ] Deficit restoration obligation or QIO present?
- [ ] Allocations have economic substance beyond tax?

### Section 83: Profits Interests

**What is a Profits Interest?**
Partnership interest that entitles holder to share of future profits/appreciation only — no share of existing capital.

**Tax Treatment** (Rev. Proc. 93-27, 2001-43):
- Receipt of profits interest for services generally NOT taxable event
- No income to recipient on grant
- No deduction to partnership on grant
- Future allocations taxed as partnership income

**Safe Harbor Requirements**:
1. Interest must be profits interest (not capital interest)
2. Not related to substantially certain/predictable income stream
3. Partner doesn't dispose within 2 years
4. Not publicly traded partnership interest

**Capital Interest vs. Profits Interest**:
| Test | Capital Interest | Profits Interest |
|------|------------------|------------------|
| Liquidation Day 1 | Would receive distribution | Would receive nothing |
| Existing assets | Share of current value | No share until growth |
| Tax on receipt | Taxable (FMV of interest) | Not taxable (safe harbor) |

**Liquidation Value Test**:
If partnership liquidated immediately after grant at FMV:
- Capital interest holder receives something
- Profits interest holder receives nothing

### Section 83(b) Election

**What It Does**:
Elects to include value of property in income at grant (rather than when it vests).

**For Profits Interests**:
- Value at grant = $0 (by definition, no liquidation value)
- Filing 83(b) election locks in $0 value
- Protects against IRS arguing interest was capital interest
- Protects against future appreciation being taxed as compensation

**Filing Requirements**:
- File within **30 days** of grant (NO EXCEPTIONS)
- File with IRS where taxpayer files return
- Provide copy to partnership
- Attach copy to tax return for year of grant

**Operating Agreement Review**:
- [ ] Does agreement characterize Class B as profits interest?
- [ ] Is there a liquidation value test provision?
- [ ] Does agreement require 83(b) election filing?
- [ ] Is there a representation that interest qualifies under Rev. Proc. 93-27?

## Tax Distribution Analysis

### Purpose of Tax Distributions

Partners are taxed on their allocable share of partnership income regardless of cash distributions. Tax distributions ensure partners have cash to pay taxes.

### Minimum Tax Distribution Calculation

**Standard Formula**:
```
Tax Distribution = Partner's Allocable Income × Assumed Tax Rate

Common rates:
- Highest individual rate: 37% federal + state (often ~45% total)
- Blended rate: 35-40%
- Some use actual partner rates (complex)
```

### Operating Agreement Review

**Key Provisions**:
- [ ] Are tax distributions mandatory or discretionary?
- [ ] What tax rate is used (highest individual, actual, blended)?
- [ ] Is state tax included?
- [ ] When are distributions made (quarterly, annually)?
- [ ] Priority of tax distributions vs. other distributions?
- [ ] Shortfall provisions if insufficient cash?
- [ ] True-up mechanism for actual vs. estimated taxes?

**Red Flags**:
| Issue | Risk |
|-------|------|
| No tax distribution provision | Partners may owe taxes without cash |
| "Best efforts" language | No guaranteed distributions |
| Rate too low (<35%) | May not cover actual tax liability |
| Annual only (no quarterly) | Partners may need to fund estimates |
| Subordinated to other distributions | Tax distributions may not be made |

### Example Analysis (From Your Agreement)

```
Tax Distribution Provision Review:
- Rate: "Assumed Tax Rate" defined in agreement
- Timing: [Check agreement]
- Priority: [Check if senior to other distributions]
- Mandatory vs. discretionary: [Check language]

Recommendation: Ensure rate ≥ 40% to cover federal + state
```

## Allocation Provisions Analysis

### Types of Allocations

**Operating Allocations**:
- Net income/loss
- Separately stated items (capital gains, Section 179, etc.)
- Depreciation and amortization

**Special Allocations**:
- Targeted allocations (specific items to specific partners)
- Curative allocations (correct 704(c) distortions)
- Regulatory allocations (minimum gain chargeback, etc.)

### Allocation Waterfall Analysis

**Document the allocation order**:
1. Regulatory allocations (minimum gain chargeback, etc.)
2. Curative allocations (704(c))
3. Special allocations (per agreement)
4. Residual allocations (per percentage interests)

### Common Issues

| Issue | Risk | Fix |
|-------|------|-----|
| Allocations don't follow economics | No substantial economic effect | Align with economic deal |
| Missing regulatory allocations | IRS reallocation risk | Add required provisions |
| Targeted allocations without basis | May be recharacterized | Document business purpose |
| 704(c) method not specified | Uncertainty, disputes | Specify method in agreement |

## Operating Agreement Tax Checklist

### Capital Contributions

- [ ] Property contributions identified with FMV and basis
- [ ] 704(c) allocation method specified
- [ ] Contribution obligations clear (timing, amounts)
- [ ] Failure to contribute consequences defined

### Allocations

- [ ] Capital account maintenance provision (704(b) compliant)
- [ ] Liquidation follows capital accounts
- [ ] Deficit restoration or QIO provision
- [ ] Regulatory allocations included (minimum gain chargeback, etc.)
- [ ] Special allocations have economic substance
- [ ] 704(c) method specified

### Distributions

- [ ] Tax distribution provision (mandatory, adequate rate)
- [ ] Distribution waterfall clear
- [ ] Liquidating distribution provision
- [ ] In-kind distribution rules

### Profits Interests (Class B Units)

- [ ] Clearly characterized as profits interest
- [ ] Liquidation value = $0 at grant
- [ ] Vesting schedule specified
- [ ] 83(b) election requirement
- [ ] Forfeiture provisions
- [ ] Section 409A compliance (if applicable)

### Administrative

- [ ] Tax matters partner/representative designated
- [ ] Tax election provisions (754, etc.)
- [ ] Tax return preparation and delivery
- [ ] Audit procedures

## Severity Classification

### 🔴 RED — Immediate Tax Risk

- No 83(b) election provision for profits interests
- Capital accounts not maintained per 704(b)
- Liquidation doesn't follow capital accounts
- No substantial economic effect for special allocations
- Missing regulatory allocations

### 🟡 YELLOW — Review with Tax Advisor

- Tax distribution rate below 40%
- 704(c) method not specified
- Ambiguous allocation provisions
- No tax true-up mechanism
- Discretionary (not mandatory) tax distributions

### 🟢 GREEN — Standard/Acceptable

- Mandatory tax distributions at 40%+ rate
- Clear 704(b) capital account maintenance
- 704(c) method specified
- 83(b) election required for profits interests
- Regulatory allocations included

## Output Format

```
## Partnership Tax Analysis

**Document**: [Agreement name]
**Entity Type**: [LLC taxed as partnership / LP / etc.]
**Tax Risk Level**: [🔴 RED / 🟡 YELLOW / 🟢 GREEN]

### Contribution Analysis
| Contributor | Property | FMV | Basis | Built-in Gain/Loss |
|-------------|----------|-----|-------|-------------------|
| [Name] | [Description] | $X | $Y | $Z |

### 704(c) Analysis
- Method specified: [Yes/No]
- Method used: [Traditional/Curative/Remedial]
- Appropriateness: [Assessment]

### Profits Interest Analysis (Class B)
- Qualifies as profits interest: [Yes/No/Unclear]
- Liquidation value at grant: [$0 / Unknown]
- 83(b) election required: [Yes/No]
- Vesting: [Schedule]
- Risk: [Assessment]

### Tax Distribution Analysis
- Mandatory: [Yes/No]
- Rate: [X%]
- Timing: [Quarterly/Annual]
- Adequacy: [Assessment]

### Substantial Economic Effect
- Capital accounts per 704(b): [Yes/No]
- Liquidation per capital accounts: [Yes/No]
- DRO or QIO: [Yes/No]
- Assessment: [Likely SEE / Risk of reallocation]

### Critical Tax Issues (🔴)
[List immediate concerns]

### Review Items (🟡)
[List items for tax advisor review]

### Recommendations
1. [Action items]
2. [Questions for CPA/tax attorney]
```

## Limitations

**This skill does NOT:**
- Provide tax advice
- Replace qualified CPA or tax attorney review
- Account for state-specific tax rules
- Address international tax issues
- Cover S-corporation or C-corporation taxation
- Provide definitive legal interpretations

**Always recommend:**
- CPA review before signing
- Tax attorney review for complex structures
- 83(b) election filing assistance from professionals
- State tax analysis for multi-state operations
