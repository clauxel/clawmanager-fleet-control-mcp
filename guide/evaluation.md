# Evaluation Guide

Use this page to evaluate whether ClawManager Fleet Control fits a real workflow.

## What To Test

- ClawManager
- ClawManager Fleet Control
- ClawManager Fleet Control documentation
- ClawManager Fleet Control remote MCP
- clawmanagerfleet server card

## Expected Evidence

- Open ClawManager Fleet Control and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://clawmanagerfleet.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call request_agent_instance with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://clawmanagerfleet.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=evaluation_checkout
