# CLAUDE.md — about-me

Long-form "about" page (stack, links, context). The GitHub profile README lives
at `subkoks/subkoks`; this repo is documentation only — no application code.

## Conventions
- Markdown-first. Keep links valid and current; prefer relative links within the repo.
- Don't duplicate the profile README here; cross-link to `subkoks/subkoks` instead.
- One logical change per commit; `type(scope): description`; feature branches only.

## CI
`@claude` mentions invoke the agent; every PR gets an automatic Claude review
(checks for broken/invalid URLs). Same-repo PRs auto-merge once checks pass.
