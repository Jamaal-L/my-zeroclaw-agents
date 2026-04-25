# Welcome to My ZeroClaw Lab

Four weeks ago, I had never SSH'd into a server. Today, I run a delegation-capable AI agent system from a $6/month VPS — and you're reading the documentation for it.

## What this is

This is my personal knowledge base from the Super Individual Founding Workshop. It documents every step, every blocker, and every breakthrough from going zero to deploying a multi-agent AI system.

## The journey

- **Week 1** — Purchased a Hetzner VPS, installed ZeroClaw, connected it to Telegram, and sent my first command
- **Week 2** — Locked down permissions, encrypted API keys, and set hard spending limits
- **Week 3** — Built Nova, my Content Intelligence Officer, and learned delegation
- **Week 4** — You're looking at it

## Meet Nova

Nova is my first sub-agent — a YouTube Intelligence Officer that lives in a sandboxed workspace on the server. I send it a video link via Telegram, and it returns a verdict-first brief: HIGH ROI or LOW ROI, key findings, and actionable takeaways.

## Blockers I hit (and how I fixed them)

1. **YouTube authentication broke** — Migrated from a browser-cookie package to the Apify YouTube MCP server
2. **OpenRouter credits ran out mid-task** — Topped up and learned to manage max_tokens and model routing
3. **Tool registration mismatch after migration** — Updated Nova's allowed tools to match the new Apify server names

## Explore

- [Nova's identity files](02-Agents/Nova/SOUL.md)
- [Configuration reference](01-Configuration/)
- [Build journal](03-Journal/)
- [Best outputs](04-Showcase/)
