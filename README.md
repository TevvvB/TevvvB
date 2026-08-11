# ((•ᴗ•))

Terminal-first tools for people who run coding agents all day.

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![CLI](https://img.shields.io/badge/-CLI-111827?style=flat-square&logo=gnometerminal&logoColor=white)
![Coding Agents](https://img.shields.io/badge/-Coding_Agents-8B5CF6?style=flat-square&logo=anthropic&logoColor=white)
![Git Worktrees](https://img.shields.io/badge/-Git_Worktrees-F05032?style=flat-square&logo=git&logoColor=white)

I spend my days driving several coding agents at once, which creates a problem the
agents themselves do not solve: a dozen sessions, a dozen worktrees, and no way to
tell at a glance which one is healthy and which one has quietly gone sideways. The
tools here come out of that. I like them small, local-first, installable in one
command, and legible without a dashboard.

## 🐣 parallel-harness-pets

**[A creature for every git worktree](https://github.com/TevvvB/parallel-harness-pets)**, living in your coding agent's status line.
Species comes from the branch name, mood tracks how tidy that branch is.

```
((•ᴗ•))  owl  · feat/checkout-flow  ♥♥♥♥♥             ·  Opus 5
[@_@]    frog · fix/session-leak    ♥♡♡♡♡  28△ 27↑    ·  Opus 5
```

Most terminal pets belong to *you* - one creature, nurtured over time. This one
belongs to a **worktree**. Six worktrees means six creatures alive at once, each
recognisable at a glance, so you always know which session you are looking at and
which one is in trouble.

Works with Claude Code, Codex CLI, tmux, your shell prompt, or any harness via
`pets render --format=json`. One command to install, one to reverse it.

```sh
brew install TevvvB/tap/parallel-harness-pets && pets install
```

## What I care about

- Agent workflows that stay legible when you are running six of them in parallel
- Terminal and status-line interfaces that inform without demanding attention
- One-command installs that wire themselves in and can be cleanly reversed
- Small sharp binaries over frameworks, local state over services
- Playful software that is still genuinely useful on a workday

## Activity

![Contribution graph](https://ghchart.rshah.org/TevvvB)

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/TevvvB)

---

If you are building for coding agents - orchestration, status surfaces, worktree
tooling, anything that makes parallel agent work less chaotic - I want to see it.
