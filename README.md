# Kingdom Office

A virtual business office of AI agents. The business is the context, the agents
are the workers, and `outputs/` is where finished work lands.

**Phase 1:** the YouTube team, a 4-agent production line for a faith-based
channel that reaches the general public.

## The office layout

```
CLAUDE.md            The business context. Every agent reads it first.
office/brand.md      Channel name candidates, voice, visual style.
.claude/agents/      The 4 agents' job descriptions.
.claude/commands/    The /episode "start button" that runs the line in order.
outputs/             The four trays where finished work lands.
```

## How to use it (phone or computer)

1. Open a Claude Code session on this repository (in the Claude app or at claude.ai/code).
2. Type `/episode` and press send, or add an idea: `/episode AI and job security`.
3. Pick one of the 3 topics the Trend Scout brings back.
4. Wait for the team to finish, then read the result in `outputs/04-approved/`.
5. Record, edit and upload yourself. Agents never publish.

You can also talk to any agent directly, e.g.
"Ask the scriptwriter to make the hook in this script stronger."

## Words to know

- **Agent:** an AI worker with one job, defined by a text file in `.claude/agents/`.
- **Command:** a shortcut you type starting with `/`, defined in `.claude/commands/`.
- **Repository (repo):** this project folder, with its full history saved on GitHub.
- **Commit:** a saved snapshot of the project, with a note saying what changed.
- **Push:** uploading your commits to GitHub so every device can see them.
