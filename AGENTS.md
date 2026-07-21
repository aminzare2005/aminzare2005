# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README** repo (`aminzare2005/aminzare2005`). Its only tracked file is `README.md`, which GitHub renders on the user's profile page.

- There is **no application code, package manager, build system, test suite, or linter**. There is nothing to install, so the update script is intentionally a no-op.
- `README.md` is HTML/markdown that embeds two external image services: `skillicons.dev` (skill icons) and `github-readme-activity-graph.vercel.app` (activity graph). These render only over the network; there is no local backend.
- To preview changes as they'd appear on a GitHub profile, wrap `README.md` in a minimal HTML page and serve it locally, e.g. `python3 -m http.server` from a directory containing an `index.html` that includes the README's HTML. Do not commit preview scaffolding into the repo.
- The "product" is verified by confirming the README renders and the embedded external images load (both return HTTP 200 when reachable).
