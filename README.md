# SecondDock releases

Signed update archives and Sparkle appcast feeds for [SecondDock](https://github.com/jazongb/second-dock)
(private source repo). This repo exists only because SecondDock's source repo is private and
Sparkle needs plain, unauthenticated HTTPS URLs for its appcast + downloads.

- `appcast-stable.xml` — what colleagues update from.
- `appcast-pilot.xml` — Jaron's own builds, ahead of stable.
- Release archives attach to tagged GitHub Releases in this repo.

Published by `scripts/release.sh` in the source repo. Nothing here is hand-edited.
