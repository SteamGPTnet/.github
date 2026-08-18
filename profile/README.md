# SteamGPT

**[steamgpt.net](https://steamgpt.net)** - free Steam data API for humans, applications and AI agents. Steam profiles, SteamID conversion, VAC / game / community / trade bans, FACEIT stats, public friend graph, batch lookups and player comparison. No API key, no registration, no cookies, no tracking.

## Quick start

```bash
curl https://steamgpt.net/summary/76561197960287930.md
```

Every endpoint answers in HTML, markdown (`.md`), JSON (`.json`) and deterministic plain text (`.ai`).

## For AI agents

- **MCP server**: `https://steamgpt.net/mcp` (Streamable HTTP, no auth) - listed in the [official MCP Registry](https://registry.modelcontextprotocol.io/v0.1/servers/net.steamgpt%2Fsteamgpt/versions/latest) as `net.steamgpt/steamgpt`
- **The whole agent path on one page**: [steamgpt.net/ai](https://steamgpt.net/ai)
- **Docs**: [docs.md](https://steamgpt.net/docs.md) | [llms.txt](https://steamgpt.net/llms.txt) | [openapi.json](https://steamgpt.net/openapi.json) | [types.d.ts](https://steamgpt.net/types.d.ts)

## Repositories

| Repo | npm | What it is |
| --- | --- | --- |
| [steamgpt-mcp](https://github.com/SteamGPTnet/steamgpt-mcp) | [`steamgpt-mcp`](https://www.npmjs.com/package/steamgpt-mcp) | MCP server / stdio proxy (`npx -y steamgpt-mcp`) |
| [steamgpt-js](https://github.com/SteamGPTnet/steamgpt-js) | [`steamgpt`](https://www.npmjs.com/package/steamgpt) | Typed JavaScript client (`npm install steamgpt`) |

---

SteamGPT is an independent service and is not affiliated with Valve Corporation or Steam.
