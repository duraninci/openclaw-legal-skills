# Legal Skills for AI Assistants

[![Skills](https://img.shields.io/badge/skills-18-blue)](./skills)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-orange)](https://claude.ai)
[![Battle Tested](https://img.shields.io/badge/Battle%20Tested-10%2B%20M%26A%20Deals-purple)]()

A comprehensive collection of legal analysis skills for AI assistants. These skills enable LLMs to provide structured legal analysis, document review, and drafting assistance across contracts, corporate law, tax planning, and compliance.

> ⚠️ **Disclaimer**: These skills are educational tools, NOT legal advice. See [LEGAL_DISCLAIMER.md](./LEGAL_DISCLAIMER.md) for full terms. Always consult qualified attorneys.

---

## 🏆 Battle-Tested in Real Transactions

**These aren't theoretical templates.** This skill set was developed and refined through hands-on experience analyzing:

### Training & Experience Foundation

| Category | Volume | What We Learned |
|----------|--------|-----------------|
| **Contracts Analyzed** | 1,000+ | Pattern recognition across industries—SaaS, manufacturing, professional services, ecommerce |
| **M&A Transactions** | 10+ | Earnout structures, asset vs. stock deals, rep & warranty nuances, indemnification caps |
| **LLC/Partnership Agreements** | 50+ | Distribution waterfalls, buy-sell triggers, majority vs. minority positioning |
| **Negotiated Deals** | 100+ | What actually gets redlined, market-standard fallbacks, leverage dynamics |
| **Due Diligence Reviews** | 25+ | Red flags that matter, deal-breaker patterns, integration risk factors |

### What Makes These Skills Different

❌ **Generic legal templates** — Copy-pasted clauses with no context  
✅ **These skills** — Built from analyzing what actually happens in negotiations

**We've seen:**
- The earnout provisions that lead to litigation (and the ones that don't)
- How minority members get squeezed in operating agreements
- Which "market standard" terms are actually negotiable
- Tax structures that save millions vs. cost millions
- Due diligence findings that kill deals vs. get waived

**This experience is encoded into every skill:**
- Position-aware analysis (majority vs. minority, buyer vs. seller)
- Specific redline suggestions with fallback positions
- Risk ratings calibrated to real transaction outcomes
- Market-standard benchmarks from actual deal data

---

## 🎯 What's Included

### Contract Review & Negotiation
| Skill | Description |
|-------|-------------|
| [contract-review](./skills/contract-review) | General contract analysis with issue spotting |
| [contract-review-anthropic](./skills/contract-review-anthropic) | Playbook-based contract review against company standards |
| [tech-contract-negotiation](./skills/tech-contract-negotiation-patrick-munro) | SaaS/technology services negotiation frameworks |

### Corporate & Partnership
| Skill | Description |
|-------|-------------|
| [llc-operating-agreement](./skills/llc-operating-agreement) | LLC/partnership agreement analysis with position-aware review |
| [founder-equity-agreement](./skills/founder-equity-agreement) | Co-founder equity splits, vesting, acceleration |
| [earnout-analysis](./skills/earnout-analysis) | M&A earnout and contingent consideration structures |
| [deferred-contribution-structures](./skills/deferred-contribution-structures) | Delayed contribution arrangements for partnerships |

### Tax Planning
| Skill | Description |
|-------|-------------|
| [partnership-llc-tax](./skills/partnership-llc-tax) | Section 721, 704(b), 704(c), 83(b) elections |
| [qsbs-analysis](./skills/qsbs-analysis) | Qualified Small Business Stock (Section 1202) |

### Due Diligence
| Skill | Description |
|-------|-------------|
| [counterparty-due-diligence](./skills/counterparty-due-diligence) | Background research on business partners |
| [vendor-due-diligence](./skills/vendor-due-diligence-patrick-munro) | IT vendor and third-party risk assessment |
| [legal-risk-assessment](./skills/legal-risk-assessment-anthropic) | Risk classification and escalation framework |

### Asset Protection & IP
| Skill | Description |
|-------|-------------|
| [asset-protection](./skills/asset-protection) | Charging order protection, entity structuring |
| [domain-ip-valuation](./skills/domain-ip-valuation) | Premium domain and IP asset valuation |
| [ip-licensing-agreement](./skills/ip-licensing-agreement) | IP and domain licensing structures |
| [insurance-provisions-analysis](./skills/insurance-provisions-analysis) | Key person, D&O, coverage adequacy |

### Employment & Compliance
| Skill | Description |
|-------|-------------|
| [employment-contract-templates](./skills/employment-contract-templates) | Offer letters, agreements, non-competes, severance |
| [legal-advisor](./skills/legal-advisor) | Privacy policies, ToS, GDPR/CCPA compliance |

---

## 💡 Real-World Use Cases

### Scenario 1: Reviewing an Incoming Operating Agreement
You're offered 25% equity in a new venture. The majority member sends you a 40-page operating agreement.

**Use:** `llc-operating-agreement` skill
**Output:** Position-aware analysis highlighting:
- Distribution waterfall favoring majority (concern level: HIGH)
- Buy-sell trigger giving majority put option at book value (concern level: CRITICAL)
- Governance provisions requiring supermajority for major decisions (concern level: MEDIUM)
- Suggested redlines with fallback positions

### Scenario 2: M&A Earnout Negotiation
You're selling your company. Buyer proposes 40% of purchase price as a 3-year earnout tied to revenue targets.

**Use:** `earnout-analysis` skill
**Output:** 
- Risk assessment of earnout structure
- Historical data on earnout achievement rates
- Specific provisions to negotiate (accounting standards, integration covenants)
- Alternative structures to propose

### Scenario 3: QSBS Tax Planning
You're structuring equity grants and want to maximize tax benefits under Section 1202.

**Use:** `qsbs-analysis` skill
**Output:**
- Eligibility checklist for your company
- Optimal timing for grants and contributions
- Holding period planning
- Stacking strategies for multiple shareholders

---

## 🚀 Quick Start

### With Claude (claude.ai)

1. Download the skill you need
2. Add to your Claude Project's knowledge base
3. Reference it in your conversation

### With Claude Code / OpenClaw

1. Clone this repo to your workspace:
```bash
git clone https://github.com/duraninci/openclaw-legal-skills.git ~/skills/legal-skills
```

2. Skills auto-load from `skills/` directory, or reference directly:
```
Review this operating agreement using ~/skills/legal-skills/skills/llc-operating-agreement/SKILL.md
```

### With Cursor / Continue

Add to your `.cursorrules` or project instructions:
```
When reviewing legal documents, load the relevant skill from ./legal-skills/skills/
```

---

## 📖 Documentation

- [Getting Started](./docs/GETTING-STARTED.md) — Installation and usage
- [Skill Index](./docs/SKILL-INDEX.md) — Detailed descriptions of each skill
- [Use Cases](./docs/USE-CASES.md) — Real-world scenarios and examples

## 📂 Repository Structure

```
legal-skills/
├── README.md
├── LICENSE
├── ATTRIBUTION.md
├── skills/
│   ├── contract-review/
│   │   ├── SKILL.md
│   │   └── examples/
│   ├── llc-operating-agreement/
│   │   └── SKILL.md
│   └── [16 more skills...]
├── examples/
│   ├── nda-review-example.md
│   ├── saas-agreement-example.md
│   └── ...
└── docs/
    ├── GETTING-STARTED.md
    ├── SKILL-INDEX.md
    └── USE-CASES.md
```

## 🤝 Contributing

Contributions welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Follow the existing skill format
4. Submit a pull request

## 📜 License

- Original skills: [MIT License](./LICENSE)
- Anthropic-sourced skills: Apache 2.0
- Patrick Munro frameworks: CC-BY (see [ATTRIBUTION.md](./ATTRIBUTION.md))

## ⚠️ Disclaimer

These skills are educational tools that assist with legal analysis. They are **NOT legal advice** and are **NOT a substitute for professional legal counsel**. 

By using these materials, you agree to the terms in [LEGAL_DISCLAIMER.md](./LEGAL_DISCLAIMER.md). Always consult qualified attorneys for legal decisions.

---

## 🔗 Related Projects

- [OpenClaw](https://github.com/openclaw/openclaw) — The AI agent framework
- [RookOS](https://github.com/duraninci/rookos) — AI Agent Command Center
- [OpenClaw Token Optimization](https://github.com/duraninci/openclaw-token-optimization) — Reduce AI costs by 90%

---

**Created by** [Duran Inci](https://github.com/duraninci) — Built from real transactions, not textbooks.
