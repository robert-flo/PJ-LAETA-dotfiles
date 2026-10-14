# PJ-LAETA-dotfiles

Public snapshot of **laeta**’s Omarchy `$HOME` right after account creation (no nixfredOS restore, no personal dotbare).

## Layout

- `home/` — mirror of `/home/laeta` at capture time (configs from `/etc/skel` + Omarchy defaults).
- `SNAPSHOT-*.txt` — inventory and machine metadata.

Excluded from the mirror: `.cache/`, `.local/share/nvim/` (Lazy.nvim download tree), future `.cfg/` (dotbare).

## Capture

- **UTC:** see `SNAPSHOT-machine.txt`
- **User:** `laeta` (uid 1004), same sudo/wheel pattern as `gracie`
- **Host:** Omarchy on `her`

## Restore (manual)

Not a turnkey installer. Copy paths from `home/` into a new user’s `$HOME` or diff against your own skel.
