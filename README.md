# Product Architect

**The most comprehensive open-source product development skill for Claude.**

31 agents · 22 frameworks · 14,000+ lines · Solo founder Day 0 → IPO

> **Note:** This repository is a [Claude Skill](https://docs.anthropic.com/en/docs/agents-and-tools/skills). Claude reads `SKILL.md`. This README is for human visitors on GitHub.

---

## Install

### Claude.ai
1. Download this repo as ZIP (Code → Download ZIP)
2. Go to Claude.ai → Settings → Capabilities → Skills
3. Upload the ZIP
4. Test: Ask Claude "Help me build a product" or "Write a PRD"

### Claude Code
```bash
git clone https://github.com/ankitjha67/product-architect.git
# Place in your Claude Code skills directory
```

### API
Use the `/v1/skills` endpoint with the `container.skills` parameter.

---

## What's Inside

**31 Agents** — specialized department heads covering: Discovery, Strategy, PRD, Design, Engineering, Testing, DevOps, Security, Legal, Compliance, Trust & Safety, Fraud, Launch, Marketing, Analytics, Customer Success, Finance, Operations, BAU, Innovation, People & HR, L&D, Wellness, PR, Governance & IPO, ESG, Government Relations, Data & AI, Platform, plus Chief Reviewer and Proactive Advisor.

**22 Frameworks** — including a Founder's Playbook (week-by-week with costs), 30-Day Launch Engine, 20 Scenario Playbooks, 20+ SOPs with process maps, salary bands, consulting frameworks (McKinsey/BCG/Bain), 200+ stress-test edge cases, universal checklists, and compliance guides for India, US, EU, UK, and Southeast Asia.

**Smart Loading** — Routes each request to only the relevant agents. Never loads everything at once. Free tier compatible.

**KDR Memory** — Key Decision Records survive chat compaction. Paste into new conversations to resume seamlessly.

**Cross-Agent Governance** — 4-level authority hierarchy prevents conflicting outputs. Compliance overrides Security overrides Finance overrides Chief Reviewer.

---

## Repository Structure

```
product-architect/
├── SKILL.md                     ← Claude reads this (main skill file)
├── SMART-LOADER.md              ← Context router + memory engine
├── agents/                      ← 31 specialized agents (00-30)
├── frameworks/                  ← 22 strategic & operational frameworks
├── references/
│   ├── compliance/              ← Country deep-dives (IN, US, EU, UK, SEA)
│   ├── industry-references.md
│   ├── DISCLAIMER.md            ← Professional review requirements
│   └── github-readme.md         ← Extended documentation
└── tools/
    └── navigator.jsx            ← Interactive web UI for founders
```

## Disclaimer

This is an educational framework, not professional advice. All legal, financial, security, and HR content requires qualified professional review before real-world use. See `references/DISCLAIMER.md`.

## License

MIT — see LICENSE file.

## Contributing

Issues, PRs, and new agent/framework contributions welcome.
