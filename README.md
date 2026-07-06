### Hi, I'm Michael 👋

Penn State Engineering Scholar (Clark Scholars / CSP, Cohort 4). Interested in AI engineering — I like building systems where LLMs call tools and take real actions, not just answer questions.

---

### 🚀 Featured project

#### [MatchPoint](https://github.com/mightym215/matchpoint) — Agentic Mentorship-Matching Platform

A multi-agent system that matches mentors with mentees, drafts grounded first-meeting agendas, and follows up on pairs that have gone quiet — built to demonstrate real agentic architecture, not a single prompt in a loop.

- **Multi-agent orchestration** on the Anthropic SDK's native tool-calling, no framework — a central dispatcher routes to three specialist agents (matcher, agenda, nudge), each with its own tools and Pydantic-validated structured outputs
- **A real evaluation harness** — hand-labeled ground truth scored against the production matcher's actual code path, reporting precision@k, accuracy, and score distribution as reproducible metrics, not assumptions
- **Full observability** — every agent run logs tokens, latency, and a full input/output trace, surfaced in a custom dashboard with hand-built, accessibility-validated data visualizations
- **Safety by default** — every agent action with an external side effect (sending email, committing a match) requires explicit human approval

`Python` `FastAPI` `PostgreSQL` `Anthropic SDK` `Next.js/React` `Docker` `GitHub Actions`

---

### 🛠️ Tech I work with

<!-- Trim/expand this to match what's actually true for you. -->

`Python` `TypeScript` `FastAPI` `Next.js` `PostgreSQL` `Docker`

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/michaelkwasimensah/)
