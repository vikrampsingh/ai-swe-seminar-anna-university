# The End of Software Engineering?

**How AI Agents Are Changing the Way Software Is Designed, Engineered and Delivered**

An *Industry Connect* seminar for MSc CS & Mathematics students at the **Department of Mathematics, College of Engineering, Guindy (CEG), Anna University** — 29 September 2026.

---

## About the Seminar

For decades, software engineering has followed a familiar path: `Requirements >> Design >> Code >> Test >> Deploy`. But now AI agents can increasingly write code, use tools, run tests, debug failures, navigate codebases, and work autonomously for hours. So if AI can write the code, what exactly should a software engineer learn and do?

This session explores how the engineering abstraction is moving **from writing software to engineering the systems that produce software** — with interactive discussions, a career perspective, and live AI & coding-agent demonstrations.

### Speaker

**Vikram Singh** — Founder & Product Architect, [Zestifai Technologies](https://www.linkedin.com/in/vikrampsingh/)
Technology entrepreneur and product architect with over two decades of experience in enterprise software engineering, product development, digital transformation, and AI.

---

## Topics Covered

1. **From Coding to Agentic Engineering** — How we moved from LLMs >> Copilots >> Coding Agents >> Agentic Systems, and why this is more than just another developer tool.
2. **The New Software Engineering Stack** — The emerging architecture: `Model >> Agent >> Loop >> Graph >> Harness >> Reliable Software`. What agents actually do, and what makes them capable of working autonomously.
3. **The Engineer's New Job** — When code becomes cheap to produce, engineering value moves to specification, architecture, context, orchestration, verification, and judgment. Why specification engineering may matter more than prompt engineering.
4. **Can We Trust AI-Generated Software?** — AI-generated software is probabilistic and can fail in unexpected ways. How do we build systems that can test, evaluate, observe, verify, and recover from AI failures?
5. **The Software Engineer of Tomorrow** — The state of today's job market, and which skills to build now. Why CS/Maths/SWE fundamentals (algorithms, probability, statistics, optimization, databases, distributed systems, security, design) still matter — perhaps more than ever. They become the vocabulary for engineering AI systems.

---

## Key Takeaways

- **The paradigm shift (2023–26):** AI moved from *answering* >> *generating* >> *executing*. AI-assisted SDLC is now mainstream, with the "Agentic DevOps Loop": `Issue >> Agent >> Branch >> Code >> Tests >> PR >> Human Review >> Merge >> Deploy`.
- **The unit of work got bigger:** `Token >> Line >> Function >> File >> Feature >> Task >> Workflow` — and the human role shifts from *Do >> Assist >> Delegate >> Supervise*.
- **AI Agents:** `AI Agent = Goal + Reasoning + Tools + State + Feedback + Autonomy`. A model ≠ an agent — the agent loop (Perceive, Reason, Plan, Act, Observe, Adapt) plus a harness (state, policy, context, tools) is what makes a system capable.
- **The bottleneck moves:** Agents raise the throughput of *plausible* code, but the "verification tax" means time saved writing is often re-spent auditing. Scarce work shifts upstream (intent, specification, architecture) and downstream (tests, evals, observability, judgment).
- **History rhymes:** Computers didn't eliminate work; they changed what work existed. From the Cold War space race to India's IT boom to Hinton's predictions about radiologists — we have often been wrong about the future. AI could be no different.
- **The bottom line:** It's not the end of engineering — it's the end of *coding as the scarce skill*. Move from writing software to **engineering systems that produce software**.

### 2026 Job Market Data (sources on the slides)

- 87%+ of technologists express some level of trust in AI outputs; ~70% use AI agents; 80% use AI at least an hour a day ([Stack Overflow Survey 2026](https://survey.stackoverflow.co/2026)).
- U.S. job postings requiring AI-literacy skills grew **70% YoY**; 1.3M new AI-enabled jobs globally over 2025–26; 75% of firms say people skills matter even more now ([LinkedIn Economic Graph, 2026](https://economicgraph.linkedin.com/research/labor-market-report-2026)).
- 90%+ of tech professionals use AI at work; wages rise faster in AI-exposed industries (16.7% vs 7.9%); 88% of executives plan to increase AI budgets ([DORA Report](https://dora.dev/research/2025/dora-report/), [PwC AI Jobs Barometer](https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-jobs-barometer.html)).

---

## Live Demo

The session included two live coding-agent demonstrations using [OpenCode](https://opencode.ai/):

- **Coding agent walkthrough** — watching an agent issue >> read repo >> edit >> run >> test >> observe >> patch.
- **Build "MediaSync" with AI** — an interactive command-line tool for managing media backup/cleanup on Android devices (uses `adb` + `rsync`, with commands like `backup`, `backup --dry-run`, `cleanup`). Participants cloned the repo, built a feature, and opened PRs for review and merge.
  - Demo repo: <https://github.com/vikrampsingh/vps-mediasync-cli>

---

## Repository Contents

| File/Directory | Description |
|---|---|
| `Slide deck for Industry Connect - CEG, Anna University - v1.5.pdf` | The main slide deck (30 slides) presented at the seminar |
| `Seminar overview for MSc CS_Maths - CEG, Anna University v2.0.pdf` | Two-page seminar overview distributed to students |
| `Invite for Industry Connect Seminar - CEG, Anna University.pdf` | The seminar invitation |
| `Further readings/` | Referenced papers in QA-ready PDF form: [The End of Software Engineering](https://arxiv.org/html/2606.05608v1), [SWE-bench](https://arxiv.org/abs/2310.06770), [SWE-agent](https://arxiv.org/abs/2405.15793), and SWE-Milestone: Evaluating AI Agents on Continuous Software Evolution |
| `pics/` | Images from the seminar |

---

## References / Further Reading

- **Book:** [Beyond Vibe Coding](https://beyond.addy.ie/) — Addy Osmani
- **Book:** [Agentic Engineering](https://learning.oreilly.com/library/view/agentic-engineering/0642572392291/) — Addy Osmani
- **Paper:** [The End of Software Engineering](https://arxiv.org/html/2606.05608v1) — Zhenfeng Cao et al.
- **Paper:** [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793) — John Yang et al.
- **Paper:** [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) — Carlos E. Jimenez et al.
- **Reports:** [DORA Report 2025](https://dora.dev/research/2025/dora-report/) · [DORA: Balancing AI Tensions](https://dora.dev/insights/balancing-ai-tensions) · [Stack Overflow Survey 2026](https://survey.stackoverflow.co/2026) · [LinkedIn Labor Market Report 2026](https://economicgraph.linkedin.com/research/labor-market-report-2026) · [PwC AI Jobs Barometer](https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-jobs-barometer.html)
- **Coding agents:** [OpenCode](https://opencode.ai/) · [OpenAI Codex](https://openai.com/codex/) · [Claude Code](https://claude.com/product/claude-code)

---

## Speaker Contact

**Vikram Singh** — <https://www.linkedin.com/in/vikrampsingh/>
