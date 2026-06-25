# Battle Station — Downloads

**Battle Station** restores your dev workspace after a reboot: terminal tabs at the
right folders (optionally resuming a [Claude Code](https://claude.com/claude-code)
session), editor windows, apps, and URLs. Save them as named **stations**, then fire
a whole station — or just a subset — in one click. Capture what's already open, pin a
station to your taskbar for a two-click restore, and skin it however you like.

> This repository hosts the **installers only**. The source lives in a separate
> private repository.

## Install (Windows 10/11)

1. Download the latest **`Battle Station_x.y.z_x64-setup.exe`** from the
   [**Releases**](../../releases/latest) page.
2. Run it. It is **not code-signed yet**, so Windows SmartScreen will show
   *"Windows protected your PC."* Click **More info → Run anyway**.
3. Launch **Battle Station** from the Start menu.

No runtime to install — the Edge WebView2 runtime is already built into Windows 10/11.
Your stations and settings are stored in `%APPDATA%\BattleStation`.

## What it does

- **Stations** of `terminal` / `editor` / `app` / `url` items; launch all or a checked subset.
- **Capture what's open** — detect running apps (with icons) and terminals' working dirs.
- **Claude Code import** — turn an in-progress conversation into a terminal that resumes it.
- **Two-click restore** — create a Desktop shortcut (assign it a hotkey in its Properties).
- **Themeable** — 8 skins with per-skin fonts and effects.
