# Coder Agent for Houston

AI coding agent for vibe coders. Delegate coding missions and planning sessions from a kanban board inside Houston.

## Features

- **Missions Board** — Kanban view of all coding tasks. Click "New Mission" to delegate work.
- **Planning Agent** — Separate AI mode that analyzes code and creates GitHub issues. Never commits.
- **Worktree Mode** — Each mission gets its own git worktree. Toggle in Configure tab.
- **Run Button** — Open your terminal in any worktree with one click.
- **Link Existing Repo** — Install into your project directory. No need to move files.

## Install

In Houston, go to **New Agent > GitHub** and paste:

```
https://github.com/ja-818/coder-agent
```

Then link your project directory when naming the agent.

## Configure

The **Configure** tab has two sections:

**Prompts** — Edit the system prompts for the Coder (execution) and Planner agents.

**Settings:**
- **Dev command** — The command to run your app (e.g. `pnpm dev`, `cargo run`). Used by the Run button.
- **Worktree mode** — When enabled, each new mission creates a separate git worktree.
