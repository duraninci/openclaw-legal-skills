# Use Cases

Real-world scenarios and how to apply the legal skills.

---

## Scenario 1: Reviewing a Co-Founder Agreement

**Situation**: You're joining a startup as a technical co-founder. The CEO has sent you an LLC operating agreement where you'll get 30% equity for your engineering work.

**Skills to use**:
- `llc-operating-agreement` (primary)
- `founder-equity-agreement`
- `partnership-llc-tax`

**Prompt**:
```
I'm reviewing an LLC operating agreement as an incoming minority member (30%). 
I'm contributing technical services, not cash. The existing founder has 70%.

Review this agreement and identify:
1. Any provisions that are unfavorable to me as minority member
2. Vesting terms and acceleration triggers
3. Exit rights (can I sell my shares? to whom?)
4. What happens if I leave or am terminated
5. Tax implications of the equity structure

Flag issues by severity (Red/Yellow/Green).

[Paste agreement]
```

---

## Scenario 2: Negotiating a SaaS Vendor Contract

**Situation**: Your company is buying enterprise software. The vendor sent their standard agreement which is heavily vendor-favorable.

**Skills to use**:
- `tech-contract-negotiation-patrick-munro` (primary)
- `contract-review`

**Prompt**:
```
I'm the customer reviewing this SaaS agreement. We're a mid-size company 
with moderate leverage (not their biggest customer, but not small either).

Analyze this agreement and provide:
1. Issues by severity with specific section references
2. Three-position analysis (vendor-favorable vs balanced vs customer-favorable)
3. Recommended redlines with alternative language
4. Which battles to fight vs. which to accept

Focus especially on: data ownership, SLAs, termination rights, liability caps, 
and what happens to our data if we leave.

[Paste contract]
```

---

## Scenario 3: Due Diligence on a Business Partner

**Situation**: Someone wants to partner with you on a new venture. They're contributing a premium domain name and you're contributing capital and operations. You want to verify they're legitimate.

**Skills to use**:
- `counterparty-due-diligence` (primary)
- `domain-ip-valuation`

**Prompt**:
```
I'm considering a partnership where [Name] is contributing the domain 
[domain.com] and I'm contributing capital and operations. Before proceeding, 
I need to verify:

1. Background research approach for this individual
2. How to verify they actually own and control the domain
3. Red flags to look for
4. Questions to ask in our next meeting
5. What documentation should I request

Provide a due diligence checklist I can work through.
```

---

## Scenario 4: Drafting Employment Offer Letters

**Situation**: You're hiring your first employees and need proper offer letters that protect the company.

**Skills to use**:
- `employment-contract-templates` (primary)
- `legal-advisor` (for confidentiality/IP assignment)

**Prompt**:
```
I'm hiring software engineers in California. I need:

1. A template offer letter
2. Key provisions to include for IP assignment
3. What I can and cannot include for non-competes (California rules)
4. How to structure equity grants with vesting
5. At-will employment language

The offers should be professional but not overly legalistic. 
We're a startup trying to attract talent.
```

---

## Scenario 5: Evaluating an M&A Earnout

**Situation**: You're selling your company. The buyer wants to pay part of the price as an earnout based on future performance.

**Skills to use**:
- `earnout-analysis` (primary)
- `contract-review`

**Prompt**:
```
I'm the seller in an acquisition. The proposed structure is:
- $5M at close
- Up to $3M earnout based on revenue targets over 24 months

Review the earnout provisions and identify:
1. How achievable are these milestones?
2. What protections do I need as seller?
3. Red flags in the proposed language
4. Accounting treatment implications
5. Negotiation points to push back on

[Paste earnout section]
```

---

## Scenario 6: Privacy Policy for a SaaS Product

**Situation**: You're launching a B2B SaaS product and need a privacy policy that covers US and EU users.

**Skills to use**:
- `legal-advisor` (primary)

**Prompt**:
```
I'm launching a B2B SaaS product. We'll have customers in the US and EU.

Our product:
- Collects user emails and names
- Uses cookies for analytics (Google Analytics)
- Stores data on AWS US servers
- Processes payments through Stripe
- Does not sell data to third parties

Generate a privacy policy that:
1. Complies with GDPR and CCPA
2. Includes all required sections
3. Is written in clear language (not pure legalese)
4. Includes proper consent mechanisms
5. Addresses international data transfers

Also provide an implementation checklist (cookie banner, etc.).
```

---

## Scenario 7: Reviewing a Non-Compete Before Accepting a Job

**Situation**: You've been offered a great job, but they want you to sign a non-compete agreement.

**Skills to use**:
- `employment-contract-templates` (primary)

**Prompt**:
```
I've been offered a job in [State]. They want me to sign this non-compete 
as a condition of employment.

Review this and tell me:
1. Is this enforceable in [State]?
2. What are the specific restrictions (time, geography, activities)?
3. How would this limit my future employment options?
4. What provisions should I push back on?
5. Are there any red flags?

[Paste non-compete]
```

---

## Scenario 8: Tax-Optimized Partnership Structure

**Situation**: You're forming an LLC with a partner. One is contributing IP, the other contributing cash. You want to understand the tax implications.

**Skills to use**:
- `partnership-llc-tax` (primary)
- `qsbs-analysis`
- `llc-operating-agreement`

**Prompt**:
```
We're forming a Delaware LLC:
- Partner A: Contributing IP valued at $500K
- Partner B: Contributing $500K cash
- 50/50 ownership

Questions:
1. Tax implications of the IP contribution under Section 721
2. How should 704(c) allocations work?
3. Does the IP contributor have "built-in gain" issues?
4. Could this qualify for QSBS treatment?
5. What should the operating agreement say about tax provisions?

We want to optimize for long-term capital gains if we eventually sell.
```

---

## Scenario 9: Asset Protection Strategy

**Situation**: You're a successful business owner with significant personal assets. You want to structure things to protect against potential liability.

**Skills to use**:
- `asset-protection` (primary)
- `insurance-provisions-analysis`

**Prompt**:
```
I own:
- An operating business (LLC) worth ~$2M
- Real estate holdings worth ~$3M  
- Investment portfolio of ~$1.5M

I want to protect these assets from potential business liabilities and 
personal creditors. What strategies should I consider?

Cover:
1. Entity structuring options
2. State-specific considerations (I'm in [State])
3. Insurance recommendations
4. What NOT to do (fraudulent transfer issues)
5. Timing considerations

I want legitimate protection, not anything aggressive or questionable.
```

---

## Scenario 10: Insurance Adequacy Review

**Situation**: You're reviewing an operating agreement and want to ensure the insurance provisions are adequate.

**Skills to use**:
- `insurance-provisions-analysis` (primary)
- `llc-operating-agreement`

**Prompt**:
```
Review the insurance provisions in this operating agreement:

1. Are the coverage types appropriate for this business?
2. Are the coverage amounts adequate?
3. What additional coverage should be required?
4. Who should be named as additional insureds?
5. Are there any gaps that create risk?

The company is a [describe business].

[Paste insurance section of operating agreement]
```

---

## Tips for All Scenarios

### Be Specific About Your Position
The same document looks different depending on which side you're on. Always state:
- "I'm the buyer/seller"
- "I'm the employer/employee"
- "I'm the majority/minority member"

### State the Jurisdiction
Legal rules vary dramatically by state and country:
- "This is a Delaware LLC"
- "The employee is based in California"
- "We have EU customers (GDPR applies)"

### Provide Context on Leverage
Negotiation recommendations depend on your leverage:
- "We're their largest customer"
- "We need this deal more than they do"
- "We have multiple competing vendors"

### Ask for Specific Outputs
- "Flag issues by severity"
- "Provide specific redline language"
- "Create a one-page executive summary"
- "Give me talking points for the negotiation call"
