# 🧩 i3wm Setup (CachyOS)

A minimal and clean **i3 window manager setup** tailored for CachyOS.
This configuration focuses on simplicity, performance, and a modern workflow using Polybar, Picom, and GTK theming.

---

## 🚀 Getting Started

### 1. Update your system

Before installing anything, make sure your system is up to date:

```bash
sudo pacman -Sy
```

---

### 2. Install required packages

Run the following command to install all dependencies needed for this configuration:

```bash
sudo pacman -S \
xclip \
gnome-themes-extra \
adw-gtk-theme \
nwg-look \
ffmpegthumbnailer \
gst-libav \
blueman \
tumbler \
pipewire \
pipewire-alsa \
pipewire-pulse \
wireplumber \
nemo \
mpv \
os-prober \
nvim \
kitty \
nautilus \
brightnessctl \
picom
```

---

## 🖥️ Features

* ⚡ Lightweight **i3** window manager setup
* 🎨 GTK theming with Adwaita Dark
* 🧰 Customizable Polybar configuration
* 🎬 Video thumbnails support in file managers
* 🔊 PipeWire audio setup
* 🖱️ Clean workflow with minimal clutter

---

## ⚙️ Notes

* This setup is designed for **CachyOS (Arch-based systems)**
* Make sure you have a working i3 environment before applying configs
* Some features may require additional fonts (e.g., Nerd Fonts)

---

## 📂 Installation

Clone the repository:

```bash
git clone <your-repo-url>
cd <your-repo-name>
```

Copy the configuration files:

```bash
cp -r .config/* ~/.config/
```

---

## 🔁 Reload i3

After copying configs, reload i3:

```bash
Mod + Shift + r
```

---

## ⚠️ Disclaimer

This configuration may overwrite your existing configs.
It is recommended to back up your current setup before applying.

---

## 📸 Preview

*Add screenshots here*

---

## 🧠 Credits

* i3 community
* Arch Linux ecosystem
* Various dotfiles inspirations

---

## 📜 License

MIT License (or your preferred license)
