# Snapshot — laeta HOME

Captured as user **laeta** after `useradd` (wheel + `04_laeta` sudoers). No `restore.sh`, no `sura-home` pull.

## Top-level (`/home/laeta`)

| Path | Role |
|------|------|
| `.bashrc` / `.bash_profile` / `.bash_logout` | Omarchy bash entry |
| `.config/` | Hyprland (Lua), terminals, git, omarchy shell.json, LazyVim tree under `nvim/` (config only) |
| `.local/share/` | Small app data (nvim plugins **excluded** from this repo) |
| `.cache/` | Empty at capture — **not** in repo |

## Stats

See `SNAPSHOT-stats.txt` and `SNAPSHOT-dirs.txt`.

## Notes

- Linux account `sura` (uid 1002) is unrelated to the AI assistant name.
- For a full Robert stack on another user, use playbook `assets/restore.sh` + `rebuild.sh`, not this repo alone.
