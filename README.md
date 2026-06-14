# 🎨 Color Picker Browser Extension

A high-performance, lightweight browser extension designed for rapid color sampling. Directly extract colors from any webpage with ease and copy their HEX codes to your clipboard—an essential utility for web designers and front-end developers.

## 🚀 Key Features

* **Browser-Native Picking**: Utilize the `EyeDropper` API to capture any pixel color from the current viewport.
* **Rapid Workflow**: Optimized for speed, allowing for instant color grabbing and copying.
* **Clean Interface**: A distraction-free popup menu designed for efficiency.
* **Configurable Settings**: Includes dedicated options for managing extension behavior.

## 🛠️ Tech Stack

* **Manifest V3**: Adheres to modern browser extension standards for security and performance.
* **Vanilla JavaScript**: Efficient event-driven logic.
* **CSS3**: Modern, responsive styling for the popup and options interfaces.

## 📁 Project Architecture

```text
projectcolors/
├── picker/            # Asset folder for picker icons/resources
├── background.js      # Service worker for background processes
├── manifest.json      # Extension metadata and permissions
├── options.html       # UI for extension settings
├── popup.css          # Styling for the popup UI
├── popup.html         # UI for the active picker tool
└── popup.js           # Core picking and clipboard logic

```

## 💻 Installation & Usage

1. **Clone the Repository**:
```bash
git clone https://github.com/amankaushik3919/color-picker12.git
cd color-picker12

```


2. **Load in Browser**:
* Navigate to your browser's extensions page (e.g., `chrome://extensions/`).
* Enable **Developer mode**.
* Select **Load unpacked** and point to the `color-picker12` folder.


3. **Run**: Click the extension icon in your browser toolbar to open the picker and start sampling colors.

---

**License**: Distributed under the **MIT License**.

**Developer**: [Aman Kaushik](https://github.com/amankaushik3919)

*Show your support by starring the repository!*
