# CLAUDE.md — about-me

Long-form **about** page for [@subkoks](https://github.com/subkoks) — stack,
links, and context that doesn't belong on the front page. Published as
[`subkoks/about-me`](https://github.com/subkoks/about-me).

**Documentation only — no application code.** The front-page profile README
lives at `subkoks/subkoks` (drafted in the `GitHub-Profile` workspace). Don't
duplicate it here; cross-link instead.

## Layout

- `README.md` — the about page itself (badges, coding-activity graph, links).
- `scripts/cloud-setup.sh` — Claude Code cloud bootstrap (no-op; no deps to install).
- `.github/workflows/` — CI: Claude review + link validation.
- `.cursor/BUGBOT.md` — Cursor review config.

## Conventions

- Markdown-first. Keep every link and image URL valid and current; prefer
  relative links within the repo.
- Shields/badges use `style=flat-square`; keep the set in sync with the profile
  README's stack section without copying its prose.
- One logical change per commit; `type(scope): description`; feature branches only.

## CI

`@claude` mentions invoke the agent; every PR gets an automatic Claude review
that checks for broken/invalid URLs. Same-repo PRs auto-merge once checks pass.

## Related

- `subkoks/subkoks` — live profile README (publish target).
- `GitHub-Profile` — redesign workspace that drafts the profile README.
