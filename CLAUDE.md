# CLAUDE.md — surfn-breeze-arc

## Project overview

Standalone repo for the **Surfn-Breeze-Arc** icon theme, split out of the `erikdubois/surfn`
monolith. See [README.md](./README.md).

## Current state

Ships one theme: `usr/share/icons/Surfn-Breeze-Arc/`. Packaged as `surfn-breeze-arc-icons-git` (recipe in
`~/KIRO-PKG-BUILD-ICONS/surfn-breeze-arc/`), `depends=('surfn-icons-git')` — the base Surfn theme.

## Patterns & decisions

- Theme dir PascalCase; repo/package lowercase. `icon-theme.cache` gitignored (rebuilt by
  the pacman hook on install). Bash scripts follow the canonical Kiro template.
