# Maintaining this profile README

A short checklist to keep `https://github.com/procatesoft` looking sharp.
GitHub renders `README.md` from this repository because the repository name
matches the account name.

## When to update

- New service or product launched → add it to **What I build** / **Selected work**
- Pricing changes on procatesoft.com → update the **Work with me** table
- New public project worth showing → add it and pin the repository

## Checklist before pushing

1. Every image URL returns `200` (dead image hosts are the #1 cause of a broken
   profile — Heroku-hosted badge services no longer resolve).
2. No placeholder links (`your-handle`, `your-website.com`).
3. Render check: open the profile page and confirm all images load, for both
   logged-out visitors and light/dark theme.
4. Links to `procatesoft.com`, `erp.procatesoft.com` and email still valid.

## Known-good services

| Purpose | Service | Status |
| --- | --- | --- |
| Header/footer waves | `capsule-render.vercel.app` | ok (use a solid `color=`, not hex lists) |
| Typing headline | `readme-typing-svg.demolab.com` | ok (the old `herokuapp` host is dead) |
| Tech icons | `skillicons.dev` | ok (no `odoo` icon — unsupported) |
| Contribution cards | `github-profile-summary-cards.vercel.app` | ok |
| Streak | `streak-stats.demolab.com` | ok |
| GitHub stats | `github-readme-stats.vercel.app` | avoid — frequently returns 503 |
