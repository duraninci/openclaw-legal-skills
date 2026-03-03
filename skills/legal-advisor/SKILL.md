---
name: legal-advisor
description: "Draft privacy policies, terms of service, cookie policies, DPAs, and compliance documents for web/SaaS businesses. Covers GDPR, CCPA, LGPD, COPPA, CAN-SPAM, and ePrivacy. Use when: (1) Creating privacy policies for websites or apps, (2) Drafting terms of service, (3) Building cookie consent frameworks, (4) Creating data processing agreements, (5) Reviewing compliance requirements by jurisdiction."
metadata:
  author: Community
  license: MIT
  version: 2026.02.28
  sources:
    - "GDPR Official Text"
    - "CCPA/CPRA Regulations"
    - "ICO Guidance Documents"
    - "IAPP Resources"
    - "FTC Enforcement Guidance"
---

# Legal Advisor Skill — Privacy & Compliance

You draft privacy policies, terms of service, and compliance documentation for web and SaaS businesses across multiple jurisdictions.

**Important**: These are templates for informational purposes. Consult with a qualified attorney for legal advice specific to your situation.

## Jurisdiction Framework

### Primary Regulations

| Regulation | Jurisdiction | Key Requirements |
|------------|--------------|------------------|
| **GDPR** | EU/EEA | Consent, data rights, DPO, breach notification |
| **CCPA/CPRA** | California | Opt-out rights, "Do Not Sell", disclosure requirements |
| **LGPD** | Brazil | Similar to GDPR, legal bases, DPO requirement |
| **PIPEDA** | Canada | Consent, access rights, accountability |
| **UK DPA** | United Kingdom | Post-Brexit GDPR equivalent |
| **COPPA** | US (Children) | Parental consent under 13, data minimization |
| **CAN-SPAM** | US (Email) | Unsubscribe, physical address, no deceptive headers |
| **ePrivacy** | EU (Cookies) | Cookie consent, electronic communications |

### Jurisdiction Detection Questions

Ask these to determine applicable regulations:
1. Where is your business incorporated?
2. Where are your servers located?
3. Where are your users/customers located?
4. Do you target specific countries in marketing?
5. Do you process data of EU residents?
6. Do you have California users?
7. Do you collect data from children under 13?
8. Do you send marketing emails?

## Privacy Policy Framework

### Required Sections (Universal)

```markdown
# Privacy Policy

**Last Updated**: [Date]
**Effective Date**: [Date]

## 1. Introduction
- Company identity and contact information
- Scope of policy
- Acceptance of terms

## 2. Information We Collect
### 2.1 Information You Provide
- Account registration data
- Payment information
- Communications with us
- User-generated content

### 2.2 Information Collected Automatically
- Device information
- Log data
- Cookies and tracking technologies
- Location data (if applicable)

### 2.3 Information from Third Parties
- Social media logins
- Analytics providers
- Advertising partners

## 3. How We Use Your Information
- Provide and maintain services
- Process transactions
- Send communications
- Improve services
- Comply with legal obligations
- [List all purposes with legal basis for GDPR]

## 4. Legal Bases for Processing (GDPR)
- Consent
- Contract performance
- Legal obligation
- Legitimate interests
- Vital interests
- Public interest

## 5. Information Sharing and Disclosure
- Service providers
- Business transfers
- Legal requirements
- With your consent

## 6. Data Retention
- Retention periods by data type
- Criteria for determining retention
- Deletion procedures

## 7. Your Rights
[Varies by jurisdiction - see below]

## 8. International Data Transfers
- Transfer mechanisms (SCCs, adequacy decisions)
- Safeguards in place

## 9. Security Measures
- Technical safeguards
- Organizational measures
- Incident response

## 10. Children's Privacy
- Age restrictions
- COPPA compliance (if applicable)
- Parental consent procedures

## 11. Changes to This Policy
- Notification procedures
- Material change handling

## 12. Contact Information
- Data controller identity
- DPO contact (if required)
- How to exercise rights
```

### GDPR-Specific Rights Section

```markdown
## Your Rights (EEA Residents)

Under GDPR, you have the following rights:

### Right of Access (Article 15)
You may request a copy of your personal data.

### Right to Rectification (Article 16)
You may request correction of inaccurate data.

### Right to Erasure (Article 17)
You may request deletion of your data ("right to be forgotten").

### Right to Restrict Processing (Article 18)
You may request limitation of processing.

### Right to Data Portability (Article 20)
You may request your data in a machine-readable format.

### Right to Object (Article 21)
You may object to processing based on legitimate interests or direct marketing.

### Rights Related to Automated Decision-Making (Article 22)
You have the right not to be subject to decisions based solely on automated processing.

### Right to Withdraw Consent
Where processing is based on consent, you may withdraw at any time.

### Right to Lodge a Complaint
You may file a complaint with your local supervisory authority.

**To exercise these rights, contact us at**: [Email/Form]
**Response time**: Within 30 days (extendable by 60 days for complex requests)
```

### CCPA-Specific Rights Section

```markdown
## Your Rights (California Residents)

Under the California Consumer Privacy Act (CCPA) and California Privacy Rights Act (CPRA):

### Right to Know
You may request disclosure of:
- Categories of personal information collected
- Sources of collection
- Business purposes for collection
- Categories of third parties with whom we share
- Specific pieces of personal information collected

### Right to Delete
You may request deletion of personal information we collected.

### Right to Correct
You may request correction of inaccurate personal information.

### Right to Opt-Out
You may opt out of:
- Sale of personal information
- Sharing for cross-context behavioral advertising

### Right to Limit Use of Sensitive Personal Information
You may limit use of sensitive categories to specified purposes.

### Right to Non-Discrimination
We will not discriminate against you for exercising your rights.

**To exercise these rights**:
- Submit a request at: [Link]
- Call us at: [Phone number]
- Email: [Email]

**Verification**: We will verify your identity before processing requests.
**Authorized Agents**: You may designate an authorized agent with written permission.
**Response time**: Within 45 days (extendable by 45 days with notice)

### Categories We Collect
[Table of categories, sources, purposes, and sharing]

### "Do Not Sell or Share My Personal Information"
[Link to opt-out mechanism]
```

## Terms of Service Framework

### Required Sections

```markdown
# Terms of Service

**Last Updated**: [Date]
**Effective Date**: [Date]

## 1. Acceptance of Terms
- Binding agreement
- Age requirements
- Authority to bind entity (for business users)

## 2. Description of Service
- What the service does
- Service availability
- Beta/preview features

## 3. User Accounts
- Registration requirements
- Account security responsibilities
- Account termination

## 4. User Conduct
- Acceptable use policy
- Prohibited activities
- Content standards

## 5. User Content
- Ownership
- License grant to company
- Content moderation rights
- DMCA/takedown procedures

## 6. Intellectual Property
- Company IP ownership
- Trademark usage
- Feedback license

## 7. Third-Party Services
- Links to third parties
- Third-party integrations
- Disclaimer of responsibility

## 8. Payment Terms (if applicable)
- Pricing
- Billing
- Refunds
- Taxes

## 9. Termination
- User termination rights
- Company termination rights
- Effect of termination

## 10. Disclaimers
- "As is" / "As available"
- No warranties
- Service availability

## 11. Limitation of Liability
- Cap on damages
- Exclusion of consequential damages
- Jurisdictional variations

## 12. Indemnification
- User indemnification obligations
- Procedure for claims

## 13. Dispute Resolution
- Governing law
- Arbitration clause (if applicable)
- Class action waiver (if applicable)
- Forum selection

## 14. General Provisions
- Entire agreement
- Severability
- Waiver
- Assignment

## 15. Contact Information
```

### Key Clauses by Business Model

**SaaS/Subscription**:
- Subscription terms and renewals
- Automatic billing
- Service level commitments
- Data handling on termination
- API usage limits

**Marketplace/Platform**:
- User-to-user transaction terms
- Platform vs. seller responsibility
- Dispute resolution between users
- Fee structure
- Prohibited listings

**E-commerce**:
- Order acceptance
- Pricing errors
- Shipping and delivery
- Returns and refunds
- Product warranties

## Cookie Policy Framework

### Cookie Categories

| Category | Purpose | Consent Required |
|----------|---------|------------------|
| **Strictly Necessary** | Essential functionality | No |
| **Performance/Analytics** | Usage statistics | Yes (EU) |
| **Functionality** | User preferences | Yes (EU) |
| **Targeting/Advertising** | Personalized ads | Yes |

### Cookie Banner Requirements

**GDPR/ePrivacy Compliant Banner Must**:
- Appear before non-essential cookies are set
- Allow granular consent by category
- Provide equal prominence to "Accept" and "Reject"
- Not use dark patterns
- Be easily accessible to change preferences
- Store consent records

### Cookie Policy Template

```markdown
# Cookie Policy

**Last Updated**: [Date]

## What Are Cookies?
[Explanation of cookies and similar technologies]

## How We Use Cookies

### Strictly Necessary Cookies
| Cookie | Purpose | Duration |
|--------|---------|----------|
| session_id | User authentication | Session |
| csrf_token | Security | Session |

### Analytics Cookies
| Cookie | Provider | Purpose | Duration |
|--------|----------|---------|----------|
| _ga | Google Analytics | Traffic analysis | 2 years |
| _gid | Google Analytics | User distinction | 24 hours |

### Functionality Cookies
[Table of cookies]

### Advertising Cookies
[Table of cookies]

## Managing Your Preferences
- Browser settings
- Our preference center: [Link]
- Opt-out links for specific providers

## Changes to This Policy
[Update notification procedures]

## Contact Us
[Contact information]
```

## Data Processing Agreement (DPA) Framework

### When Required
- When you are a data controller using a processor
- When you are a processor for controllers
- Required under GDPR Article 28

### Required DPA Provisions

```markdown
# Data Processing Agreement

## 1. Definitions
- Personal Data
- Processing
- Data Controller
- Data Processor
- Data Subject
- Sub-processor

## 2. Subject Matter and Duration
- Nature of processing
- Purpose of processing
- Types of personal data
- Categories of data subjects
- Duration

## 3. Processor Obligations
- Process only on documented instructions
- Ensure personnel confidentiality
- Implement security measures (Article 32)
- Assist with data subject requests
- Assist with DPIA and prior consultation
- Delete or return data on termination
- Provide information for audits

## 4. Sub-processing
- Prior authorization requirement
- Sub-processor obligations
- Liability for sub-processors

## 5. Data Transfers
- Transfer mechanisms
- Adequacy decisions
- Standard Contractual Clauses
- Supplementary measures

## 6. Security Measures
- Technical measures (encryption, access controls)
- Organizational measures (training, policies)
- Regular testing and evaluation

## 7. Data Breach Notification
- Timing (without undue delay, max 72 hours)
- Information to provide
- Cooperation obligations

## 8. Audit Rights
- Controller audit rights
- Notice requirements
- Confidentiality of audit results

## 9. Liability and Indemnification
- Allocation of liability
- Indemnification provisions

## Annex A: Details of Processing
[Specific processing activities]

## Annex B: Technical and Organizational Measures
[Security measures in detail]

## Annex C: Sub-processors
[List of approved sub-processors]

## Annex D: Standard Contractual Clauses
[If applicable for international transfers]
```

## Compliance Checklists

### GDPR Compliance Checklist

- [ ] **Lawful Basis**: Identified legal basis for each processing activity
- [ ] **Privacy Policy**: Published and accessible
- [ ] **Consent**: Valid consent mechanisms where required
- [ ] **Data Subject Rights**: Procedures to handle requests
- [ ] **DPO**: Appointed if required (public authority, large scale monitoring, special categories)
- [ ] **Records of Processing**: Article 30 documentation
- [ ] **DPIAs**: Conducted for high-risk processing
- [ ] **Security**: Appropriate technical and organizational measures
- [ ] **Breach Procedures**: 72-hour notification process
- [ ] **Vendor Contracts**: DPAs with all processors
- [ ] **International Transfers**: Valid transfer mechanisms
- [ ] **Training**: Staff privacy awareness training

### CCPA Compliance Checklist

- [ ] **Privacy Policy**: Updated with CCPA disclosures
- [ ] **Notice at Collection**: Provided before or at collection
- [ ] **"Do Not Sell" Link**: On homepage (if selling data)
- [ ] **Request Mechanisms**: At least two methods
- [ ] **Verification Process**: Identity verification procedures
- [ ] **Response Procedures**: 45-day response timeline
- [ ] **Training**: Staff trained on CCPA requirements
- [ ] **Vendor Contracts**: Service provider agreements updated
- [ ] **Financial Incentive Notices**: If offering incentives for data

### Website Compliance Checklist

- [ ] Privacy Policy linked in footer
- [ ] Terms of Service linked in footer
- [ ] Cookie consent banner (for EU visitors)
- [ ] Cookie policy available
- [ ] Contact information visible
- [ ] Unsubscribe links in marketing emails
- [ ] Physical address in emails (CAN-SPAM)
- [ ] Age gate (if age-restricted content)
- [ ] Accessibility statement
- [ ] DMCA/copyright policy

## Output Format

When drafting documents, provide:

```
## [Document Type] for [Company Name]

**Prepared**: [Date]
**Jurisdictions**: [List applicable jurisdictions]
**Business Model**: [Description]

---

[Full document text]

---

## Implementation Notes
1. [Required customizations]
2. [Information to gather]
3. [Technical requirements]

## Compliance Checklist
- [ ] [Action items]

## Recommended Review Schedule
- Annual review
- After material business changes
- After regulatory updates
```

## Limitations

**This skill does NOT:**
- Provide legal advice
- Replace consultation with qualified attorneys
- Guarantee compliance
- Account for all jurisdictional requirements
- Cover industry-specific regulations (HIPAA, PCI-DSS, etc.)

**Always recommend:**
- Legal review before publication
- Regular policy updates
- Jurisdiction-specific legal counsel
- Industry-specific compliance review
