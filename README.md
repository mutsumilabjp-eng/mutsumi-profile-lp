# Mutsumi

Mutsumi profile / hub LP.

## Source of truth
- Canonical copy/design: Notion
- Production code: this repository
- Production hosting: Cloudflare Workers Static Assets
- Worker name: `mutsumi`
- Production branch: `main`

## Deploy
Push to `main` → GitHub Actions → Wrangler → Cloudflare Workers.

Required GitHub Actions secrets:
- `CLOUDFLARE_API_TOKEN`
- `CLOUDFLARE_ACCOUNT_ID`

Do not deploy this LP from another brand's repository or Cloudflare account.
