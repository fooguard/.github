![Foo Guard](./assets/foo-guard-mark.svg)

# Foo Guard

Foo Guard is a pre-deployment security scanner for AI agent configurations, MCP/tool definitions, permissions, credentials, and autonomy risks.

It uses deterministic static analysis to identify risky permissions, secret exposure, dangerous tool access, approval gaps, and unsafe autonomy before AI agents reach production.

Foo Guard can enforce security policy through GitHub Checks, CI, CLI workflows, and `.fooguard.yml`.

## What Foo Guard scans

- AI agent configurations
- MCP/tool definitions
- permissions and capabilities
- exposed credentials and secret-like values
- approval gaps
- unsafe autonomy
- compound-risk combinations

## How Foo Guard fits

Foo Guard focuses on static, pre-deployment analysis.

It does not currently:

- proxy live prompts
- inspect live model responses
- sit inline between applications and LLMs
- act as a runtime LLM firewall

## Links

- Website: https://fooguard.com
- About: https://fooguard.com/about
- Documentation: https://fooguard.com/docs
- Pricing: https://fooguard.com/pricing
- Research: https://fooguard.com/research/static-ai-agent-security-analysis
- AI Agent Security Scanner: https://fooguard.com/ai-agent-security-scanner
- MCP Security Scanner: https://fooguard.com/mcp-security-scanner
