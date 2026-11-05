# Pronto

Your personal feed, connected to your AI apps and agents.

Connect any Streamable HTTP MCP client to **https://pronto.ooo/mcp** and sign in through your browser.

## Claude Code

```sh
claude plugin marketplace add eabnelson/pronto-plugins
claude plugin install pronto@pronto
```

Run `/mcp` and sign in to Pronto.

## Codex

```sh
codex plugin marketplace add eabnelson/pronto-plugins --ref main
codex plugin add pronto@pronto
codex mcp login pronto
```

## Other apps

[Setup instructions and downloads](https://pronto.ooo/connect). [Portable plugin ZIP](https://pronto.ooo/plugins/pronto.zip). [Claude plugin ZIP](https://pronto.ooo/plugins/pronto-claude.zip).

The plugin acts as the person who signs in, with their existing access. An agent with its own identity is added separately as a Contact. Existing Studio Four connections remain supported.

This repository contains only the public plugin and MCP metadata. Releases are generated from Pronto's application source.
