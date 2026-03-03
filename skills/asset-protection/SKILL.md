---
name: asset-protection
description: "Analyze asset protection structures for business owners including charging order protection, entity structuring, liability shields, and creditor-proofing strategies. Use when: (1) Structuring partnerships to protect against partner liabilities, (2) Evaluating LLC vs. corporation for asset protection, (3) Analyzing charging order protections, (4) Reviewing agreements for liability exposure, or (5) Planning structures to separate personal and business assets."
metadata:
  author: Rook (Custom Build)
  license: MIT
  version: 2026.02.28
  sources:
    - "Asset Protection Law"
    - "LLC Statutes by State"
    - "Fraudulent Transfer Law"
---

# Asset Protection Analysis Skill

You analyze business structures and agreements for asset protection, helping identify liability exposures and recommending protective structures.

**Important**: Asset protection planning must be done proactively, before claims arise. Transfer of assets to avoid existing creditors can be fraudulent transfer. All planning must be reviewed by qualified attorneys.

## Asset Protection Fundamentals

### The Goal

Protect assets from:
1. **Personal creditors** reaching business assets
2. **Business creditors** reaching personal assets
3. **Partner's creditors** reaching your share
4. **Your creditors** reaching partner's share or business

### Key Concepts

| Concept | Definition |
|---------|------------|
| **Charging Order** | Creditor's remedy against LLC/partnership interest — only gets distributions |
| **Foreclosure** | Creditor can force sale of asset |
| **Inside Liability** | Claims arising from business operations |
| **Outside Liability** | Claims against owner personally (not from business) |
| **Veil Piercing** | Court ignores entity protection due to abuse |
| **Fraudulent Transfer** | Moving assets to avoid creditors (illegal) |

## Entity Comparison for Asset Protection

### LLC vs. Corporation vs. Partnership

| Factor | LLC | Corporation | General Partnership |
|--------|-----|-------------|---------------------|
| **Personal liability for business debts** | Protected | Protected | NOT Protected |
| **Charging order protection** | ✅ Strong (varies by state) | ❌ Weak (stock can be seized) | ⚠️ Varies |
| **Inside liability shield** | ✅ Yes | ✅ Yes | ❌ No |
| **Outside liability shield** | ✅ Yes (charging order) | ❌ No (stock seizure) | ⚠️ Limited |
| **Veil piercing risk** | Medium | Medium | N/A |

### Charging Order Protection Explained

**What is a Charging Order?**

When a creditor obtains judgment against an LLC member personally, the creditor can get a "charging order" against the member's LLC interest.

**What Charging Order DOES:**
- Creditor receives distributions that would have gone to debtor-member
- Creditor must report distributions as income (even if not received)
- Creditor becomes an "assignee" — no voting or management rights

**What Charging Order DOES NOT (in strong protection states):**
- Creditor CANNOT force LLC to make distributions
- Creditor CANNOT force sale of the LLC interest
- Creditor CANNOT access LLC assets directly
- Creditor CANNOT participate in management

**This creates "reverse pressure":**
- Creditor has phantom income (tax liability) without cash
- Creditor may be willing to settle for less than full claim

### State-by-State Charging Order Protection

| Protection Level | States | Description |
|------------------|--------|-------------|
| **Strongest** | Wyoming, Nevada, Delaware, South Dakota | Charging order is EXCLUSIVE remedy; cannot foreclose |
| **Strong** | Arizona, Florida, Texas, Alaska | Charging order exclusive for multi-member LLCs |
| **Moderate** | Most states | Charging order primary remedy; foreclosure possible in some cases |
| **Weak** | California, New York | Courts have allowed foreclosure in some cases |

**Delaware LLC Statute (Example):**
> "The entry of a charging order is the exclusive remedy by which a judgment creditor of a member or of a member's assignee may satisfy a judgment out of the judgment debtor's limited liability company interest."

### Single-Member LLC Risk

**Warning:** Single-member LLCs have WEAKER protection in many states.

| State | SMLLC Charging Order Protection |
|-------|--------------------------------|
| Wyoming | ✅ Protected |
| Nevada | ✅ Protected |
| Delaware | ✅ Protected |
| Florida | ❌ NOT protected (Olmstead case) |
| California | ❌ NOT protected |
| Colorado | ❌ NOT protected |

**Solution:** Add a second member (spouse, trust, holding company) to convert SMLLC to multi-member.

## Protecting Against Partner's Creditors

### The Risk

**Scenario:** You're in business with a partner. Partner gets sued personally (car accident, divorce, failed side business). Can partner's creditor take:
- The business?
- Your share?
- Business assets?

### Protections in Operating Agreement

**Essential Provisions:**

```
1. CHARGING ORDER AS EXCLUSIVE REMEDY

To the fullest extent permitted by applicable law, a charging order 
shall be the sole and exclusive remedy available to a creditor of a 
Member or Assignee with respect to such Member's or Assignee's 
Membership Interest.

2. NO FORECLOSURE

No creditor of a Member shall have any right to foreclose upon, 
partition, or force sale of a Member's Membership Interest.

3. NO CREDITOR RIGHTS

A creditor with a charging order shall have no right to:
(a) Participate in management of the Company;
(b) Vote on any matter;
(c) Access books and records;
(d) Become a Member or Assignee except as permitted herein;
(e) Interfere with Company operations.

4. DISTRIBUTION DISCRETION

The Managers shall have sole discretion regarding the timing and 
amount of distributions. Nothing in this Agreement shall require 
the Company to make any distribution.

5. MANDATORY REDEMPTION ON CHARGING ORDER

If a charging order is entered against a Member's interest, the 
Company shall have the right (but not obligation) to redeem such 
interest at [fair market value / formula price / X% of book value].

6. INVOLUNTARY TRANSFER RESTRICTIONS

No Member's interest may be transferred, whether voluntarily or 
involuntarily, including by operation of law, court order, or 
charging order, without [unanimous consent / Manager approval].
```

### Additional Structural Protections

**1. Holding Company Structure:**
```
Instead of:
[Partner A] ←→ [Operating LLC] ←→ [Partner B]

Use:
[Partner A] → [A's Holding LLC] ←→ [Operating LLC] ←→ [B's Holding LLC] ← [Partner B]
```
- Each partner holds interest through their own LLC
- Adds additional layer of charging order protection
- Partner's personal creditor must go through two layers

**2. Series LLC (where available):**
- Wyoming, Delaware, Illinois, Texas, Nevada
- Each series is separate for liability purposes
- Assets in one series protected from other series' creditors

**3. Spendthrift Provisions (for trusts):**
- If partner holds through trust, add spendthrift clause
- Prevents creditors from reaching trust assets
- Must be properly structured

## Protecting Business Assets from Personal Creditors

### Inside vs. Outside Liability

**Inside Liability:** 
- Claims arising FROM the business
- Example: Customer sues for product defect
- Business assets are at risk
- Your personal assets protected (if proper structure)

**Outside Liability:**
- Claims against you PERSONALLY
- Example: Car accident, personal guarantee, divorce
- Charging order protection applies
- Business operates normally

### Operating Agreement Provisions

```
PERSONAL LIABILITY SHIELD

1. No Member shall be personally liable for any debt, obligation, 
or liability of the Company, whether arising in contract, tort, 
or otherwise.

2. No Member shall be required to make any contribution to the 
Company to satisfy Company obligations.

3. No creditor of the Company shall have any right to proceed 
against any Member personally for any Company obligation.
```

### Avoiding Veil Piercing

**Courts may "pierce the veil" (ignore LLC protection) if:**
- Entity is alter ego of owner
- Inadequate capitalization
- Commingling of funds
- Failure to observe formalities
- Fraud or injustice

**Best Practices to Maintain Protection:**
| Practice | Description |
|----------|-------------|
| Separate accounts | Business has own bank accounts |
| Proper capitalization | Business has adequate funding |
| Maintain records | Operating agreement, meeting minutes, resolutions |
| Sign properly | "John Doe, Manager of XYZ LLC" not just "John Doe" |
| No commingling | Don't pay personal expenses from business |
| Observe formalities | Hold meetings, document decisions |
| Insurance | Maintain appropriate coverage |

## Liability Exposure in Partnership Agreements

### Red Flags to Look For

| Red Flag | Risk |
|----------|------|
| **Cross-guarantees** | You're liable for partner's obligations |
| **Joint and several liability** | Each partner liable for full amount |
| **Personal guarantees of company debt** | Pierces LLC protection |
| **Weak transfer restrictions** | Creditor could become your partner |
| **No charging order language** | Court may not apply protection |
| **Mandatory distributions** | Creditor will receive cash |

### Protective Provisions

**1. Indemnification:**
```
INDEMNIFICATION

Each Member shall indemnify and hold harmless the Company and the 
other Members from and against any and all claims, liabilities, 
losses, and expenses arising from:
(a) Such Member's breach of this Agreement;
(b) Such Member's negligence or willful misconduct;
(c) Any personal obligation or liability of such Member;
(d) Any judgment, lien, or encumbrance against such Member's interest.
```

**2. Insurance Requirements:**
```
INSURANCE

Each Member shall maintain:
(a) Personal liability insurance of at least $[X];
(b) Professional liability insurance (if applicable);
(c) Such other insurance as the Managers reasonably require.

Failure to maintain required insurance shall constitute a material 
breach of this Agreement.
```

**3. Buy-Out on Creditor Event:**
```
BUY-OUT ON CREDITOR EVENT

If any of the following occurs with respect to a Member:
(a) Entry of a charging order against such Member's interest;
(b) Bankruptcy filing by or against such Member;
(c) Assignment for benefit of creditors;
(d) Attachment or levy on such Member's interest;

Then the Company and/or other Members shall have the option to 
purchase such Member's interest at [fair market value / formula / 
X% discount] payable over [X] months.
```

## Bankruptcy Considerations

### Member Bankruptcy

**Chapter 7 (Liquidation):**
- Trustee steps into member's shoes
- Gets charging order protection (same as creditor)
- Cannot force distribution or sale (in strong states)
- LLC continues operating

**Chapter 11/13 (Reorganization):**
- Debtor remains in control
- Plan may address LLC interest
- Consult bankruptcy counsel

### Company Bankruptcy

**If the LLC files bankruptcy:**
- Members' personal assets still protected
- Unless personal guarantees exist
- Unless veil piercing applies

## Due Diligence Checklist

### For New Partnership/LLC

- [ ] State of formation (WY, NV, DE preferred)
- [ ] Multi-member structure (not SMLLC in weak states)
- [ ] Strong charging order language in operating agreement
- [ ] Discretionary distributions (not mandatory)
- [ ] Transfer restrictions
- [ ] Buy-out on creditor event provision
- [ ] Indemnification provisions
- [ ] Insurance requirements
- [ ] No cross-guarantees

### For Existing Partnership

- [ ] Current state of formation
- [ ] Current charging order protections
- [ ] Partner's financial situation (known risks?)
- [ ] Existing judgments or liens
- [ ] Insurance coverage adequate?
- [ ] Operating agreement protections present?
- [ ] Consider redomiciling to stronger state

## Output Format

```
## Asset Protection Analysis

**Entity:** [Name]
**State:** [Formation state]
**Structure:** [LLC/Corp/Partnership]
**Protection Level:** [🔴 WEAK / 🟡 MODERATE / 🟢 STRONG]

### Charging Order Protection
| Element | Status |
|---------|--------|
| Multi-member | [Yes/No] |
| Strong state | [Yes/No] |
| Exclusive remedy language | [Yes/No] |
| No foreclosure provision | [Yes/No] |

### Operating Agreement Review
| Provision | Present | Adequate |
|-----------|---------|----------|
| Charging order language | [Y/N] | [Y/N] |
| Distribution discretion | [Y/N] | [Y/N] |
| Transfer restrictions | [Y/N] | [Y/N] |
| Buy-out on creditor event | [Y/N] | [Y/N] |
| Indemnification | [Y/N] | [Y/N] |
| Insurance requirements | [Y/N] | [Y/N] |

### Risk Assessment
**Partner creditor risk:** [Low/Medium/High]
**Business creditor risk:** [Low/Medium/High]
**Veil piercing risk:** [Low/Medium/High]

### Recommendations
1. [Structural changes]
2. [Operating agreement amendments]
3. [Insurance additions]
4. [Questions for counsel]
```

## Limitations

**This skill does NOT:**
- Provide legal advice
- Replace asset protection attorney
- Address fraudulent transfer analysis
- Cover international asset protection
- Guarantee protection in all cases

**Always recommend:**
- Asset protection attorney for planning
- Proactive planning (before claims arise)
- Compliance with all formalities
- Regular review of structures
