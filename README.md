# UNDERWIRE

An independent tech & activism zine, by scrypt-kitty. Launching soon.

**Live (GitHub Pages):** https://scrypt-kitty.github.io/underwire/

Static, zero-JS, no trackers. Own design system in `styles.css` (no external fonts/CDNs).

## Campaigns

Independent, public-sourced field guides (Topics · Debunking · FAQ · Take Action):

- **Flock Off** — mass ALPR / Flock surveillance → `/underwire/campaigns/flock-off/`
- **Project Raspberry** — hyperscale data centers → `/underwire/campaigns/raspberry/`

Hub: `/underwire/campaigns/`. Copy is written from public sources only and is not
affiliated with, or derived from, any single organization's internal work.

## Environments

Published by `.github/workflows/pages.yml` (Pages source: GitHub Actions):

| Env         | Branch    | URL                                             |
|-------------|-----------|-------------------------------------------------|
| **prod**    | `main`    | https://scrypt-kitty.github.io/underwire/       |
| **preview** | `preview` | https://scrypt-kitty.github.io/underwire/preview/ |

Changes go on a `feat/*` branch → PR to `main`; point `preview` at a branch to show it live.
