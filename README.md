# Yujin Life Gmail — public information

An independent, buildless documentation site for a personal-use, read-only Gmail assistant.

- `index.html`: application overview and the read-only permission boundary.
- `privacy.html`: data access, purpose, configured AI processing, local retention and control.
- `terms.html`: personal-use scope and limitations.
- `styles.css` / `favicon.svg`: original static presentation assets.
- `.nojekyll`: publish the static files without a Jekyll build.

This repository contains **only public informational pages**. It is not the private
Yujin application, has no Gmail connection or login flow, and contains no email data,
credentials, private configuration, or application backend source.

## GitHub Pages

Use the repository's **Settings → Pages → Deploy from a branch → main → /(root)**.
The expected project URL is `https://jeremyzhangsyd.github.io/yujin-life-info/`.
Publication must be verified before those URLs are used in OAuth branding.

No packages, build tool, server-side runtime, external fonts, analytics, scripts,
forms or tracking are required. All page and asset links are relative so a custom
domain can be attached later. No `CNAME` is set until the owner supplies and verifies
the intended domain.

## OAuth readiness is separate

Publishing these pages does not switch Google's OAuth application to Production,
verify an app/domain, change permissions, or renew a Gmail grant. Those steps require
their own configuration and owner approval. The informational site does not expose
the private office UI.

## Contact

Use this repository's issues for general questions. Never post email contents,
tokens, passwords or other private material.
