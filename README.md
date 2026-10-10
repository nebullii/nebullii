<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=28&duration=3500&pause=1200&color=58A6FF&center=true&vCenter=true&width=600&lines=Building+Mitig8it" alt="Building Mitig8it" />

<sub><i>A GitHub-native security platform that reviews pull requests, verifies a fix in a sandbox, and posts it as a suggestion for a human to apply.</i></sub>

</div>

<br />

<table>
<tr>
<td width="50%" valign="top">

#### 👩‍💻 About

I’m a software engineer with **6 years** of experience building production backend systems and APIs, integrating third-party services, and making databases fast. More recently my work has been applied AI: one LLM support agent shipped to a real customer base and evaluated in production, and Mitig8it since then, where every rule earns its place on measured precision.

</td>
<td width="50%" valign="top">

#### 🚀 Right now

Right now I’m building evaluation harnesses for tool-calling agents: separating filter misses from model misses, and measuring where tool-selection accuracy falls off as the catalogue grows.

</td>
</tr>
</table>

#### 🔢 Three numbers

| | |
|---|---|
| **60%** | less manual customer support after an autonomous LLM agent with five tools, strict JSON routing and rule-based escalation went live. |
| **5 metric families** | used to evaluate that agent in production: outcome, trajectory, quality, operational and safety, from resolution and reopen rates to grounding rate, tool failure rate and token cost. |
| **0.67 to 0.97** | precision of posted findings after Mitig8it's per-rule gate, over 172 findings adjudicated by hand across 23 vulnerable repositories. 51 of 63 repairs proved by a generated test. |

#### 🔭 Areas of Interest

`🤖 Agent systems & evaluation` &nbsp; `🧰 Developer tools & security` &nbsp; `⚙️ Production systems`

#### 📊 How I work

<table>
<tr>
<td width="33%" valign="top">

**01**

Tiered before expensive: deterministic rules run first, static analysis next, and an LLM only where the cheaper tiers are ambiguous.

</td>
<td width="33%" valign="top">

**02**

Rules and models kept on evidence, not preference: every tier 2 rule posts only while its measured precision stays above 0.8, over **172 findings adjudicated by hand**.

</td>
<td width="33%" valign="top">

**03**

Model-written changes run in a locked-down sandbox, hash-checked before and after the write.

</td>
</tr>
</table>

#### 🛠️ Tech Stack

<table>
<tr>
<td width="50%" valign="top">

**Gen AI**

Agent harnesses: tool calling, intent routing, strict JSON outputs, rule-based escalation.<br />
Evaluation gates: hand-labelled corpora, per-rule precision thresholds, LLM-as-judge.<br />
Production agent metrics: outcome, trajectory, quality, operational, safety.<br />
Budgeted LLM workers: queue-leased runs, concurrency caps, rate limits, per-run token and USD ceilings, fail-open triage.<br />
LangChain, LangGraph, LangSmith. A2A protocol. OpenAI, Anthropic, Gemini, Ollama.

</td>
<td width="25%" valign="top">

**Data and Retrieval**

PostgreSQL, pgvector, Redis, embeddings, Semgrep AST analysis.

</td>
<td width="25%" valign="top">

**Software and Infra**

Python, FastAPI, gRPC, Ruby on Rails, Docker, GCP Cloud Run, AWS, GitHub Actions. Go and Rust contributions.

</td>
</tr>
</table>

<div align="center">

<br />

**Open to AI Engineer roles where agents, their evaluation, and their token cost are the job. Python and Ruby on Rails underneath. New York, remote or relocation.**

</div>
