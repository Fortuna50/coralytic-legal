# Coralytic — Legal & Support

Static site hosting for Coralytic's legal documents and support page.

Live URLs (after GitHub Pages is enabled):
- **Home**: https://burakozyer.github.io/coralytic-legal/
- **Privacy Policy**: https://burakozyer.github.io/coralytic-legal/privacy.html
- **Terms of Use**: https://burakozyer.github.io/coralytic-legal/terms.html
- **Support**: https://burakozyer.github.io/coralytic-legal/support.html

## Setup (one-time)

1. Push this repo to GitHub
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → Save
3. Wait ~1 minute for first deploy
4. URLs above become live

## Custom domain (optional, later)

When `coralytic.app` is registered:
1. Add CNAME record at domain registrar pointing to `burakozyer.github.io`
2. In repo Settings → Pages → Custom domain: `coralytic.app`
3. Update app's `PaywallFooter.swift` URLs from GitHub Pages to custom domain

## Editing

Plain HTML + CSS — edit any file directly, push, GitHub Pages redeploys automatically (~30s).
