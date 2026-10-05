# LinkedFiles

Find which Blender files use an image.

Pick a texture and a folder. LinkedFiles looks through every `.blend` file in
that folder and its subfolders and shows which ones use the texture, and
exactly where: object, material (or world, compositor, Geometry Nodes,
modifier…) and node. It also lists referenced images whose files are missing.

This repository hosts the **downloads only**.

## Download

1. Open the [latest release](https://github.com/Rainfall831/LinkedFiles-releases/releases/latest).
2. Download the file ending in **`_x64-setup.exe`** and run it.

It installs for your Windows user only (no administrator rights needed) and
adds a Start menu shortcut. LinkedFiles checks for updates when it starts and
asks before installing one.

> **"Windows protected your PC"?** From version 0.1.1 the installer is
> code-signed by **Syed Fahib**. Microsoft SmartScreen still warns about new
> downloads until enough people have installed them. Check that the publisher
> says Syed Fahib, then click **More info → Run anyway**. Only do this for
> installers downloaded from this page.

To uninstall: **Settings → Apps → Installed apps → LinkedFiles → Uninstall**.

## Requirements

- Windows 10 or 11 (64-bit)
- [Blender](https://www.blender.org/download/) installed. LinkedFiles uses it in
  the background to read `.blend` files. It finds standard installs
  automatically; otherwise choose `blender.exe` from the Blender button.

## Privacy

Your project files stay on your computer. LinkedFiles has no accounts,
analytics or telemetry and never uploads files, file names, paths or search
results. It goes online only to check this page for updates (GitHub sees your
IP address, as with any website) and when you click **Download Blender**.

It stores, only on your computer: the Blender path and recent folders
(`%APPDATA%\com.linkedfiles.app`), a search cache and a log
(`%LOCALAPPDATA%\com.linkedfiles.app`). You can delete them at any time.

## Feedback and support

Use the **Feedback** button in the app, or email founder@apturra.com.

## License

Free to use. © 2026 Syed Fahib. All rights reserved. See [LICENSE.md](LICENSE.md).
