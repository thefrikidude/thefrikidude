## yoo!
so u finally found me. here's a cookie for u 🍪 *(don't worry, i won't track u)*

i'm currently exploring scalable backend architectures, system design, ai and cloud *(basically fcking around and finding things out)*

**story time:**

my interest in software started back in 9th grade after watching *iron man* —
got inspired by jarvis, and never really stopped exploring since.

### open source stuff

i occasionally fix things in codebases i didn't write.

**[Orca](https://github.com/stablyai/orca)** — 3 merged PRs + 2 co-authored
- [#35987](https://github.com/stablyai/orca/pull/35987) — co-authored the fix that stopped Orca's terminal daemon from spawning `ps` ~1,000×/min on macOS, which kept `syspolicyd` at 70–270% CPU. my measurements and diagnosis led to reading the process table in-process. *([credited by the maintainer](https://github.com/stablyai/orca/pull/35987#issuecomment-6506406272))*
- [#28317](https://github.com/stablyai/orca/pull/28317) — fixed launch readiness for Pi-based coding agents.
- [#33580](https://github.com/stablyai/orca/pull/33580) — fixed Antigravity account saving with missing ID tokens.
- [#34403](https://github.com/stablyai/orca/pull/34403) — fixed Claude session restarts getting blocked by the live session cap.
- [#33656](https://github.com/stablyai/orca/pull/33656) — co-authored a fix for account recognition after token refresh.


**[Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator)** — 1 merged PR
- [#6902](https://github.com/OrchestratorInc/agent-orchestrator/pull/6902) — enabled Claude Code's to-do tools in chat sessions.
