# LumoCue + Claude Code

LumoCue provides a physical status and attention indicator for Claude Code.

Instead of repeatedly checking the terminal, LumoCue lets you see the state of your coding agent from across your desk or room.

## Status States

| Claude Code state | LumoCue |
|---|---|
| Agent working | 🔵 Blue — Working |
| Task finished / ready | 🟢 Green — Finished |
| User input or attention required | 🔴 Red — Needs Attention |
| Attention alert | 🔔 Chirp |
| Alert acknowledged | 👆 Touch |

## Why Use a Physical Indicator?

Claude Code can work autonomously while you move your attention elsewhere.

The problem is knowing when to come back.

LumoCue moves that information outside the terminal and into peripheral vision:

**Start task → Claude works → LumoCue shows status → return when needed**

No repeated terminal checking is required.

## Claude Code Integration

Claude Code is currently the primary tested AI coding-agent integration for LumoCue.

LumoCue responds to agent workflow events and converts them into simple physical status signals.

Detailed installation and configuration instructions will be maintained here as the integration evolves.

## Troubleshooting

If LumoCue does not respond as expected:

1. Confirm that the LumoCue device is connected by USB.
2. Confirm that the LumoCue software is installed and running.
3. Confirm that your Claude Code integration is enabled.
4. Restart the LumoCue application if necessary.
5. Reconnect the LumoCue USB device.
6. Test the Claude Code workflow again.

If the problem continues, open an Issue in this repository and include:

- Operating system
- Claude Code version
- LumoCue software version
- Expected status
- Status actually displayed
- Steps needed to reproduce the problem

Please do not post passwords, API keys, tokens, or other sensitive information in an Issue.

## Want to Integrate Another Agent?

LumoCue is designed to expand beyond Claude Code.

We are interested in integrations with:

- Codex
- OpenCode
- Cursor
- Gemini CLI
- Other AI coding agents

If your agent exposes useful workflow events through hooks, APIs, scripts, logs, or another interface, open an Issue and describe what is available.

## LumoCue

Learn more about the hardware:

https://lumocue.dev
