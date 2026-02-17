# PM Skills for AI Product Managers

**Structured frameworks for AI product managers — covering daily workflows, product thinking, and technical depth.**

Covers the full PM toolkit: writing PRDs, defining metrics, running prioritization, doing competitive analysis, building product strategy, and more — all tuned for the AI product landscape.

## Skills

### PM Workflow Skills

| Skill | Command | Use For |
|-------|---------|---------|
| **PRD Writer** | `/prd-writer` | Generate structured PRDs from a feature brief or idea |
| **Prioritization Matrix** | `/prioritization-matrix` | Score and rank features using RICE/ICE/weighted scoring |
| **User Research Synthesis** | `/user-research-synthesis` | Synthesize interviews and feedback into actionable insights |
| **Launch Checklist** | `/launch-checklist` | Generate launch readiness checklists for product releases |
| **Stakeholder Brief** | `/stakeholder-brief` | Write exec-ready updates, decision docs, and status reports |
| **Metric Dashboard** | `/metric-dashboard` | Design KPI dashboards and metric tracking plans |
| **PM Writing** | `/pm-writing` | Rewrite any PM doc with extreme clarity — BLUF, numbered lists, force-ranked priorities |

### Product Thinking Skills

| Skill | Command | Use For |
|-------|---------|---------|
| **Product Sense** | `/product-sense` | "Design X", "Improve X", productize a capability |
| **Product Strategy** | `/product-strategy` | Market entry, competitive positioning, build-vs-buy, long-term vision |
| **Analytical PM** | `/analytical-pm` | Metrics, goal-setting, root-cause analysis, trade-offs, A/B tests |
| **Technical PM** | `/technical-pm` | System design, API design, ML/AI technical depth |
| **Behavioral PM** | `/behavioral-pm` | Leadership stories, conflict resolution, stakeholder management |

### AI Industry Skills

| Skill | Command | Use For |
|-------|---------|---------|
| **AI Product Teardown** | `/ai-product-teardown` | Structured teardown of ChatGPT, Claude, Gemini, etc. |
| **AI Market Landscape** | `/ai-market-landscape` | Real-time competitive analysis of the AI market |
| **PM Case Study** | `/pm-case-study` | Case studies from real AI product launches and decisions |
| **AI Ethics & Trade-offs** | `/ai-ethics-tradeoffs` | Safety/capability trade-offs, content policy, responsible scaling |
| **Mock Interviewer** | `/mock-interviewer` | Interactive mock practice with scoring and feedback |

## Installation

### Claude Code Plugin (Recommended)

```bash
/plugin marketplace add aroyburman-codes/pm-skills
```

### Manual Installation

```bash
git clone https://github.com/aroyburman-codes/pm-skills.git ~/.claude/skills/pm-skills
```

### OpenSkills (Cross-tool)

```bash
npx openskills install aroyburman-codes/pm-skills
```

## How It Works

Each skill follows a research-first workflow:

1. **You describe what you need** — e.g., `/prd-writer AI-powered search feature for our docs platform`
2. **The skill researches** — web searches for latest data, competitor approaches, best practices
3. **Generates structured output** — Following proven frameworks with inline citations
4. **Ready to use** — Copy into your docs, share with stakeholders, or iterate further

## Frameworks

### Product Sense
`Clarify → Why Build → Users → Pain Points → Solutions → Metrics`

### Product Strategy
`Alignment → Landscape → Options → Recommendation → Risks`

### Analytical PM
- **Metrics**: NSM → Supporting → Counter → Ecosystem → Trade-offs
- **Root-cause**: Clarify → Segment → Hypothesize (MECE) → Validate → Act
- **Trade-offs**: Quantify → Framework → Experiment → Recommend

### Technical PM
`Constraints → Personas → System Design → Trade-offs → API/DX → Metrics`

### Prioritization
`Impact → Confidence → Effort → Score → Rank → Communicate`

## Compatibility

Works with Claude Code, Cursor, Windsurf, Codex, and other tools supporting the [Agent Skills](https://agentskills.io) standard.

## Contributing

PRs welcome! To add a new skill:

1. Create a directory in `skills/` with your skill name
2. Add a `SKILL.md` following the frontmatter format (see existing skills)
3. Keep `SKILL.md` under 500 lines — use reference files for detailed content
4. Submit a PR with a description of the skill and example usage

## License

MIT License — see [LICENSE](LICENSE)
