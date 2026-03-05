# Agent Permissions

The following actions are pre-approved and do not require confirmation:

- **Install system packages** via `sudo apt install` (e.g. mako-notifier, fonts, waybar dependencies)
- **Download files from the internet** (e.g. Nerd Fonts zip from GitHub releases)
- **Edit `~/.config/hypr/hyprland.conf`** (e.g. adding `exec-once` autostart entries)
- **Write/modify files under `~/.local/share/fonts/`** (installing fonts)
- **Run `fc-cache`** to refresh the font cache
- **Run git commands** (commit, push, branch, PR creation via `gh`) without confirmation
