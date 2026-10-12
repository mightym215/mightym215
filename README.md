# Hi, I'm Michael 👋

CS senior at Penn State and Customer Success Engineer co-op at IBM. I build AI agents that call real tools and take real actions, and I care most about what makes them trustworthy: grounded answers, real evals, and a human in the loop.

🌐 **Portfolio:** [mightym215.github.io](https://mightym215.github.io)

## 🎬 Marquee: AI movie concierge
[Live demo](https://marquee-rdgp.onrender.com) · [Code](https://github.com/mightym215/marquee)

Tell it your mood, like *"something like Parasite but funnier, under 2 hours,"* and an agent finds real movies through an MCP server I wrote for TMDB and Letterboxd. I built it because I love movies.

- **8 tool MCP server** in TypeScript that works in the app and in any MCP client
- **Grounded picks:** if the agent recommends a movie it never actually retrieved, the code drops it
- **21 case eval harness** that checks every pick against real TMDB data for runtime, year, genre, language, rating, and watch history
- **Live tool call streaming, Letterboxd sync,** and **Blend** for planning movie night with a friend

`TypeScript` `MCP` `Claude API` `React` `Express` `Vitest` `Render`

## 🤝 MatchPoint: multi agent mentorship matching
[Code](https://github.com/mightym215/matchpoint)

Matches mentors with mentees, drafts first meeting agendas, and follows up on pairs that have gone quiet.

- **Three specialist agents** (matcher, agenda, nudge) on native tool calling with no framework, each with Pydantic validated outputs
- **Hand labeled eval harness** scored against the real matcher code, reporting precision@k and accuracy
- **Full observability:** every run logs tokens, latency, and a full trace in a custom dashboard
- **Human approval** before anything with a real side effect, like sending an email or committing a match

`Python` `FastAPI` `PostgreSQL` `Anthropic SDK` `Next.js` `Docker` `GitHub Actions`

## 🛠️ Tech I work with
`Python` `TypeScript` `FastAPI` `Express` `React` `Next.js` `PostgreSQL` `Docker` `Kubernetes` `MCP`

## 📫 Reach me
[LinkedIn](https://www.linkedin.com/in/michaelkwasimensah/) · [Portfolio](https://mightym215.github.io) · michaelmensah274@gmail.com
