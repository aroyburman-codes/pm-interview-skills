# PM Interview Skills for AGI Companies

**10 Claude Code skills for crushing PM interviews at OpenAI, Anthropic, and DeepMind.**

No one else has skills specifically targeting PM interviews at AGI companies. These skills use battle-tested structured frameworks to generate strong-hire caliber answers with real-time research and citations.

## Skills

### Core Interview Skills

| Skill | Command | Use For |
|-------|---------|---------|
| **Product Sense** | `/product-sense` | "Design X", "Improve X", productize a capability |
| **Product Strategy** | `/product-strategy` | Market entry, competitive positioning, build-vs-buy, long-term vision |
| **Analytical PM** | `/analytical-pm` | Metrics, goal-setting, root-cause analysis, trade-offs, A/B tests |
| **Technical PM** | `/technical-pm` | RLHF, evals, RAG, LLM deployment, system design, API design |
| **Behavioral PM** | `/behavioral-pm` | "Tell me about a time...", conflict, leadership, failure stories |

### Prep & Context Skills

| Skill | Command | Use For |
|-------|---------|---------|
| **Mock Interviewer** | `/mock-interviewer` | Interactive mock interviews with scoring and feedback |
| **AI Product Teardown** | `/ai-product-teardown` | Structured teardown of ChatGPT, Claude, Gemini, etc. |
| **AI Market Landscape** | `/ai-market-landscape` | Real-time competitive analysis of the AI/AGI market |
| **PM Case Study** | `/pm-case-study` | Case studies from real AI product launches and decisions |
| **AI Ethics & Trade-offs** | `/ai-ethics-tradeoffs` | Safety/capability trade-offs, content policy, responsible scaling |

## Installation

### Claude Code Plugin (Recommended)

```bash
/plugin marketplace add aroyburman-codes/pm-interview-skills
```

### Manual Installation

```bash
git clone https://github.com/aroyburman-codes/pm-interview-skills.git ~/.claude/skills/pm-interview-skills
```

### OpenSkills (Cross-tool)

```bash
npx openskills install aroyburman-codes/pm-interview-skills
```

## How It Works

Each skill follows a research-first workflow:

1. **You ask a question** — e.g., `/product-sense How would you improve Claude for enterprise?`
2. **The skill researches** — 5-10 web searches for latest data, competitor intel, thought leader perspectives
3. **Generates a structured answer** — Following the specific framework for that round type, with inline citations
4. **Strong-hire caliber** — Structured to hit the specific signals interviewers look for at AGI companies

## Frameworks

### Product Sense
`Clarify → Why Build → Users → Pain Points → Solutions → Metrics`

### Product Strategy
`Alignment → Landscape → Options → Recommendation → Risks`

### Analytical PM
- **Metrics**: NSM → Supporting → Counter → Ecosystem → Trade-offs
- **Root-cause**: Clarify → Segment → Hypothesize (MECI) → Validate → Act
- **Trade-offs**: Quantify → Framework → Experiment → Recommend

### Technical PM
`Constraints → Personas → System Design → Trade-offs → API/DX → Metrics`

### Behavioral PM
`Situation (10%) → Task (10%) → Action (60%) → Result (15%) → Reflection (5%)`

### AI Ethics
`Scope → Analyze Perspectives → Framework → Evaluate Options → Recommend & Monitor`

## Who This Is For

- PMs interviewing at **OpenAI**, **Anthropic**, **DeepMind**, or any AI-first company
- PMs transitioning into AI/ML product roles
- Anyone who wants structured frameworks for thinking about AI products
- Works with Claude Code, Cursor, Windsurf, Codex, and other tools supporting the [Agent Skills](https://agentskills.io) standard

## What Makes This Different

| | This repo | General PM skills | Generic interview coaching |
|---|---|---|---|
| **AGI-company specific** | OpenAI, Anthropic, DeepMind focus | Generic PM work | Generic STAR method |
| **Research-first** | Live web search for every answer | Static frameworks | No research |
| **Technical depth** | RLHF, evals, RAG, agents, alignment | No ML coverage | No technical |
| **Safety-aware** | Ethics, responsible scaling, content policy | Not covered | Not covered |
| **Interactive mock** | Plays the interviewer, scores you | No simulation | Basic Q&A |
| **Cited sources** | Inline links in every answer | No citations | No citations |

## Company-Specific Flavor

Each skill adapts its tone and emphasis based on the target company:

- **OpenAI**: Ambitious, creative, 10x thinking, bias toward action
- **Anthropic**: Careful, principled, safety-first, intellectual humility
- **DeepMind**: Scientific rigor, research-driven, long-term thinking

## Contributing

PRs welcome! To add a new skill:

1. Create a directory in `skills/` with your skill name
2. Add a `SKILL.md` following the frontmatter format (see existing skills)
3. Keep `SKILL.md` under 500 lines — use reference files for detailed content
4. Submit a PR with a description of the skill and example usage

## License

MIT License — see [LICENSE](LICENSE)

---

Built while prepping for PM interviews at AGI companies.
