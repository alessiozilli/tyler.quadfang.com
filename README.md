# Tyler's Command Centre — tyler.quadfang.com

**Built:** 2026-05-04 by forge-cowork Sonnet 4.6
**Mission:** Public command centre for Tyler.
**Target domain:** `tyler.quadfang.com`
**Repo:** `alessiozilli/tyler.quadfang.com` (GitHub Pages, public)

## Source of truth

`index.html` lives at:
- **Cowork session (built):** `C:\Users\user\AppData\Roaming\Claude\local-agent-mode-sessions\320b10dd-9494-47d8-8207-b09ebb4aad10\fb3fb3ae-2608-43a6-9145-f05db07ce093\local_ddae5713-33ed-450d-8db3-5b89d60fd555\outputs\index.html`
- forge-code on beast: copied from session path above into this folder before pushing — that's the canonical source after session ends.

## Deployment plan

1. **forge-code on beast** — `gh repo create alessiozilli/tyler.quadfang.com --public --source=. --push`, with `index.html` + `CNAME` (containing `tyler.quadfang.com`), enable GH Pages on `main` branch root.
2. **Alessio (manual)** — DNS for `quadfang.com` lives at **Google Domains / Squarespace**, NOT Wix. Add CNAME record: `tyler` → `alessiozilli.github.io`.
3. **Verify** — `https://tyler.quadfang.com` resolves and serves the page within 24h. HTTPS auto-issues via GH Pages Let's Encrypt once domain verified.

## Bus dispatch

Mission sent to forge-code on beast via agent_messages. Awaiting Pages green confirmation, then Alessio adds DNS at Squarespace panel.
