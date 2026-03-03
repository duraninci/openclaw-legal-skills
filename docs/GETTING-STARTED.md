# Getting Started with Legal Skills

This guide covers how to install and use these legal analysis skills with various AI assistants.

## Overview

Legal Skills are structured prompts that give AI assistants specialized knowledge for legal analysis. Each skill contains:
- Domain expertise and frameworks
- Analysis checklists
- Output formats
- Severity classifications
- Limitations and disclaimers

## Installation

### Option 1: Clone the Repository

```bash
git clone https://github.com/duraninci/legal-skills.git
```

### Option 2: Download Individual Skills

Download only the skills you need from the `skills/` directory.

## Usage by Platform

### Claude.ai (Web)

1. Open Claude and go to a Project
2. Click "Add to project knowledge"
3. Upload the `SKILL.md` file for the skill you want
4. Start a new conversation in that project
5. Claude will automatically reference the skill

**Example prompt:**
```
Review the attached NDA and identify any concerns. Flag issues by severity.
```

### Claude Code CLI

If using Claude Code or similar CLI tools:

```bash
# Reference the skill in your prompt
claude "Using the framework in ./legal-skills/skills/contract-review/SKILL.md, review this NDA: [paste contract]"
```

### OpenClaw

Skills in your `~/clawd/skills/` directory are automatically available:

```bash
# Copy skills to your OpenClaw workspace
cp -r legal-skills/skills/* ~/clawd/skills/
```

Then reference naturally:
```
Review this operating agreement as a minority member
```

OpenClaw will automatically load `llc-operating-agreement` based on the context.

### Cursor / VS Code

Add to your `.cursorrules` file:
```
When analyzing legal documents, reference frameworks from ./legal-skills/skills/

For contract review: use ./legal-skills/skills/contract-review/SKILL.md
For LLC agreements: use ./legal-skills/skills/llc-operating-agreement/SKILL.md
```

### API Usage

When using the Claude API:

```python
import anthropic

# Load the skill
with open("legal-skills/skills/contract-review/SKILL.md") as f:
    skill_content = f.read()

client = anthropic.Anthropic()

message = client.messages.create(
    model="claude-sonnet-4-20250514",
    max_tokens=4096,
    system=skill_content,
    messages=[
        {"role": "user", "content": "Review this contract: [contract text]"}
    ]
)
```

## Best Practices

### 1. Provide Context

Tell the AI your position in the deal:
- "I'm the buyer reviewing this acquisition agreement"
- "I'm a minority investor reviewing this operating agreement"
- "I'm the employer drafting this offer letter"

### 2. Specify Jurisdiction

Legal rules vary by location:
- "This is a Delaware LLC"
- "The employee is in California"
- "GDPR applies to this privacy policy"

### 3. Request Specific Output

Ask for the format you need:
- "Provide a severity-rated list of issues"
- "Create a redline with suggested changes"
- "Give me a negotiation position summary"

### 4. Iterate

Start broad, then drill down:
1. "Review this agreement and identify top concerns"
2. "Explain the liability provisions in detail"
3. "Draft alternative language for Section 5.2"

## Example Workflow

### Contract Review Workflow

1. **Initial Review**
   ```
   Review this vendor agreement. I'm the customer. 
   Identify issues by severity (Red/Yellow/Green).
   ```

2. **Deep Dive**
   ```
   Explain the indemnification provisions. 
   What risks do they create for us?
   ```

3. **Negotiation Prep**
   ```
   Draft balanced alternative language for the 
   problematic indemnification clause.
   ```

4. **Summary**
   ```
   Create a one-page executive summary of key 
   terms and recommended changes.
   ```

## Combining Skills

You can combine multiple skills for complex tasks:

```
Using the llc-operating-agreement and partnership-llc-tax skills, 
review this operating agreement for both legal and tax implications.
```

## Troubleshooting

### Skill Not Loading?

- Ensure the SKILL.md file is in the correct location
- Check file permissions
- Verify the skill is referenced in your prompt or project

### Output Too Generic?

- Provide more context about your position
- Specify the jurisdiction
- Ask for specific frameworks to be applied

### Missing Analysis?

- Request specific sections to be analyzed
- Ask for the severity classification
- Request the skill's checklist to be applied

## Getting Help

- Open an issue on GitHub for bugs or suggestions
- Check the [examples](../examples/) directory for sample outputs
- Review the [Use Cases](./USE-CASES.md) for common scenarios
