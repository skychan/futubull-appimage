# Futubull (富途牛牛)  AppImage for Linux (AUR)

This repository provides an Arch Linux PKGBUILD for installing **Futubull** as an **AppImage**.  
Futubull is a professional trading platform supporting HK stocks, US stocks, A-shares via Connect, options, ETFs, and more — covering major global markets.

---

## 📦 Package Info

- **Package name**: `futubull-appimage`
- **Version**: 15.13.11208
- **Architecture**: `x86_64`
- **Format**: [AppImage](https://appimage.org/)
- **Source**: [Download](https://softwaredownload.futunn.com/FTNN_desktop_15.13.11208_amd64.AppImage)
---

## 🧰 Features

- Cross-platform Futu Niuniu trading terminal
- Supports:
  - 🇭🇰 HK Stocks
  - 🇺🇸 US Stocks
  - 🇨🇳 China A-shares (via Connect)
  - Options, ETFs, and more
- Self-contained AppImage – no complex dependency tree
- Desktop integration (`.desktop` file + icon included)

---

## 🔧 Installation (via AUR)

Using [yay](https://github.com/Jguer/yay):

```bash
yay -S futubull-appimage
```

Or manually:

```bash
git clone https://aur.archlinux.org/futubull-appimage.git
cd futubull-appimage
makepkg -si
```

## 🖥️ Usage

After installation, launch it via:

```bash
futubull
```

Or find "FTNN" in your application launcher.

## 💡 Notes

The AppImage will be installed to `/opt/appimages/Futubull`.

Desktop file and icon are installed for launcher integration.

The installer disables AppImageLauncher integration prompt by default.

## 📝 License

This PKGBUILD is MIT licensed.

Futubull is proprietary software — see [Futu’s terms of use](https://www.futunn.com/about/disclaimer). (http://futunn.com)

