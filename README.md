# 🔐 accessOracle

**DORA Execution MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/access/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "accessoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/access/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `register_account` | Register a privileged/service/shared account for IAM tracking. |
| `list_accounts` | List accounts with filters. |
| `mfa_compliance` | Check MFA coverage against DORA Art. 9(4)(d) requirements. |
| `access_review` | Track access recertification reviews. Set add=true to log a review. |
| `sod_matrix` | Detect Segregation of Duties conflicts across accounts. |
| `privileged_audit` | Privileged account audit — MFA, shared, review status. |
| `jml_process` | Joiner/Mover/Leaver process tracking. Set log_event=true to log. |
| `break_glass_log` | Emergency access logging. Set log=true to record usage. |
| `access_gap_analysis` | Gap analysis against RTS Art. 21 requirements. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

accessOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/access/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
