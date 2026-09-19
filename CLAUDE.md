# VTA — Виткова Татьяна

Single-page site for a private psychology practice (Виткова Татьяна — psychologist/gestalt therapist, 30+ years practice). Repo: `followorbounce/vta`. Target audience is Russian-speaking clients.

## Structure

- `index.html` — the entire site (hero, dark theme, single page, no separate CSS/JS files currently)

## Conventions

- **Content is intentionally in Russian** — this is a real exception to the usual "no Russian" rule, since the client and audience are Russian-speaking. Keep all client-facing copy in Russian; only use another language if the client's content does.
- Dark theme — recent commit already refactored dark theme colors for consistency; match existing palette/tokens rather than introducing new ones.
- No build step — this is a plain static HTML file, edit directly.

## Analytics
Cloudflare Web Analytics beacon added 2026-09-19, shares the `followorbounce.github.io` Web Analytics site (see `[[cloudflare-analytics-setup]]` in memory).
