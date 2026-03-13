
<div align="center">

```
████████╗███████╗██████╗ ███╗   ███╗██╗   ██╗██╗  ██╗
╚══██╔══╝██╔════╝██╔══██╗████╗ ████║██║   ██║╚██╗██╔╝
   ██║   █████╗  ██████╔╝██╔████╔██║██║   ██║ ╚███╔╝ 
   ██║   ██╔══╝  ██╔══██╗██║╚██╔╝██║██║   ██║ ██╔██╗ 
   ██║   ███████╗██║  ██║██║ ╚═╝ ██║╚██████╔╝██╔╝ ██╗
   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═╝
██████╗ ███████╗███████╗██╗  ██╗████████╗ ██████╗ ██████╗ 
██╔══██╗██╔════╝██╔════╝██║ ██╔╝╚══██╔══╝██╔═══██╗██╔══██╗
██║  ██║█████╗  ███████╗█████╔╝    ██║   ██║   ██║██████╔╝
██║  ██║██╔══╝  ╚════██║██╔═██╗    ██║   ██║   ██║██╔═══╝ 
██████╔╝███████╗███████║██║  ██╗   ██║   ╚██████╔╝██║     
╚═════╝ ╚══════╝╚══════╝╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝     
```

**A full desktop environment installer & setup tool for Termux**  
*X11 · XFCE · proot-distro · Sound · Themes · One script to rule them all*

---

![License](https://img.shields.io/badge/license-MIT-blueviolet?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Termux%20%7C%20Android-ff69b4?style=flat-square)
![Arch](https://img.shields.io/badge/arch-AArch64-purple?style=flat-square)
![Shell](https://img.shields.io/badge/shell-zsh%20%2B%20nerd%20fonts-hotpink?style=flat-square)
![Stars](https://img.shields.io/github/stars/mairecheco/termux-desktop?style=flat-square&color=blueviolet)

</div>

---

## ✨ What is this?

**termux-desktop** is an interactive, all-in-one setup script that transforms your bare Termux installation into a fully configured desktop environment — no manual config, no wiki diving, no pain.

Just run `install.sh`, answer a few questions, and you're done.

---

## 🎨 Available Styles

| Style | Preview |
|-------|---------|
| **macOS (Ventura)** | ![macos](styles/macos/ventura-xfce.png) |
| **Windows 10** | ![win10](styles/windows10/screenshot.png) |
| **Windows 95** | *(retro vibes)* |
| **Windows XP** | *(bliss wallpaper included)* |

---

## 🚀 Features

- **Interactive installer** — guided setup with prompts for username, style, and software
- **X11 support** — full graphical session via `startx11` and `stopx11`
- **XFCE desktop** — lightweight, fast, beautiful
- **proot-distro** — full Linux distro container (Debian/Ubuntu)
- **Sound support** — PulseAudio configured out of the box
- **Zsh shell** — nerd fonts, dynamic system info on login, purple/pink theme
- **Browser choice** — Firefox, Chromium, or Falkon
- **App selection** — office, editors, media, and more
- **Custom home layout** — `~/Desktop`, `~/Documents`, `~/Downloads`, `~/Pictures`, etc.
- **Styles fetched from GitHub** — always up to date

---

## ⚡ Quick Install

```bash
curl -fsSL https://raw.githubusercontent.com/mairecheco/termux-desktop/main/install.sh | bash
```

Or clone and run manually:

```bash
git clone https://github.com/mairecheco/termux-desktop
cd termux-desktop
bash install.sh
```

---

## 🖥️ Usage

| Command | Description |
|---------|-------------|
| `startx11` | Start the XFCE desktop session |
| `stopx11` | Stop the X11 session |

---

## 📦 Style Packs

Styles are published as GitHub Releases. The installer fetches and applies them automatically based on your choice.

You can also grab them manually from the [Releases](https://github.com/mairecheco/termux-desktop/releases) page:

| Release Tag | Contents |
|-------------|----------|
| `style-macos` | macOS Ventura theme, cursors, dock, GTK, wallpapers |
| `style-windows10` | Windows 10 icons, themes, wallpaper |
| `style-windows95` | Windows 95 retro pack |
| `style-windowsxp` | Windows XP full pack (fonts, cursors, sounds, icons) |

---

## 🗂️ Repository Structure

```
termux-desktop/
├── install.sh              # main installer
├── lib/
│   ├── x11.sh              # X11 / startx11 / stopx11 setup
│   ├── sound.sh            # PulseAudio setup
│   ├── proot.sh            # proot-distro container setup
│   ├── shell.sh            # zsh + nerd fonts + prompt
│   ├── apps.sh             # software installation
│   └── styles.sh           # theme/style fetcher & applier
├── styles/
│   ├── macos/
│   ├── windows10/
│   ├── windows95/
│   └── windowsxp/
└── assets/
    └── screenshots/
```

---

## 🤝 Credits

Made with 💜 by **[mairecheco](https://github.com/mairecheco)**

| Platform | Link |
|----------|------|
| 🐙 GitHub | [@mairecheco](https://github.com/mairecheco) |
| 📸 Instagram | [@maireche.exe](https://instagram.com/maireche.exe) |
| ▶️ YouTube | [@M17DOS](https://youtube.com/@M17DOS) |
| 🎵 TikTok | [@abdou_mhf7](https://tiktok.com/@abdou_mhf7) |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

*Built from Algeria 🇩🇿 — for everyone.*

</div>