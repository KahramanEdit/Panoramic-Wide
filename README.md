<div align="center">

# 🎮 Panoramic Wide

**Stretch any web video to 32:9 ultra-wide**
**without distorting the center.**

[![Manifest V3](https://img.shields.io/badge/Manifest-V3-22d3ee?style=flat-square)](https://developer.chrome.com/docs/extensions/mv3/)
[![Chrome](https://img.shields.io/badge/Chrome-88%2B-blue?style=flat-square&logo=googlechrome)](https://www.google.com/chrome/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Made by](https://img.shields.io/badge/Made%20by-Clenix%20%2F%20Kahraman-06b6d4?style=flat-square)](https://github.com/KahramanEdit)

</div>

---

## ✨ Features

- 🎯 **Center-preserving stretch**
  Only the edges are warped,
  the middle stays untouched.
- 🎚️ **Adjustable safe zone**
  Protect 20% – 90% of the
  center of the video.
- ⌨️ **Quick toggle**
  Press `Alt + S` anytime
  to enable or disable.
- 🖥️ **Fullscreen aware**
  Works inside native
  fullscreen video players.
- 🧠 **Auto detection**
  Picks the largest
  `<video>` element on the page.
- 🔒 **Zero telemetry**
  No data leaves your device.
  Everything is local.

---

## 📦 Installation

### 1. Get the files

```bash
git clone https://github.com/KahramanEdit/Panoramic-wide.git
Or Code → Download ZIP.

2. Load into Chrome
Open chrome://extensions

Enable Developer mode
(top-right toggle)

Click Load unpacked

Select the Panoramic-wide folder

3. Verify
Open any video and press Alt + S.

🎮 Usage
Action	How
Toggle on / off	Alt + S
Safe zone	Popup (20% – 90%)
Fullscreen	Video's own button
🔧 How It Works
The extension draws the video
into a WebGL canvas and runs
a non-linear fragment shader.

Pixels near the center are
left almost untouched, while
the edges are progressively
stretched. The result looks
natural on 32:9 and 21:9
monitors, ultra-wides, and
multi-monitor setups.

content.js – WebGL renderer

popup.html – settings UI

manifest.json – MV3 config

⚙️ Tech Stack
Manifest V3

WebGL + GLSL fragment shader

chrome.storage.sync

Vanilla JS (no framework)

🐛 Known Limitations
Not available on the
Chrome Web Store
(manual install only)

No auto-update —
re-install after each
new release

Chrome shows a
"Developer mode" banner
on every launch

🔒 Privacy
No user data is collected.
No telemetry. No analytics.

All settings live in
chrome.storage.sync and
never leave your browser.

⚠️ Disclaimer & No Liability
Use at your own risk.

This extension is provided
"as is", without warranty
of any kind, express or implied.

The developer accepts
NO responsibility for any
damage, data loss, broken
players, bricked devices, or
any other consequence arising
from the use of this software.

You are solely responsible
for how you install and use
this extension.

Author: Clenix / Kahraman
GitHub: KahramanEdit

<div align="center"> <sub>Made with ☕ by <b>Clenix</b></sub> </div> ```
