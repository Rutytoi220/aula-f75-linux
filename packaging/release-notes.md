Prebuilt F75 Studio for x86_64 Linux. No build tools needed.

Built on Ubuntu 22.04 (glibc 2.35), so it runs on Linux Mint 21 and 22, LMDE 6, Ubuntu 22.04 and newer, Debian 12 and newer, and similar distros.

**AppImage (easiest)**

```bash
chmod +x F75_Studio-*-x86_64.AppImage
./F75_Studio-*-x86_64.AppImage
```

On first start, use the keyboard access button in the app to install the udev rule (one password prompt). If the AppImage does not start, run it with `--appimage-extract-and-run`.

**Tarball**

Extract it and run `./f75-studio`. The folder also has the desktop entry, icon and udev rule.

Check downloads against `SHA256SUMS`. To build from source instead, see the README.
