<div align="center">

# 🏴 FOUNDER OS

**A minimal, hand-built Arch Linux spin, powered by Hyprland.**

*A personal learning project — not a finished distro.*

![Arch Based](https://img.shields.io/badge/base-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Hyprland](https://img.shields.io/badge/WM-Hyprland-58E1FF?style=for-the-badge&logo=wayland&logoColor=white)
![Status](https://img.shields.io/badge/status-VM%20tested%20only-orange?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

</div>

---

## 📖 About

**Founder OS** is a custom Arch Linux ISO built from the ground up with [`archiso`](https://wiki.archlinux.org/title/Archiso), running **Hyprland** as its window manager. It was built as a personal project to learn how Arch-based ISOs are actually put together — bootstrap, package selection, boot modes, the works.

It is **not** trying to be the next Kali, Arch, Debian, or anything close. It's a bare-minimum environment with a small set of tools out of the box. If you're looking for a polished, batteries-included OS, this isn't it — and that's on purpose.

> ⚠️ **This is a learning project, not a finished product.** Expect rough edges. Expect missing stuff. That's the point.

---

## ✨ Features

- 🧱 Built on vanilla Arch Linux architecture — nothing exotic under the hood
- 🌊 [Hyprland](https://hyprland.org/) as the default window manager
- ⚡ Minimal footprint — only a handful of tools included by default
- 🛠️ Fully open source, fully inspectable build scripts

---

## ⌨️ Default Keybinds

| Keybind | Action |
|---|---|
| `Super + Q` | Open terminal |

*(More keybinds coming as the project grows — check the Hyprland config for the full list.)*

---

## 🔑 Default Credentials

```
Username: founder
Password: founder
```

> 🔐 **Change this immediately** if you install anything persistent. This is a live/demo credential, not meant for anything you care about staying secure.

---

## 💿 Getting Founder OS

Grab the latest ISO from the [Releases](../../releases) page.

### Running in a VM (recommended, and the only tested method)

Founder OS has **only been tested in a virtual machine.** It has **not** been tested by flashing to a USB drive — try that at your own risk, and feel free to open an issue if you do and it works (or doesn't).

If you're running it in VirtualBox, VMware, or any other VM software:

> ⚠️ **Enable 3D acceleration** in your VM settings before booting. Hyprland relies on it, and without it you'll likely run into rendering issues or a broken session.

**VirtualBox:** `Settings → Display → Screen → Enable 3D Acceleration`

---

## 🚧 What This Is (and Isn't)

| ✅ It is | ❌ It isn't |
|---|---|
| A learning project | A finished, polished OS |
| A minimal Arch + Hyprland base | A Kali/Parrot alternative |
| Fully open source | Feature-complete |
| VM tested | USB/bare-metal tested |

---

## 🤝 Contributing

This started as a solo learning project, but issues, suggestions, and PRs are welcome — especially if you catch something broken or have ideas for what a "minimum viable OS" should include.

---

## 📜 License

Open source — see [`LICENSE`](./LICENSE) for details.

---

<div align="center">

*Built by [Founder Linux](https://github.com/FTFoundersTeam) as a way to actually learn how an OS gets put together.*

</div>
