<div align="center">

# Luna AI Desktop Assistant
### *Your AI. Your PC. Your rules.*

[English](README.md) | [العربية](README.ar.md)

[![Windows](https://img.shields.io/badge/Platform-Windows%2011-blue?style=flat-square&logo=windows)](https://github.com/EinMM/Luna-AI)
[![Status](https://img.shields.io/badge/Status-Beta%200.1-orange?style=flat-square)](https://github.com/EinMM/Luna-AI)
[![Privacy](https://img.shields.io/badge/Privacy-Local%20First-success?style=flat-square&logo=shield)](https://github.com/EinMM/Luna-AI)

</div>

---

## 🚀 Welcome to Luna AI

**Luna AI** is a powerful Windows desktop assistant designed around a **Local-first** philosophy. It runs directly on your hardware without internet or forced subscriptions by default, manages your local files, reads documents, and respects your privacy. When you need heavy-duty processing, a single click routes your request securely to the cloud.

Built by **Hussain (EinMM)**, Luna features a custom-engineered engine (`llama-cpp` based) that manages its own lifecycle, includes intelligent hardware-based model recommendations, and introduces a flexible, multi-language interface architecture starting with Arabic and English.

---

## ✨ Core Features (Beta 0.1)

* **🧠 Local-First & Custom Engine:** Runs locally out-of-the-box. Features **Speed Mode (MTP)** for blazing-fast token generation and **Sleep Mode** to automatically free up VRAM when idling or when fullscreen games/apps need resources.
* **📂 Smart File Assistant:** Browse, search, read, and write Word (`.docx`), Excel (`.xlsx`), and PDF documents locally within your workspace (`Documents\Luna Workspace`). Every write or delete action **requires your explicit confirmation**.
* **🌐 Hybrid & Cloud Flexibility:** Optional integration with **OpenAI** and **Google Gemini** using your own API keys securely stored in the Windows Credential Manager. Includes fine-grained privacy controls and "Private Chat 🔒" modes.
* **💬 Multi-Language & RTL Ready:** Designed from the ground up to support modern multi-language interfaces (starting with English and Arabic) with full RTL layout support.
* **🧠 Persistent Personal Memory:** Remembers what *you* ask it to remember ("Remember that..."), avoiding hidden tracking while strictly rejecting sensitive data (passwords, PINs, IDs).

---

## ⚙️ Hardware Recommendations

Luna automatically detects your GPU VRAM and suggests the optimal local model:
* **12GB+ VRAM:** Gemma 4 12B (QAT) + Speed Mode
* **6–8GB VRAM:** Gemma 4 E4B (Balanced speed & tools)
* **4GB VRAM:** Gemma 4 E2B
* **No dedicated GPU:** Cloud mode recommended.

---

## ⛔ What Luna Cannot Do (Yet)
* Voice input/output (STT/TTS).
* Direct web browsing (text search via OpenAI is supported).
* Autonomous OS/app control (coming in future levels).
* macOS or Linux support (**Windows 11 only**).

---

## 🗺️ Roadmap Highlights
* **Luna Web & Vision** (Web search with sources, image understanding)
* **Desktop Agent** (Multi-step desktop workflows and tray integration)
* **Luna Voice & Background Tasks**
* **Skills & Plugins Ecosystem**

---

- 👉 [Report a Bug](https://github.com/Lunaicore/Luna-AI/issues/new?labels=bug&title=%5BBUG%5D+)
- 👉 [Request a Feature](https://github.com/Lunaicore/Luna-AI/issues/new?labels=enhancement&title=%5BFEATURE%5D+)

---

## 📄 License & Terms
All rights reserved © 2026 **Hussain (EinMM)**. This repository hosts public release assets and documentation for Luna AI Beta.
