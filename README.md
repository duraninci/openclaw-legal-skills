# Legal Skills for AI Assistants

[![Skills](https://img.shields.io/badge/skills-18-blue)](./skills)
[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Claude Compatible](https://img.shields.io/badge/Claude-Compatible-orange)](https://claude.ai)

A comprehensive collection of legal analysis skills for AI assistants. These skills enable LLMs to provide structured legal analysis, document review, and drafting assistance across contracts, corporate law, tax planning, and compliance.

> **Disclaimer**: These skills assist with legal analysis but do not provide legal advice. All output should be reviewed by qualified legal professionals.

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

## 🚀 Quick Start

### With Claude (claude.ai)

1. Download the skill you need
2. Add to your Claude Project's knowledge base
3. Reference it in your conversation

### With Claude Code / OpenClaw

1. Clone this repo to your workspace:
```bash
git clone https://github.com/duraninci/legal-skills.git ~/skills/legal-skills
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

These skills are educational tools that assist with legal analysis. They are NOT a substitute for professional legal advice. Always consult qualified attorneys for legal decisions.

---

**Created by** [Duran Inci](https://github.com/duraninci)
