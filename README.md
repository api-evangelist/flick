# Flick

Flick is an AI filmmaking studio that lets creators direct short films with AI on an infinite, node-based canvas. Rather than a linear prompt-to-clip generator, Flick gives directors a nonlinear workspace to plan, iterate and assemble complete narratives of any length — generating scenes, keeping character faces and styles consistent across shots, controlling shot composition, and editing images by reference.

- Website: https://flick.art
- Documentation: https://flick.art/docs/
- Pricing: https://flick.art/pricing (free tier with 300 credits; paid plans from $5/mo)
- Community: https://discord.gg/SPYgXej78k

Founded by Ray Wang (previously a founding engineer on the Instagram AI team) and award-winning filmmaker Zoey Zhang. Y Combinator- and GV-backed.

## API surface

Flick does **not** currently publish a public developer API, SDKs, webhooks, or an MCP server. The `/api/` path is an internal application API that `robots.txt` explicitly disallows. No first-party packages were found on npm or PyPI, and no public GitHub organization exists. Flick does publish a real `llms.txt`, captured verbatim in `llms/`.

## Identity note

This repo was created as a merged VC-portfolio stub from **two different companies named "Flick"**:

- **Bullpen Capital's Flick** (`flickapp.com`) — a sports fan-engagement group-chat app founded in Edinburgh by FanDuel co-founders Nigel Eccles and Rob Jones. It is **deadpooled**, and `flickapp.com` now resolves to an unrelated Indonesian gambling spam site (verified 2026-07-20). That domain has been removed from this profile.
- **GV's Flick** (`flick.art`) — the live AI filmmaking studio profiled here.

The defunct `flickapp.com` company should be tracked separately or dropped rather than conflated with this one.
