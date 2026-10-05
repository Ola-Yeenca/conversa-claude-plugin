# Conversa Workflow Automation for Claude

This is the public Claude plugin bundle for Conversa. It helps real-estate professionals turn supplied listing facts and buyer enquiries into grounded multilingual reply drafts, unanswered-question lists, and qualification steps without a Conversa account. It can also prepare an optional consent-gated demonstration of Conversa's existing enquiry-to-WhatsApp workflow.

The bundle connects to one anonymous remote MCP server:

`https://conversa-plugin-production.up.railway.app/public/mcp`

## Documentation

- [Connect and use Conversa](https://conversa-plugin-production.up.railway.app/docs)
- [Connector data handling](https://conversa-plugin-production.up.railway.app/privacy)
- [Conversa website](https://c.smeanalytica.com/)
- [Support](https://c.smeanalytica.com/contact)

The connector is deployed and its public overview, documentation, privacy notice, and favicon are reachable. This repository is public. Directory submission, review, approval, and publication are separate provider states and should be checked in the Claude directory portal.

## Local validation

With Claude Code installed, run:

```bash
claude plugin validate .
```

The repository contains only the public plugin manifest, branded directory icon, public MCP reference, skill, and this README. It contains no backend source, credentials, private agency configuration, or customer data.

## Security reports

Report a suspected security vulnerability through the [SME Analytica support page](https://c.smeanalytica.com/contact). Include the plugin version and affected tool, but do not include credentials, phone numbers, customer data, or an active consent capability.

## License

The scoped MIT license in [`LICENSE`](LICENSE) applies only to `.claude-plugin/plugin.json`, `.mcp.json`, `skills/conversa-enquiry/SKILL.md`, and this `README.md`. Conversa and SME Analytica names, trademarks, logos, icons, other brand assets, the MCP runtime and backend, the browser demo, and all other source remain outside that grant.
