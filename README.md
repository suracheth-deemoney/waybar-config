# Waybar Config

A Waybar configuration for Hyprland with a light theme based on Catppuccin accents.

## Dependencies

Install required system packages:

```bash
sudo apt install -y waybar mako-notifier
```

## Fonts

This config uses **JetBrainsMono Nerd Font** for icon glyphs. Install it manually:

```bash
mkdir -p ~/.local/share/fonts/JetBrainsMono
cd ~/.local/share/fonts/JetBrainsMono
curl -fLo JetBrainsMono.zip \
  "https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip"
unzip JetBrainsMono.zip
rm JetBrainsMono.zip
fc-cache -fv
```

**Noto Sans** (fallback font) is available via:

```bash
sudo apt install -y fonts-noto-core
```

## Modules

| Module | Description |
|---|---|
| `hyprland/workspaces` | Workspace switcher |
| `hyprland/window` | Active window title |
| `cpu` / `memory` | System resource usage |
| `network` | WiFi/Ethernet status |
| `group/volume` | Volume control via WirePlumber (`wpctl`) |
| `hyprland/language` | Input language switcher |
| `custom/notification` | Notification count via mako |
| `tray` | System tray |
| `battery` | Battery status with charging states |
| `clock` | Date and time |
