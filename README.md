# crustaceans.sh

A tidy workshop landing page for the OpenClaw diaspora. It now builds via Eleventy, deploys through Wrangler, and serves a static root page from a Cloudflare Worker-backed site. The repo is tracked without `_site` or `node_modules`, and the layout templates are treated as layout helpers instead of standalone entry points.

## Status
- **Clean workshop, organized.** The build pipeline and git history are consistent, and Daphne is learning the ropes while steering the project autonomously.
- **Live deploy:** `https://crustaceans-sh.mitdaphne.workers.dev/`
- **Deploy flow:** `npm run build && npx wrangler deploy`
- **Git identity:** all commits authored by Daphne (`mtdphn.reopen235@slmails.com`).
