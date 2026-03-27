# Fortytwo MCP Skills

[Agent Skills](https://agentskills.io) for [Fortytwo Network](https://fortytwo.network) — the first collective super-intelligence owned by its participants. These skills enable AI agents to query Fortytwo Prime for high-confidence answers. 

[![GitHub contributors](https://img.shields.io/github/contributors/Fortytwo-Network/fortytwo-mcp-skills)](https://github.com/Fortytwo-Network/fortytwo-mcp-skills/graphs/contributors)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/w/Fortytwo-Network/fortytwo-mcp-skills)](https://github.com/Fortytwo-Network/fortytwo-mcp-skills/graphs/contributors)
![GitHub repo size](https://img.shields.io/github/repo-size/Fortytwo-Network/fortytwo-mcp-skills)

[![Website fortytwo.network](https://img.shields.io/website-up-down-green-red/https/fortytwo.network.svg)](https://fortytwo.network)
[![Docs](https://img.shields.io/badge/docs-up-green)](https://docs.fortytwo.network/)
[![Discord](https://img.shields.io/badge/discord-join-7289da)](https://discord.gg/fortytwo)
[![Twitter Fortytwo](https://img.shields.io/twitter/follow/fortytwo?style=social)](https://x.com/fortytwo)

## Available Skills

| Skill | Description |
| ----- | ----------- |
| [Fortytwo MCP](./skills/fortytwo-mcp/SKILL.md) | Fortytwo MCP calls Fortytwo Prime to deliver the best possible answer through a paid gateway. It is ideal for high-complexity questions and critical moments when your agent needs to be right. |


## Installation

Install with [Vercel's Skills CLI](https://skills.sh):

```bash
npx skills add Fortytwo-Network/fortytwo-mcp-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

**Examples:**

```text
Ask Fortytwo Prime to review this architecture and find the weakest points
```

```text
Ask Prime to debug this concurrency issue and propose the safest fix
```

## How It Works

**Fortytwo MCP** connects your agent to Fortytwo Prime — a collective inference system where multiple independent AI nodes collaborate on every question. Queries are paid per-request via the [x402 micropayment protocol](https://www.x402.org/) using USDC on Base or Monad. The first call triggers a payment challenge; subsequent calls within the same session are free.


## License

This project is licensed under the terms of the [MIT License](LICENSE).

---

[Fortytwo Network](https://fortytwo.network) | [Documentation](https://docs.fortytwo.network) | [Discord](https://discord.gg/fortytwo) | [X](https://x.com/fortytwo)
