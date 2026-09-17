# Adrian Grițcan Portfolio

Static portfolio deployed to the existing Cloudflare Worker:

https://adriangritcan.techpage.workers.dev/

## Cloudflare build settings

- Worker name: `adriangritcan`
- Production branch: `main`
- Build command: leave empty
- Deploy command: `npx wrangler deploy`

The `wrangler.jsonc` name intentionally matches the existing Cloudflare Worker.
