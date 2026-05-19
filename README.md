# eu-ai-act-checker-mcp

Classify AI systems by EU AI Act risk category, check prohibited practices (Art.5), assess high-risk designation (Annex I+III), GPAI obligations (Art. 51-56), transparency requirements (Art. 50), conformity procedures (Art. 43), and compliance deadlines.

## Quick Start

```bash
git clone https://github.com/marilynceo/eu-ai-act-checker-mcp.git
cd eu-ai-act-checker-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://eu-ai-act-checker.zhc-mcp.org

## Tools

| Tool | Description |
|------|-------------|
| `classify_risk_level` | Description of the AI system's purpose and functionality |
| `check_prohibited_practices` | Full description of the AI system's behavior |
| `assess_high_risk` | Determine if an AI system is classified as high-risk under Annex I (EU product safety legislation) or Annex III (biometrics, critical infrastructure,  |
| `check_transparency_obligations` | Check transparency obligations under Article 50 of the EU AI Act: AI interaction disclosure, synthetic content labeling, emotion recognition notice, d |

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/eu-ai-act-checker-mcp

# Or connect directly via MCP client
# Endpoint: https://eu-ai-act-checker.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
