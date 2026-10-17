# AGENTS.md

Instructions for coding agents that work in this repository.

## Project

The `.github` repository of the `opensource-finance` GitHub organization.
GitHub renders `profile/README.md` on https://github.com/opensource-finance. Nothing else here is published.

| Path | Contents |
|---|---|
| `profile/README.md` | The organization profile page. |
| `profile/assets/` | `logo.png` and `og-image.png`. The README loads the logo from https://opensource.finance/logo.png, not from here. |

## Rules

- There is no build, test, or CI. Check a change by previewing the Markdown on GitHub.
- GitHub sanitizes profile HTML: inline `style` attributes and scripts are dropped. Use `align`, `<picture>`, and `<img width>` only.
- Keep claims in step with the Osprey repo and https://opensource.finance (license, rule counts, latency numbers). Check the source before you change a number.
- Badge and link targets must resolve. Check each URL you add.

## Commits and pull requests

- Use Conventional Commits: `feat:`, `fix:`, `docs:`, `chore:`.
- Do not mention AI tools or assistants in commit messages, PR titles, or PR descriptions. No `Co-Authored-By` trailers.
