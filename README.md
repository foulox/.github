# .github

Account-wide default community health files for github.com/foulox. GitHub automatically applies these to every repo owned by this account that doesn't define its own override — no copying, no per-repo maintenance.

- `.github/PULL_REQUEST_TEMPLATE.md` — the standard PR format (Summary + Test plan, split into Claude-automated vs. Lou-manual verification). Edit here to change it everywhere at once.

This repo must stay **public** — GitHub does not support private `.github` repos for this feature. It contains no project content, only process templates.

Repos with their own local `.github/PULL_REQUEST_TEMPLATE.md` (e.g. `tigerwolves`) use their own copy instead — a local file always takes precedence over this default.
