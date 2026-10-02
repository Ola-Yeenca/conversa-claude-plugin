# Conversa Workflow Automation for Claude

This is the public Claude plugin bundle for Conversa. It helps real-estate professionals turn supplied listing facts and buyer enquiries into grounded multilingual reply drafts, unanswered-question lists, and qualification steps without a Conversa account. It can also prepare an optional consent-gated demonstration of Conversa's existing enquiry-to-WhatsApp workflow.

The bundle connects to one anonymous remote MCP server:

`https://conversa-plugin-production.up.railway.app/public/mcp`

## Documentation

- [Connect and use Conversa](https://conversa-plugin-production.up.railway.app/docs)
- [Connector data handling](https://conversa-plugin-production.up.railway.app/privacy)
- [Conversa website](https://c.smeanalytica.com/)
- [Support](https://c.smeanalytica.com/contact)

The connector is deployed and its public overview, documentation, privacy notice, and favicon are reachable. This repository is public, but its Claude directory draft has not been submitted or approved.

## Local validation

With Claude Code installed, run:

```bash
claude plugin validate .
```

The repository contains only the public plugin manifest, branded directory icon, public MCP reference, skill, and this README. It contains no backend source, credentials, private agency configuration, or customer data.

## License

No license has been selected or granted for this repository. SME Analytica retains all rights unless it adds an explicit license later.
