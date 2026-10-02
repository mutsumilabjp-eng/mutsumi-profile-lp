# Mutsumi

Mutsumi profile / hub LP.

## Source of truth
- Canonical copy/design: Notion
- Production code: this repository
- Production hosting: Cloudflare Workers Static Assets
- Worker name: `mutsumi`
- Production branch: `main`

## Deploy
Push to `main` → Cloudflare Workers Builds (Git integration, build command: none, deploy command: `npx wrangler deploy`).

Account: Mutsumi.lab.jp (`b62fc18…`). URL: https://mutsumi.app1008.workers.dev/

Files listed in `.assetsignore` are not published.

Do not deploy this LP from another brand's repository or Cloudflare account.
