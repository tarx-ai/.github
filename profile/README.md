# TARXAN Inc

**TARX** — Free to think.

Local-first AI work software: start on your **Computer**, scale to **Supercomputer** when permitted, run **Enterprise Private** on your infrastructure.

| | |
|---|---|
| Product | [tarx.com](https://tarx.com) |
| Download | [tarx.com/download](https://tarx.com/download) |
| Docs | [docs.tarx.com](https://docs.tarx.com) |
| MCP | [mcp.tarx.com](https://mcp.tarx.com) |

## Naming

| Term | Meaning |
|------|---------|
| **TARXAN Inc** | Company |
| **TARX** | Product |
| **TARX Desktop** | Mac desktop app |
| **tarx-desktop** | Desktop repository |

## Core repositories

| Repo | Role |
|------|------|
| **[tarx-desktop](https://github.com/tarx-ai/tarx-desktop)** | TARX Desktop (Electron shell) — public product surface |
| **[tarx-cli](https://github.com/tarx-ai/tarx-cli)** | Install & manage local Computer runtime |
| **[tarx-mcp](https://github.com/tarx-ai/tarx-mcp)** | Canonical remote MCP (`mcp.tarx.com`) |
| **[tarx](https://github.com/tarx-ai/tarx)** | Product monorepo / beachhead (when published) |
| **[tarx-sdk](https://github.com/tarx-ai/tarx-sdk)** | Client SDK stubs & contracts |
| **[tarx-examples](https://github.com/tarx-ai/tarx-examples)** | Design-partner examples |

Related private product code (not all public): Screens (`tarx-web`), runtime core, mobile.

## Install trust (Desktop)

1. Download only from [tarx.com/download](https://tarx.com/download)
2. Verify **SHA-256** on the page against your file
3. Prefer **notarized** builds — Gatekeeper: *Notarized Developer ID*
4. Read release notes for the version you install

```bash
shasum -a 256 ~/Downloads/TARX-*-arm64.dmg
spctl --assess --type execute -v /Applications/TARX.app
```

## Public status

- macOS Desktop: public beta (signed / notarized releases)
- Windows Desktop: not public yet
- Voice production: closed
- Unrelated forks and experiments are **archived** to keep the org readable

## Contact

- Web: [tarx.com](https://tarx.com)
- Enterprise: via product surfaces on tarx.com
