# ClawManager Fleet Control

ClawManager Fleet Control is a hosted remote MCP for ClawManager.

This repository is a public documentation project for ClawManager Fleet Control. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://clawmanagerfleet.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=readme_home
- Pricing: https://clawmanagerfleet.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=readme_pricing
- Checkout: https://clawmanagerfleet.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://clawmanagerfleet.clauxel.com/mcp
- Server card: https://clawmanagerfleet.clauxel.com/server-card.json
- Registry name: `com.clauxel.clawmanagerfleet/clawmanagerfleet-mcp`
- Tools: `request_agent_instance`, `check_instance_status`, `close_agent_instance`, `export_runtime_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: request_agent_instance
- MCP tool: check_instance_status
- MCP tool: close_agent_instance
- MCP tool: export_runtime_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
