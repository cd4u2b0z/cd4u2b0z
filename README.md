# Cdubz

**`Arch Linux Craftsman`**

I build my desktop from raw config files — not installers, not templates. Arch Linux + Hyprland + a four-repo provisioning stack that rebuilds everything from scratch in 30 minutes. Every color is dynamic, every panel is hand-rolled, every widget replaces a janky GTK dialog with something that belongs on the desktop.

<p align="left">
   <a href="https://github.com/cd4u2b0z?tab=followers">
      <img alt="followers" title="Follow me on GitHub" src="https://custom-icon-badges.demolab.com/github/followers/cd4u2b0z?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/>
   </a>
   <a href="https://github.com/cd4u2b0z?tab=repositories&sort=stargazers">
      <img alt="total stars" title="Total stars on GitHub" src="https://custom-icon-badges.demolab.com/github/stars/cd4u2b0z?color=55960c&style=for-the-badge&labelColor=488207&logo=star"/>
   </a>
</p>

---

### The Stack

```
DCLi ─── orchestration (Rust CLI)
 └── Ansible ─── system state (packages, services, full rebuild)
      └── Chezmoi ─── user state (dotfiles, themes, keybinds)
           └── Quickshell ─── UI state (QML bar, floating panels)
                └── Hyprland ─── compositor (Wayland, GPU-accelerated)
```

### What I Build

| Project | What It Is |
|---------|-----------|
| [**quickshell-bar**](https://github.com/cd4u2b0z/quickshell-bar) | GPU-accelerated status bar — QML/QtQuick, native PipeWire + Bluetooth, wallust-themed floating panels |
| [**dcli**](https://github.com/cd4u2b0z/dcli) | System orchestrator — one command to provision, sync, and push everything |
| [**dotfiles**](https://github.com/cd4u2b0z/dotfiles) | Hyprland + 22 configs — dynamic Everforest theming, Chezmoi-managed |
| [**ansible-system**](https://github.com/cd4u2b0z/ansible-system) | Full Arch rebuild in ~30 minutes — 190 packages, services, dotfile bootstrap |

#

### Languages and Tools

![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/bash-%234EAA25.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)
![Qt](https://img.shields.io/badge/QML-%2341CD52.svg?style=for-the-badge&logo=qt&logoColor=white)
![Ansible](https://img.shields.io/badge/ansible-%23EE0000.svg?style=for-the-badge&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/arch_linux-%231793D1.svg?style=for-the-badge&logo=arch-linux&logoColor=white)
![Wayland](https://img.shields.io/badge/hyprland-%2358E1FF.svg?style=for-the-badge&logo=wayland&logoColor=black)
![Neovim](https://img.shields.io/badge/neovim-%2357A143.svg?style=for-the-badge&logo=neovim&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

#

<div align="center">

*If it's worth doing, it's worth understanding.*

</div>
