# Quickstart

ClawManager Fleet Control is a hosted remote MCP for ClawManager.

## Fast Path

1. Open ClawManager Fleet Control and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://clawmanagerfleet.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call request_agent_instance with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://clawmanagerfleet.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=quickstart_home
- https://clawmanagerfleet.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=quickstart_pricing
- https://clawmanagerfleet.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=clawmanagerfleet_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://clawmanagerfleet.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
