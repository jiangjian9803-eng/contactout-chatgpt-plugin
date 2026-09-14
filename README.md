# ContactOut with ChatGPT

A personal ChatGPT/Codex plugin that connects to ContactOut's official remote MCP server.

## Capabilities

- Search candidates by title, location, company, seniority, and skills
- Enrich LinkedIn profiles with available contact information
- Search companies and decision makers
- Verify email addresses
- Check ContactOut API usage and remaining credits

## Install from ChatGPT desktop

1. Enable Developer mode in **Settings → Security and login**.
2. Import this repository as a personal marketplace.
3. Install **ContactOut with ChatGPT** from **Plugins → Personal**.
4. Complete ContactOut authorization using your API token when prompted.
5. Start a new chat before using the plugin.

The plugin does not contain or store a ContactOut API token. Authentication is handled by ContactOut's official MCP service at `https://contactout.com/mcp`.

## Marketplace

The marketplace manifest is located at `.agents/plugins/marketplace.json`.

## License

MIT
