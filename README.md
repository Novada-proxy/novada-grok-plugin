# Novada MCP Plugin for Grok Build

Live web access for AI agents — search, extract, crawl, research, and structured platform data, all from a single hosted MCP server.

## What this plugin provides

| Capability | Details |
|---|---|
| Web search | Google, DuckDuckGo, and Yandex |
| Content extraction | Any URL, including anti-bot protected pages (Cloudflare, DataDome) |
| Site crawl & map | BFS/DFS crawl up to 20 pages; sitemap-based URL discovery |
| Multi-source research | 3–10 parallel searches, deduped, with cited source material |
| Structured platform data | 14 platforms: Amazon, Google, LinkedIn, YouTube, TikTok, X (Twitter), GitHub, Walmart, Instagram, Facebook, Bing, DuckDuckGo, Yandex, Perplexity AI |
| Browser automation | Full CDP browser sessions for JS-heavy pages and login flows |
| Proxy | Residential, ISP, mobile, datacenter, and static IPs with geo-targeting |

## MCP server

- **Endpoint:** `https://mcp.novada.com/mcp`
- **Transport:** Streamable HTTP
- **Auth:** OAuth 2.1 (dynamic client registration + PKCE S256) or Bearer key

## Getting started

**Option 1 — OAuth (no setup)**

Connect through Grok Build; the first tool call opens a browser authorization flow against your Novada account.

**Option 2 — Bearer key**

1. Sign up at [novada.com](https://www.novada.com) — free credits for new accounts.
2. Copy your API key from the dashboard.
3. Set `NOVADA_API_KEY=<your-key>` in your environment, or pass it as a Bearer token.

## Links

- Homepage: https://www.novada.com
- Developer docs: https://developer.novada.com
- Dashboard: https://dashboard.novada.com

## License

MIT — see [LICENSE](./LICENSE).
