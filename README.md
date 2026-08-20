# lumocue-agent-integrations
Physical status light integrations for Claude Code and AI coding agents — stop watching the terminal.
# LumoCue — Physical Status Light for AI Coding Agents

**Stop watching the terminal. Let your AI agent signal you.**

LumoCue is a physical USB status light designed for AI coding workflows.

🔵 **Working** — your agent is working  
🟢 **Finished** — your task is complete  
🔴 **Needs attention** — your agent needs you  
🔔 **Chirp** — optional attention alert  
👆 **Touch** — acknowledge the alert

## Why LumoCue?

AI coding agents can work autonomously for minutes at a time, but that creates a new problem:

**How do you know when to come back?**

Instead of repeatedly checking the terminal, another window, or your phone, LumoCue moves agent status into your peripheral vision.

Start the task.  
Do something else.  
Come back when LumoCue tells you.

## Claude Code

Claude Code is the first AI coding workflow tested with LumoCue.

The goal is simple:

Claude Code → status event → LumoCue → physical signal

## Beyond Claude Code

We want LumoCue hardware to be useful across the AI coding ecosystem.

Potential integrations include:

- Claude Code
- OpenAI Codex
- OpenCode
- Cursor
- Gemini CLI
- Other agentic development tools

If your coding agent can expose its state through hooks, scripts, APIs, logs, or other events, there may be a way to connect it to LumoCue.

## Build an Integration

This repository is the public home for:

- Integration guides
- Agent adapters
- Example scripts
- Setup instructions
- Troubleshooting
- Community experiments
- Requests for additional AI-agent support

The core LumoCue firmware and proprietary hardware implementation are not published here.

The goal is to provide enough of an interface for developers to experiment with new agent integrations without modifying the device firmware.

## Current Status

| Integration | Status |
|---|---|
| Claude Code | ✅ Tested |
| Codex | 🧪 Planned / community exploration |
| OpenCode | 🧪 Planned / community exploration |
| Cursor | 🧪 Planned / community exploration |
| Gemini CLI | 🧪 Planned / community exploration |
| Other agents | 💡 Ideas welcome |

## Have an Agent You Want LumoCue to Support?

Open an Issue and tell us:

1. Which AI coding agent you use
2. What events/status information it exposes
3. How you currently know when the agent finishes or needs attention
4. What LumoCue behavior you would like

Contributions, experiments, and integration ideas are welcome.

## LumoCue Hardware

Learn more about the physical LumoCue device:

**https://lumocue.dev**

---

**LumoCue**

Simple signals. Less screen watching.
