<div align="center">

# 🌸 MiniYuri — RO Survivors

**Yuri-RO · v1.0.0**

A free, unofficial browser-side tool for **RO Survivors**, featuring a simple God Mode toggle and a compact Yuri-themed interface.

[Join our Discord](https://discord.gg/DvP8UxQP3J) · [Download releases](../../releases)

</div>

## ✨ Features

- **God Mode toggle** — attempts to prevent normal in-game damage through a client-side modification.
- **Yuri-themed menu** with the Yuri mascot.
- **Draggable and minimizable interface**.
- **Alt + G** shortcut to toggle God Mode.
- **Status indicator** showing whether the local game flag is active.
- **Settings persistence** (optional).
- **Discord button** for community updates and support.

> **Note:** This is a client-side modification, not a guarantee of invulnerability. Some death conditions, game updates, or server-side checks may still affect a run.

## 📦 Download

Get the latest packaged builds from the [GitHub Releases page](../../releases).

| Version | Format | Best for |
| --- | --- | --- |
| Chrome / Edge extension | `.zip` | Recommended for everyday use |
| Tampermonkey userscript | `.user.js` | Users who prefer a userscript manager |

**Current release:** `1.0.0`

## 🧩 Installation

### Chrome / Edge extension

1. Download the extension ZIP from [Releases](../../releases).
2. Extract the ZIP to a folder you plan to keep.
3. Open `chrome://extensions` (or `edge://extensions`).
4. Turn on **Developer mode**.
5. Click **Load unpacked** and select the folder containing `manifest.json`.
6. Open or refresh [RO Survivors](https://ro-survivors.com/).

**Important:** Remove or disable older Yuri-RO builds first. Do not run the extension and userscript together.

### Tampermonkey

1. Install the Tampermonkey browser extension.
2. Download the `.user.js` file from [Releases](../../releases).
3. Open the file in Tampermonkey and confirm installation.
4. Open or refresh [RO Survivors](https://ro-survivors.com/).

## 🎮 Usage

- Open the game and start a run.
- Use the on-screen **God Mode** toggle or press **Alt + G**.
- Check the menu status. **ACTIVE** indicates the tool sees the local God Mode flag enabled; it does **not** guarantee server acceptance.
- You can drag or minimize the panel to keep it out of the way.

## 🔄 Updates

New versions will be posted under [GitHub Releases](../../releases) and announced on [Discord](https://discord.gg/DvP8UxQP3J).

**Automatic updating is not configured in v1.0.0.** Unpacked browser extensions must be updated manually. The userscript also requires separately configured update metadata before Tampermonkey can update it automatically.

## 🛠️ Support and bug reports

If something breaks after a game update, please report:

- The **Yuri-RO version** and whether you use the extension or userscript.
- Your **browser and version**.
- What you expected versus what happened.
- A screenshot or error message, if available.

Please don't share passwords, account tokens, cookies, or other private account information.

Join the community: **https://discord.gg/DvP8UxQP3J**

## 🔒 Source and distribution

MiniYuri is free to use. The original development source is kept private; this repository is intended for downloadable builds, documentation, and release notes.

**Browser-delivered JavaScript remains inspectable.** Minification or obfuscation does not make client-side code impossible to examine.

## ⚠️ Disclaimer

Yuri-RO is an **unofficial fan-made tool**. It is not developed, approved, or endorsed by RO Survivors or its creators. Modifying gameplay may violate the game's rules and could lead to account penalties. Use it at your own risk.

RO Survivors and its associated assets belong to their respective owners. The Yuri-RO branding and mascot are separate from the game.

---

<div align="center">

**Made for the MiniYuri community 🌸**

</div>
