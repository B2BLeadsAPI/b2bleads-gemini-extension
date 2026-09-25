# B2BLeads for Gemini CLI

Search and enrich B2B business contacts (name, address, phone, website, email) by industry, location, and company size — directly from Gemini CLI.

## Install

```bash
gemini extensions install https://github.com/B2BLeadsAPI/b2bleads-gemini-extension
```

## Tools

- `search_leads` — find business leads by industry, location, and company size
- `list_industries` — list supported industry values
- `list_saved_lists` — list this account's saved lead lists
- `get_saved_list` — get the leads saved in a specific list

## Authentication

The B2BLeads MCP server uses OAuth 2.1 (PKCE). On first use, Gemini CLI will prompt you to sign in with your B2BLeadsAPI account. Get an account at [b2bleadsapi.com](https://b2bleadsapi.com).

## Links

- [B2BLeadsAPI](https://b2bleadsapi.com)
- [MCP server source](https://github.com/gtovtya/b2bleads-mcp)
