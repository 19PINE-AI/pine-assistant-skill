# Pine Assistant Skill

ClawHub skill for [Pine AI](https://19pine.ai) assistant — let your agent handle customer service, bill negotiations, reservations, and more.

## Install

```bash
openclaw skills install pine-assistant
```

The skill requires the `pine` CLI:

```bash
pip install pineai-cli
```

## What it does

This skill gives your AI agent the ability to:

- **Negotiate bills** — Comcast, AT&T, insurance, etc.
- **Cancel subscriptions** — Hulu, gym memberships, etc.
- **Make reservations** — restaurants, appointments, hotels
- **Dispute charges** — unauthorized transactions, billing errors
- **Resolve account issues** — replacements, refunds, closures
- **Outreach** — call businesses for quotes, availability, info

## How it works

The skill wraps the `pine` CLI, which talks to both the Pine AI Assistant and Voice APIs. Your agent uses shell commands (`pine sessions list`, `pine send`, `pine task start`, etc.) to manage sessions and tasks.

Authentication is handled interactively via `pine auth login` — email verification, no manual token setup.

## Also see

- [pine-voice](https://clawhub.ai/pineclaw/pine-voice) — Direct phone calls via Pine AI voice agent
- [Pine CLI](https://github.com/19PINE-AI/pineai-cli) — The unified CLI this skill wraps
