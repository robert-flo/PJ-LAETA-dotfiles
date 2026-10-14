# PJ-LAETA-dotfiles

Public snapshot of **laeta**’s Omarchy `$HOME` right after account creation (no nixfredOS restore, no personal dotbare).

## Layout

**Dotbare:** bare repo lives in `~/.cfg` on user `laeta`; work tree is `$HOME`. Remote = this repository (`master`).

- Dotfiles at repo root (`.bashrc`, `.config/`, …) — same paths as on disk.
- `SNAPSHOT-*.txt` — inventory from first capture (historical).

Excluded via `.gitignore`: `.cache/`, `.local/share/nvim/`, `.cfg/`, and playbook session noise (see file).

## Capture

- **UTC:** see `SNAPSHOT-machine.txt`
- **User:** `laeta` (uid 1004), same sudo/wheel pattern as `gracie`
- **Host:** Omarchy on `her`

## Restore (manual)

Not a turnkey installer. Copy paths from `home/` into a new user’s `$HOME` or diff against your own skel.
