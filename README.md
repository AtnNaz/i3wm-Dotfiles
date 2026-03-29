# 🌌 Blue i3wm Dotfiles

A minimalist, high-performance i3wm configuration featuring a deep black, navy blue, and neon blue color palette. Optimized for developers and power users on Arch Linux.

![i3wm-display](https://img.shields.io/badge/WM-i3wm-blue)
![OS-Arch](https://img.shields.io/badge/OS-Arch_Linux-blue?logo=arch-linux)
![Shell-Bash](https://img.shields.io/badge/Shell-Bash-lightgrey)

## 🎨 Aesthetic Theme
- **Color Palette:** Deep Black `#0A0E17`, Navy Blue `#111926`, Electric Blue `#0088CC`, and White `#FFFFFF`.
- **Bar:** Custom Polybar with system monitoring modules.
- **Terminal:** Alacritty with JetBrains Mono Nerd Font.
- **GTK Theme:** Arc-Dark (Modified for seamless integration).

## ⌨️ Keybindings (Super = Windows Key)

| Key | Action |
| :--- | :--- |
| `Mod + Enter` | Open Terminal (Alacritty) |
| `Mod + d` | Application Launcher (Rofi) |
| `Mod + e` | File Manager (Thunar) |
| `Mod + b` | Web Browser (Firefox) |
| `Mod + q` | Close Application |
| `Mod + Shift + q` | Kill Application (Force) |
| `Mod + l` | Lock Screen |
| `Mod + Arrow Keys` | Change Focus |
| `Mod + Shift + Arrows`| Resize Windows |
| `Mod + Ctrl + Arrows` | Move Windows |
| `PrtSc` | Full Screenshot to Clipboard |
| `Mod + PrtSc` | Area Screenshot to Clipboard |
| `Mod + [0-9]` | Switch Workspaces |

## 🛠️ Installation (Arch Linux)

1. **Install Dependencies:**
   ```bash
   sudo pacman -S i3-wm polybar rofi thunar alacritty maim xclip i3lock xdotool ttf-jetbrains-mono-nerd papirus-icon-theme playerctl
