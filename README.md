
# WebGL MSH Viewer (Streaming Visualization)

🎮 A lightweight, client-side mesh viewer built with WebGL2, capable of streaming and visualizing `.msh` and `.res` files. This tool is designed to handle large files in the browser, offering smooth interaction and real-time scalar field coloring.

> 🚫 **Note:** The core rendering and parsing logic is not open-sourced. Only the viewer interface and usage entry are public.

---

## 🌐 Online Preview

You can open the [viewer.html](./viewer.html) file locally or deploy it to GitHub Pages.

Upload your `.msh` and `.res` files to see them visualized directly in the browser.

---

## 📂 Project Structure

webgl-msh-viewer/
├── viewer.html # Public-facing UI
├── core.min.js # Minified core logic (non-open-source)
├── example/ # Optional sample .msh/.res files
└── README.md


---

## 🚀 Features

- ✔️ WebGL2 rendering, no server needed
- 📦 Stream-based parsing of large mesh/result files
- 🎨 Field-based scalar coloring
- 📁 Works entirely in the browser

---

## 🛡 License & Disclosure

This project distributes only the public interface and the compiled logic.  
The original source code is intentionally excluded to protect proprietary parsing/rendering algorithms.

MIT License applies to the visible parts.

---

## 📩 Feedback & Suggestions

Feel free to [open an issue]([https://github.com/](https://github.com/lizzyly7/simulation-view/issues)) to report bugs or suggest improvements.

感谢支持！欢迎提出宝贵意见 😊
