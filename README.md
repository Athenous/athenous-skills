# Athenous Skills

A collection of **50 ready-to-use AI marketing workflows** for agencies, marketers, founders and campaign managers.

Each Skill is a standalone `SKILL.md` with:
- a clear task description and activation guidance
- required inputs and a missing-information strategy
- a specialist workflow with concrete steps
- a defined output contract and copy/paste starter prompt
- an example invocation and quality checks
- optional Athenous MCP guidance where live data or actions may help

**Skills are instructions, not executable integrations.** They work with user-provided information without Athenous MCP. When Athenous MCP is connected, the agent must discover the tools and schemas actually exposed in that session. Installing Skills does not connect accounts, grant permissions or make unsupported platform operations possible.

## Quick start

### Claude Code — plugin installation

From a Claude Code session:

```bash
/plugin marketplace add Athenous/athenous-skills
/plugin install athenous-marketing-skills@athenous-skills
```

If you prefer direct installation, clone the repository and copy the selected Skill folders into your project's `.claude/skills/` directory:

```bash
git clone https://github.com/Athenous/athenous-skills.git
mkdir -p .claude/skills
cp -R athenous-skills/skills/* .claude/skills/
```

### Cursor

Copy selected Skill folders into your project's `.cursor/skills/` directory (or use the Agent Skills location supported by your Cursor version):

```bash
mkdir -p .cursor/skills
cp -R athenous-skills/skills/* .cursor/skills/
```

### Codex and other Agent Skills-compatible clients

Copy selected Skill folders into the `.agents/skills/` directory supported by your project/client:

```bash
mkdir -p .agents/skills
cp -R athenous-skills/skills/* .agents/skills/
```

Client support and discovery paths can change. Check your AI client's current Skills documentation if it does not automatically discover the files. The Skill content is plain Markdown and can also be opened and used manually.

## How to use a Skill

1. Install the Skill or open its `SKILL.md`.
2. Ask for the task by name or describe the task clearly.
3. Use the included **Copy/paste prompt** as a starting point.
4. Provide the requested exports, links, business context or creative assets.
5. Review the result, assumptions and data gaps before acting.

Example:

```text
Use meta-ads-optimizer for the Acme account.
Goal: improve qualified lead volume without increasing monthly spend.
Period: the last 30 complete days.
Here are the campaign and ad-level exports: [attach files].
Audit performance, identify the biggest bottlenecks and return prioritized
recommendations. Do not change live campaigns.
```

## Connect Athenous MCP (optional)

Athenous MCP is a separate data and action connection. Connect it using the current instructions provided by Athenous. Once connected, a Skill may use only the tools, fields and operations actually exposed to the current session and authorized for the active user/client.

- Start with read-only analysis when available.
- Never assume an account, integration, report, metric or write operation exists.
- Keep client/workspace data isolated.
- Before publishing, changing budgets, editing campaigns, inviting users or performing another consequential write, show the exact proposed action and obtain explicit confirmation.
- Never put API keys, tokens or passwords in Skill files.

## Requirements

To get started, you need:

- An AI assistant that supports Skills, such as [Claude](https://claude.ai/), [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview), [Cursor](https://cursor.com/), or another compatible agent.
- For live marketing account data: an [Athenous account](https://app.athenous.io/) and the [Athenous MCP connection](https://mcp.athenous.io/mcp), with the relevant advertising or social accounts connected and authorized.
- No Athenous MCP connection is required to use the Skills with pasted exports, uploaded reports, URLs or other information you provide manually.

The exact subscription or plan required depends on the AI client and its current Skills support. Check the provider's current requirements.

---

## Support

The Athenous Skills collection is **free to access**.

Need help? Contact us at [**contact@athenous.io**](mailto:contact@athenous.io).

Learn more about [Athenous](https://athenous.io/).

---

## Catalogue

Version **0.3.0** contains 50 Skills across five categories. See [the full catalogue](docs/catalogue.md) and [catalogue.json](catalogue.json).

| Category | Skills |
|---|---:|
| Marketing strategy | 10 |
| Social media and content | 10 |
| Paid advertising | 10 |
| Analytics and optimization | 10 |
| Agency workflows and automation | 10 |
| **Total** | **50** |

## Quality principles

- Each Skill has a distinct domain and task; it is not just a renamed generic prompt.
- Inputs, assumptions, evidence and limitations are explicit.
- Outputs are designed to be handed to a marketer, agency team or client.
- Recommendations are prioritized by impact, confidence, effort and risk.
- Unknown data is labeled rather than fabricated.
- Live actions require explicit user confirmation and server-side authorization.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidance and [SECURITY.md](SECURITY.md) for responsible disclosure.

## License

The Skills are provided at no charge. **No repository license has been selected yet**, so do not assume permission to redistribute, relicense or commercially republish the content.
