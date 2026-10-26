# stardust.red

Static website for the domain `stardust.red`, hosted on GitHub Pages (custom domain via `CNAME`).

Main job: public home page, privacy policy and terms of service for **stardust-mail**, the owner's
read-only Gmail desktop app, as required by Google's OAuth consent-screen branding.

- `/stardust-mail/` home, `/stardust-mail/privacy/` privacy policy, `/stardust-mail/terms/` terms.

## Rules
- Plain HTML + one shared `style.css`. No build tools, npm, frameworks, trackers or third-party scripts/fonts.
- Dark-mode friendly (`prefers-color-scheme`), semantic and accessible HTML.
- Policy text must stay truthful to how stardust-mail actually works (gmail.readonly + openid/email; mail cached
  locally, AEAD-encrypted with DPAPI-protected keys; no servers/analytics/sharing; sign-out revokes and
  deletes the cache). If the app changes, update the policy and its "Last updated" date.
- Do not push, change repo settings or DNS without the owner's explicit OK.
- Git identity: `ziggy <ziggy@stardust.red>` (repo-local).
