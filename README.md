<div align="center">

<img src="assets/header.svg" width="100%" alt="Header" />

<a href="https://github.com/wujuncheng-dev">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3200&pause=900&color=0284C7&center=true&vCenter=true&width=600&lines=Welcome+to+my+corner+of+GitHub!;Make+machines+do+the+boring+work;Small+tools%2C+big+time+savings;Always+shipping%2C+always+learning" alt="Typing SVG" />
</a>

<br/>

<a href="https://github.com/wujuncheng-dev?tab=followers"><img src="https://img.shields.io/github/followers/wujuncheng-dev?style=flat-square&logo=github&logoColor=white&labelColor=0284c7&color=e0f2fe&label=Followers" alt="Followers" /></a>
<a href="mailto:wjc2569878796@gmail.com"><img src="https://img.shields.io/badge/Gmail-wjc2569878796%40gmail.com-0284c7?style=flat-square&logo=gmail&logoColor=white&labelColor=0ea5e9&color=e0f2fe" alt="Email me" /></a>
<img src="https://img.shields.io/badge/Focus-AI%20Agents-0284c7?style=flat-square&logo=probot&logoColor=white&labelColor=0ea5e9&color=e0f2fe" alt="Focus" />
<img src="https://img.shields.io/badge/Open%20to-Collaboration-0284c7?style=flat-square&logo=handshake&logoColor=white&labelColor=0ea5e9&color=e0f2fe" alt="Open to collaboration" />

</div>

<br/>

<table width="100%">
<tr>
<td width="55%" valign="top">

## 🙋 About Me

- 🔭 Working on **backend services** and **AI-agent tooling**
- 🌱 Deep-diving into **LangChain / LangGraph**, RAG pipelines, and multi-agent systems
- ⚙️ I automate everything that gets repeated twice
- 🛠️ Love building small tools that make daily development smoother
- 🚀 Open-sourced my own projects under [**VibeStack-AI**](https://github.com/VibeStack-AI) — check them out below!
- 💬 Ask me about Python automation, LLM apps, and dev workflows

</td>
<td width="45%" valign="top">

## 🧰 Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,ts,bash&perline=4&theme=light" alt="Languages" />

**Frameworks & Tools**

<img src="https://skillicons.dev/icons?i=fastapi,react,nodejs,docker,git,linux,vscode,postgres&perline=4&theme=light" alt="Tools" />

</td>
</tr>
</table>

## VibeStack-AI

<table width="100%">
<tr>
<td width="50%" valign="top">

<a href="https://github.com/VibeStack-AI/agent-rules">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=VibeStack-AI&repo=agent-rules&theme=default&hide_border=true&bg=ffffff&title_color=0284c7&text_color=334155&icon_color=0ea5e9" alt="agent-rules" />
</a>

One rulebook, two agents. `agent-rules` keeps the global rules for Claude Code and Codex CLI in sync so I don't end up editing the same file in two places.

- Single source of truth in `rules/core.md`; `make sync` generates the per-platform files.
- `make install` symlinks `~/.claude/CLAUDE.md` and `~/.codex/AGENTS.md`; `--dry-run`, `make status`, `make uninstall` are all there.
- Existing files are auto-backed up to `.bak.<timestamp>` before install.
- CI checks that `dist/` matches `rules/` so nothing drifts silently.
- Optional CodeGraph integration: when a project has `.codegraph/`, the rules tell the agent to explore symbols before touching files.

</td>
<td width="50%" valign="top">

<a href="https://github.com/VibeStack-AI/vibestack-fastapi">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=VibeStack-AI&repo=vibestack-fastapi&theme=default&hide_border=true&bg=ffffff&title_color=0284c7&text_color=334155&icon_color=0ea5e9" alt="vibestack-fastapi" />
</a>

A FastAPI template I keep coming back to. `vibestack-fastapi` is the version I'd start a new internal service from today.

- Split client / backoffice APIs with separate Swagger and ReDoc.
- Async throughout: FastAPI, SQLAlchemy 2.0 async, Celery for background work.
- Postgres + Redis + Alembic migrations; JWT auth on the backoffice side.
- Documentation nav gated by `ENV` — off in production, OpenAPI JSON export still available.
- `docker-compose up -d` brings up Postgres, Redis, and the app.

</td>
</tr>
</table>

<sub><a href="https://github.com/VibeStack-AI">VibeStack-AI</a> is the org I keep these projects under.</sub>

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=wujuncheng-dev&theme=default&hide_border=true&background=ffffff&ring=0284c7&fire=0ea5e9&currStreakLabel=0284c7&sideLabels=334155&dates=64748b" alt="Streak Stats" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=wujuncheng-dev&theme=minimal&hide_border=true&color=0c4a6e&line=0284c7&point=0ea5e9&area=true&area_color=e0f2fe" width="94%" alt="Activity Graph" />

</div>

## Popular repositories

<div align="center">

<a href="https://github.com/VibeStack-AI/agent-rules">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=VibeStack-AI&repo=agent-rules&theme=default&hide_border=true&bg=ffffff&title_color=0284c7&text_color=334155&icon_color=0ea5e9" alt="agent-rules" />
</a>
<a href="https://github.com/VibeStack-AI/vibestack-fastapi">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=VibeStack-AI&repo=vibestack-fastapi&theme=default&hide_border=true&bg=ffffff&title_color=0284c7&text_color=334155&icon_color=0ea5e9" alt="vibestack-fastapi" />
</a>

</div>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/wujuncheng-dev/wujuncheng-dev/output/github-snake.svg" alt="Contribution Snake" />

</div>

<div align="center">

<img src="assets/footer.svg" width="100%" alt="Footer" />

<sub>✨ Thanks for stopping by — have a nice day! ✨</sub>

</div>
