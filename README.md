# 🎧 Spectral Audio Restoration (NVSR-Inspired)

This project is a standalone spectral recovery tool that enhances audio recordings by restoring missing high-frequency content. It uses advanced DSP techniques inspired by neural audio super-resolution models like AudioSR and NVSR-ResUNet — but with no machine learning required.

---

## Features

- **DSP-based enhancement** that mimics neural super-resolution smoothness
- **Pink noise blending** with adaptive gain and high-frequency masking
- **Fully offline** — no deep learning models or GPU needed
- **Cross-platform** Python script with `tkinter` GUI
- **Supports RX XML presets** for batch processing

---

## Demo (Audio Files)

You can compare before and after audio examples in the `demo/` folder:

- `demo/before.wav` – original low-quality or degraded audio
- `demo/after.wav` – restored version with enhanced high frequencies

---

## Installation

**Requirements:**

- Python 3.8+
- Required packages:
