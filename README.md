<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=24&duration=3500&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=AI+Engineer.+LLM+agents+and+their+evaluation." alt="AI Engineer. LLM agents and their evaluation." />

<sub><i>AI engineer. Production LLM agents, agent evaluation, token and cost control. Python and Ruby on Rails, 6 yrs.</i></sub>

</div>

<br />

<table>
<tr>
<td width="50%" valign="top">

#### 👩‍💻 About

I’m a software engineer with **6 years** of production software in Python and Ruby on Rails. In applied AI: one LLM support agent shipped to a real customer base and evaluated in production, then Mitig8it, where every rule earns its place on measured precision.

Based in New York City. Before that, 6 years at Thingbits Electronics in Mumbai building a full stack Rails/Spree commerce platform, its integrations (Zoho Books, Bluedart, Razorpay, PayPal) and a production LLM support agent that cut manual customer support by 60%. MS Computer Science, Clark University (Dec 2025). Second Place, Clark University Technology Product Innovation Challenge, Fall 2025 ($1,250) for Code Sentry.

</td>
<td width="50%" valign="top">

#### 🚀 Right now

Right now I’m designing an evaluation harness for tool-calling agents: separating filter misses from model misses, and measuring where tool-selection accuracy falls off as the catalogue grows. The gold set is labelled and versioned.

</td>
</tr>
</table>

#### 🔢 Three numbers

| | |
|---|---|
| **60%** | less manual customer support after an autonomous LLM agent with five tools, strict JSON routing and rule-based escalation went live. |
| **5 metric families** | used to evaluate that agent in production: outcome, trajectory, quality, operational and safety, from resolution and reopen rates to grounding rate, tool failure rate and token cost. |
| **0.67 to 0.97** | precision of posted findings after Mitig8it's per-rule gate, over 172 adjudicated findings across 23 vulnerable repositories. 51 of 63 fixes verified, 46 of them by fail-then-pass tests. |

#### 🤝 Open source

ZeroClaw: 5 merged PRs. cmux: 5 merged PRs and 4 open. vLLM: 1 open PR.

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

Rules and models kept on evidence, not preference: every tier 2 rule posts only while its measured precision stays above 0.8, over **172 adjudicated findings**.

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
Evaluation gates: labelled corpora, per-rule precision thresholds, LLM-as-judge.<br />
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

**Open to AI Engineer roles where agents, their evaluation, and their token cost are the job. New York, remote or relocation.**

</div>
