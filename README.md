# GMForge — AI Session Scribe, Instant Encounter Builder & Live Co-Pilot for VTTs

Official public distribution repository for **GMForge (`v0.1.0`)**.

- **Live Web App, GM Command Center & Landing Page:** [https://alanhenschel.github.io/gmforge-releases/](https://alanhenschel.github.io/gmforge-releases/)
- **Owlbear Rodeo 2.0 Popover View:** [https://alanhenschel.github.io/gmforge-releases/?vtt=owlbear](https://alanhenschel.github.io/gmforge-releases/?vtt=owlbear)

---

## 1. Install in Owlbear Rodeo 2.0
1. Open your Owlbear Rodeo 2.0 profile -> **Extensions** -> **Add Extension**.
2. Paste the Manifest URL:
   ```text
   https://alanhenschel.github.io/gmforge-releases/manifest.json
   ```
- **Official Store Submission PR:** [owlbear-rodeo/extensions#207](https://github.com/owlbear-rodeo/extensions/pull/207)

---

## 2. Install in Foundry VTT (v12 & v13)
1. Open Foundry VTT Setup -> **Add-on Modules** -> **Install Module**.
2. In the **Manifest URL** field at the bottom, paste:
   ```text
   https://github.com/alanhenschel/gmforge-releases/releases/latest/download/module.json
   ```
3. Click **Install** and enable **GMForge AI Co-Pilot & VTT Sync** (`gmforge-sync`) inside your world.

---

## 3. Install in Chrome / Brave / Edge (Roll20 & D&D Beyond)
1. Download [`chrome-extension-gmforge-roll20-ddb.zip`](https://github.com/alanhenschel/gmforge-releases/releases/download/v0.1.0/chrome-extension-gmforge-roll20-ddb.zip) from the [Latest Release](https://github.com/alanhenschel/gmforge-releases/releases/tag/v0.1.0) and unzip it.
2. Open `chrome://extensions` (or `brave://extensions`), enable **Developer mode**, click **Load unpacked**, and select the unzipped folder.
3. Open any campaign on `https://app.roll20.net` or `https://www.dndbeyond.com` to toggle the GMForge drawer.
