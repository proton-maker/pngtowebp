# PNG ➜ WebP Converter (GUI)

A sleek and simple drag-and-drop tool to convert `.png` images to `.webp`, built with Python and powered by [`ttkbootstrap`](https://ttkbootstrap.readthedocs.io/).

> 🔄 Supports batch conversion, dark/light mode toggle, and auto output to `output/` directory.

---

## ✨ Features

- ✅ Modern GUI with `ttkbootstrap` (Flatly / Darkly themes)
- 🖱️ Drag & Drop support (optional)
- 📂 Bulk and single file selection
- 🗂️ Auto-create `output/` directory for results
- 🌗 Light/Dark theme toggle
- 💬 Live progress bar + error reporting
- 🧪 Built-in dependency auto-installer (pip)

---

## 🖥️ Screenshot

![webp-converter-screenshot](https://github.com/proton-maker/pngtowebp/blob/main/image.png?raw=true)  
*(Screenshot placeholder — replace with your actual app preview)*

---

## 🧰 Requirements

- Python **3.8+**
- OS: Windows / macOS / Linux (Tkinter compatible)

Required Python packages (installed automatically on first run):

- `Pillow`
- `ttkbootstrap`
- `tkinterdnd2` *(optional, only for drag-and-drop)*

---

## 🚀 How to Run

```bash
python image-to-webp.py
