# spam-call-shield

**English** · [Türkçe](README.tr.md)

**An AI-agent kit for fighting unwanted sales calls and texts, the legal way.**

Turn Claude, ChatGPT or Gemini into a careful assistant that helps you:

1. **Opt out** of telemarketing in your country's official system.
2. **Log** every unwanted call or text that still arrives, in a format authorities and courts accept.
3. **Identify** who is really behind a number, using public sources only.
4. **Prepare** the complaint, demand letter or small-claims paperwork.

The agent never sends, files or calls anything on its own. You stay in control of every step.

> Inspired by a viral post where someone asked an AI agent to register their number on the US Do Not Call list and track violations. The agent itself admitted the hard limits: spoofed VoIP numbers can't be traced without a subpoena, and it wouldn't file anything without permission. This kit is built around that honesty.

## Pick your region

| Region | What you can realistically get | Status | Start here |
|---|---|---|---|
| 🇺🇸 **United States** | Statutory damages of up to **$500 per call** (up to 3× if willful, at the court's discretion) under the TCPA | ✅ Ready | [regions/us](regions/us/README.md) |
| 🇹🇷 **Türkiye** | The company gets an **administrative fine**; the money goes to the state, not to you | ✅ Ready | [regions/tr](regions/tr/README.md) |
| 🇪🇺 **European Union** | GDPR rights: ask *"where did you get my number?"*, demand erasure, complain to the regulator | 🤝 **Contributions wanted** | [regions/eu](regions/eu/README.md) |

Other countries: see [CONTRIBUTING.md](CONTRIBUTING.md). Every legal claim needs an official source.

## How to use it (5 minutes)

**Option A: any chatbot (no install)**
1. Open your region's folder and copy the agent prompt (`regions/us/prompts/agent-prompt.md` or `regions/tr/promptlar/ajan-prompt.md`).
2. Paste it into Claude, ChatGPT or Gemini as the first message.
3. Keep your call log in the CSV template from the same folder (Excel, Google Sheets or Numbers can open it).

**Option B: Claude Code**
Copy `claude-skill/spam-call-shield/` into `~/.claude/skills/` and type `/spam-call-shield`.

## What's in the box

```
core/            Rules every agent follows + generic log and caller-research guides
regions/us/      Do Not Call Registry, TCPA, demand letter, small claims
regions/tr/      İYS opt-out, Ticaret Bakanlığı complaint (Turkish)
regions/eu/      GDPR outline + country template (contributions wanted)
claude-skill/    Ready-made Claude Code skill
examples/        Fully worked examples with fictional data
```

## Read before you start

- **Not legal advice.** See [DISCLAIMER.md](DISCLAIMER.md). Laws change; every region folder lists its sources and the date they were checked.
- **Privacy.** Your call log contains personal data. Read [PRIVACY.md](PRIVACY.md) before pasting anything into an AI chat.
- **Recording calls can be illegal.** In Türkiye, and in several US states, recording a call without the other side's consent is a crime. The guides explain safe ways to keep evidence.
- **Scams are different.** If a caller is trying to steal money or data, report them to the police or fraud authority. This kit handles telemarketing, not fraud.

## License

[MIT](LICENSE). Use it, fork it, translate it.
