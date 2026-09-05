<h1 align="center">Tisha Chawla</h1>

<p align="center">
  <b>Software Engineer @ Microsoft</b> &nbsp;·&nbsp; building the control plane for AI agents<br>
  <sub>https://tishachawla-jg.github.io<sub>
  <sub>Co-creator of <a href="https://github.com/theagentplane/tokenops">TokenOps</a> and <a href="https://github.com/theagentplane/chronicle">Chronicle</a> at <a href="https://theagentplane.github.io/">The Agent Plane</a></sub>
</p>

<p align="center">
  <a href="https://theagentplane.github.io/"><img alt="The Agent Plane" src="https://img.shields.io/badge/The_Agent_Plane-0b7285?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/tisha-chawla/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://dev.to/tisha"><img alt="dev.to" src="https://img.shields.io/badge/dev.to-2f3437?style=flat-square&logo=devdotto&logoColor=white"></a>
  <a href="https://www.youtube.com/@Tisha_Talks_Tech"><img alt="YouTube" src="https://img.shields.io/badge/Tisha_Talks_Tech-c4302b?style=flat-square&logo=youtube&logoColor=white"></a>
</p>

<hr>

### The problem I work on

Multi-agent systems fail in two ways that ordinary tooling cannot see. They **overspend**, because a runaway loop burns a month of budget before a per-request rate limit notices anything is wrong. And they are **unreproducible**, because a trace tells you what happened without letting you run it again.

We built the two pieces of infrastructure that fix that, as open source.

<table>
<tr>
<td width="50%" valign="top">

#### 🪙 [TokenOps](https://github.com/theagentplane/tokenops)

**Run-aware token governance.** Cap spend across a whole agent workflow instead of per request, with a shared ledger plus in-path enforcement that can throttle, downgrade, or halt a run before it burns the budget.

[![stars](https://img.shields.io/github/stars/theagentplane/tokenops?style=flat-square&color=0b7285&label=stars)](https://github.com/theagentplane/tokenops/stargazers)
[![PyPI](https://img.shields.io/pypi/v/agent-tokenops?style=flat-square&color=3775a9&label=agent-tokenops)](https://pypi.org/project/agent-tokenops/)

```bash
pip install agent-tokenops
```

</td>
<td width="50%" valign="top">

#### 🎬 [Chronicle](https://github.com/theagentplane/chronicle)

**Record and replay for agent decision graphs.** Turn a production failure into a committed regression test, then re-run your fix deterministically, with no live LLM calls and no flaky reproduction.

[![stars](https://img.shields.io/github/stars/theagentplane/chronicle?style=flat-square&color=0b7285&label=stars)](https://github.com/theagentplane/chronicle/stargazers)
[![PyPI](https://img.shields.io/pypi/v/agent-chronicle?style=flat-square&color=3775a9&label=agent-chronicle)](https://pypi.org/project/agent-chronicle/)

```bash
pip install agent-chronicle
```

</td>
</tr>
</table>

> **Featured by Microsoft Developer:** *"Who spent all the tokens?"* &nbsp;
> [LinkedIn](https://www.linkedin.com/posts/microsoft-developers_who-spent-all-the-tokens-tokenops-gives-activity-7499191980715982848-224b) · [X](https://x.com/msdev/status/2093425027500978292)

Both feed a shared [**control plane**](https://github.com/theagentplane/control-plane), one SQLite and one UI, where agents never touch the database file. Releases are exercised against [**testbench**](https://github.com/theagentplane/testbench), a set of tool-neutral multi-agent workloads I keep separate so the testing stays honest.

<hr>

### 🎤 Talks

| | |
|---|---|
| **[FinOps for AI Agents: Who Spent All the Tokens?](https://www.youtube.com/watch?v=GJX19pNhmSw)** | AI Engineer World's Fair, San Francisco · with Susheem Koul |
| **[Your Agent Failed in Prod. Good Luck Reproducing It.](https://www.youtube.com/watch?v=Lc8zRh9muoY)** | On replayability for autonomous agents · with Susheem Koul |
| **[Shorts →](https://www.youtube.com/@Tisha_Talks_Tech/shorts)** | Short-form agent infrastructure explainers |

### ✍️ Writing

- **[TokenOps: Real-Time, Run-Scoped Cost Control for AI Agents](https://commandline.microsoft.com/tokenops-real-time-run-scoped-cost-control-ai-agents/)** in *Microsoft Command Line*
- **[40% of AI Agent Projects Will Be Canceled by 2027. Token Governance Is How You Avoid It.](https://dev.to/tisha/40-of-ai-agent-projects-will-be-canceled-by-2027-token-governance-is-how-you-avoid-it-38id)**
- **[Debugging Multi-Agent Systems: Your Trace Tree Is Lying](https://dev.to/tisha/debugging-multi-agent-systems-your-trace-tree-is-lying-1oi9)**
- **[You Recorded the Incident. Now Prove Your Fix Actually Works.](https://dev.to/tisha/you-recorded-the-incident-now-prove-your-fix-actually-works-2cni)**
- **[Spec-Driven Development: When Structure Helps and When It Becomes Tax](https://dev.to/tisha/spec-driven-development-when-structure-helps-and-when-it-becomes-tax-1f66)**

  *More at [dev.to/tisha →](https://dev.to/tisha)*

<hr>

<p align="center">
  <sub>Working on agent infrastructure, FinOps for LLMs, or reproducible agent testing? I'd like to hear about it. <a href="https://www.linkedin.com/in/tisha-chawla/">Say hi on LinkedIn</a>.</sub>
</p>
