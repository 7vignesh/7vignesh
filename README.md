<h1 align="center">Hi, I'm Vignesh 👋</h1>

<h3 align="center">Full-Stack Engineer · Building AI-native dev tools</h3>

<p align="center">
  I design and ship products end-to-end — architecture, backend, frontend, and the AI workflows that build them faster.
  Currently exploring what it takes to make AI coding agents actually <em>reliable</em>, not just fast.
</p>

<p align="center">
  <a href="https://vignxsh.dev"><img src="https://img.shields.io/badge/Portfolio-vignxsh.dev-8A2BE2?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/vignesh-gopikrishnan-3851a1217/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://x.com/Vignesh7123"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="mailto:vigneshgopikrishnan.7@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<br/>

## 🚀 What I'm Building

<table>
<tr>
<td width="50%" valign="top">

### 🔎 [Skannr](https://skannr-ten.vercel.app)
**Universal AI code analysis tool** — repo-agnostic static + AI-powered review, published to npm. Ships a "Blast Radius" feature that walks git-diff → dependency graph → risk score, with a React/D3 visualizer, plus a pre-commit review mode called Guard.

`TypeScript` `AI Analysis` `D3.js` `npm`

**[→ github.com/7vignesh/skannr](https://github.com/7vignesh/skannr)**

</td>
<td width="50%" valign="top">

### ⚙️ [StackForge](https://stackforge-web.vercel.app)
**A loop engine for AI coding agents.** Instead of generating code, it enforces structured progress — gating "done" on evidence (passing type-checks, tests), persisting memory across sessions, and stopping runaway agents. No LLM inside, no API keys — your agent supplies the intelligence, StackForge supplies the discipline.

`TypeScript` `SQLite` `MCP` `Agent Tooling`

**[→ github.com/7vignesh/stackforge](https://github.com/7vignesh/stackforge)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [Fossel](https://github.com/7vignesh/fossel)
**Local-first MCP memory for every repo you work on.** Store conventions, bug fixes, reviewer patterns, and decisions in SQLite on your machine with FTS5 search. Works with Cursor, Claude Desktop, and any stdio MCP client. No accounts, no cloud.

`TypeScript` `SQLite` `MCP` `FTS5`

**[→ github.com/7vignesh/fossel](https://github.com/7vignesh/fossel)**

</td>
<td width="50%" valign="top">

### ✅ [SpecTruth](https://github.com/7vignesh/spectruth)
**Done-integrity auditor for AI coding agents.** When an agent marks a spec task complete, SpecTruth audits the claim against acceptance criteria using deterministic static evidence - no scores, no confidence values, just READY / BLOCKED / REVIEW_REQUIRED.

`TypeScript` `Kiro` `Spec-Driven` `Static Analysis`

**[→ github.com/7vignesh/spectruth](https://github.com/7vignesh/spectruth)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 [PgPulse](https://github.com/litepacks/pgpulse)
**Terminal-based live monitoring tool for PostgreSQL** (like `top`/`htop` for Postgres). Reads `pg_stat_activity`, `pg_stat_statements`, locks, and table/index summaries with low overhead. Features a 5-slot ring buffer for 10-second activity windows and delta mode for statement stats.

`JavaScript` `PostgreSQL` `TUI` `neo-blessed`

**[→ github.com/litepacks/pgpulse](https://github.com/litepacks/pgpulse)**

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

### 🌱 Open Source

Active contributor to **[Tracer-Cloud/OpenSRE](https://github.com/Tracer-Cloud/opensre)** — 12 merged PRs on agentic observability/SRE tooling.

<details>
<summary>Merged PRs to OpenSRE</summary>

| # | Title |
|---|---|
| [#3821](https://github.com/Tracer-Cloud/opensre/pull/3821) | fix(delivery): align error shapes across messaging delivery modules |
| [#2222](https://github.com/Tracer-Cloud/opensre/pull/2222) | feat(scheduler): add cron-driven scheduled deliveries to messaging providers |
| [#1714](https://github.com/Tracer-Cloud/opensre/pull/1714) | feat(messaging): add identity model, DM pairing, and tool approval metadata |
| [#1570](https://github.com/Tracer-Cloud/opensre/pull/1570) | fix(synthetic-tests): skip E2E tests gracefully when LLM credentials are missing |
| [#1404](https://github.com/Tracer-Cloud/opensre/pull/1404) | feat(interactive-shell): run_cli_command supports full opensre subcommand surface |
| [#1037](https://github.com/Tracer-Cloud/opensre/pull/1037) | refactor(tools): centralize code-host unavailable payload for code-host tools |
| [#1017](https://github.com/Tracer-Cloud/opensre/pull/1017) | test(tools): add unit tests for Bitbucket tools |
| [#1015](https://github.com/Tracer-Cloud/opensre/pull/1015) | test(cli): add direct unit tests for CLI layout renderers |
| [#1007](https://github.com/Tracer-Cloud/opensre/pull/1007) | test(tools): add unit tests for Azure Monitor Logs tool |
| [#977](https://github.com/Tracer-Cloud/opensre/pull/977) | feat(alerts): normalize incoming payloads to OpenSRE canonical format |
| [#958](https://github.com/Tracer-Cloud/opensre/pull/958) | refactor(wizard): split integration health validators into grouped modules |
| [#957](https://github.com/Tracer-Cloud/opensre/pull/957) | refactor(wizard): migrate Slack webhook validation from requests to httpx |

</details>

Active contributor to **[Agent-Field/agentfield](https://github.com/Agent-Field/agentfield)** — 20 merged PRs across the control plane, Go/Python/TypeScript SDKs, and security hardening.

<details>
<summary>Merged PRs to AgentField</summary>

| # | Title |
|---|---|
| [#952](https://github.com/Agent-Field/agentfield/pull/952) | feat(control-plane): add per-key rate limiting on hot endpoints |
| [#945](https://github.com/Agent-Field/agentfield/pull/945) | fix(execute): propagate agent 4xx in async lane instead of blanket 502 |
| [#943](https://github.com/Agent-Field/agentfield/pull/943) | fix(execute): resolve webhook not triggering on async status callback |
| [#917](https://github.com/Agent-Field/agentfield/pull/917) | feat(examples): triggers-demo-go end-to-end demo + Go skill docs |
| [#915](https://github.com/Agent-Field/agentfield/pull/915) | feat(sdk/go): trigger test helpers + fixture library |
| [#914](https://github.com/Agent-Field/agentfield/pull/914) | feat(sdk/go): dispatch envelope unwrap + Context injection |
| [#906](https://github.com/Agent-Field/agentfield/pull/906) | feat(sdk/go): triggers package + OnEvent/OnSchedule sugar |
| [#904](https://github.com/Agent-Field/agentfield/pull/904) | fix(sdk/python): add lock timeouts + offload blocking requests fallback |
| [#899](https://github.com/Agent-Field/agentfield/pull/899) | fix(sdk/python): replace bare asyncio.run() with loop-aware helpers |
| [#812](https://github.com/Agent-Field/agentfield/pull/812) | chore(sdk/python): enable ruff ASYNC lint rules to gate async/blocking hazards |
| [#799](https://github.com/Agent-Field/agentfield/pull/799) | fix(sdk/python): resolve ResultCache cross-loop deadlock |
| [#796](https://github.com/Agent-Field/agentfield/pull/796) | feat(sdk/typescript): trigger system parity - dispatch, sugar, testing, demo |
| [#794](https://github.com/Agent-Field/agentfield/pull/794) | test(sdk/python): expand verification.py coverage to 100% |
| [#790](https://github.com/Agent-Field/agentfield/pull/790) | fix(security): SSRF protection for approval callback_url |
| [#743](https://github.com/Agent-Field/agentfield/pull/743) | feat(sdk/ts): add trigger types, factories, and registration plumbing |
| [#724](https://github.com/Agent-Field/agentfield/pull/724) | fix(sdk/go): rewrite max_tokens to max_completion_tokens for newer OpenAI models |
| [#717](https://github.com/Agent-Field/agentfield/pull/717) | fix(control-plane): add timestamp freshness checks to prevent webhook replay attacks |
| [#716](https://github.com/Agent-Field/agentfield/pull/716) | fix(control-plane): flush SSE headers immediately in memory events handler |
| [#715](https://github.com/Agent-Field/agentfield/pull/715) | fix(control-plane): implement graceful shutdown on SIGTERM/SIGINT |
| [#701](https://github.com/Agent-Field/agentfield/pull/701) | fix(control-plane): prevent structured logs from leaking execution payloads |

</details>

Active contributor to **[supabase/supabase-js](https://github.com/supabase/supabase-js)** — open PRs on auth and PostgREST type improvements.

<details>
<summary>Open PRs to supabase-js</summary>

| # | Title | Status |
|---|---|---|
| [#2573](https://github.com/supabase/supabase-js/pull/2573) | feat(auth): add maxAutoRefreshFailures option | 🟡 Open |
| [#2445](https://github.com/supabase/supabase-js/pull/2445) | fix(postgrest): add typed column inference for order() with referencedTable | 🟡 Open |

</details>

<br/>

## 🛠️ Tech Stack

**Languages & Runtime**
<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" />
</p>

**Frontend**
<p>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

**Backend & Data**
<p>
<img src="https://img.shields.io/badge/Express.js-404D59?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi" />
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Prisma-3982CE?style=flat-square&logo=prisma&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.io-black?style=flat-square&logo=socket.io&badgeColor=010101" />
</p>

**Cloud & Infra**
<p>
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-039BE5?style=flat-square&logo=firebase" />
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/DigitalOcean-0167FF?style=flat-square&logo=digitalocean&logoColor=white" />
<img src="https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white" />
</p>

**Tools**
<p>
<img src="https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-121011?style=flat-square&logo=github&logoColor=white" />
</p>

<br/>

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=7vignesh&theme=dark&hide_border=true&include_all_commits=false&count_private=false" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=7vignesh&theme=dark&hide_border=true&include_all_commits=false&count_private=false&layout=compact" />
</p>
<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=7vignesh&theme=dark&hide_border=true" />
</p>

<br/>

<p align="center"><i>Open to full-stack / AI-tooling roles — always happy to talk about agentic engineering.</i></p>
