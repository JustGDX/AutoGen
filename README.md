# 🏠 Floor Plan Designer — Smart Layout Builder

A Kivy-based app to design and generate custom floor plans with **drag-and-drop rooms, appliances, auto-layout generation, and OCR image scanning**.

Built with **Python (Kivy)** — lightweight, modular, and designed for interactive floor planning and visualization.

---

## 🚀 Features

* 🧱 Add rooms, walls, borders, appliances, and text
* 🏠 Auto-generate 4-room layouts (bedroom, kitchen, living room, bathroom)
* 🔄 Rotate objects in 90° steps
* 📏 Appliance scaling based on room size
* 📷 OCR scan (detects labels from images using Tesseract)
* 💾 Save & load floor plans as `.json`
* ↩️ Undo / Redo support
* 📐 Pixel ↔ meter conversion (1m = 40px)
* ⚠️ Validation system (warns if furniture doesn’t fit)

---

## 🧱 Project Files

### `floorplan_designer.py`

* Core engine of the app
* Handles elements, validation, auto-layout generation
* Manages scaling, rotation, and unit conversion logic

### `main.py`

* Main UI controller
* Handles toolbar actions and user input
* Manages OCR integration and file save/load operations

### `widgets.py`

* Rendering system
* Draws rooms, appliances, text, and grid on canvas
* Responsible for visual updates and UI drawing logic

---

## 🧠 How It Works

The system is split into 3 main layers:

* **Logic Layer** → Handles structure, rules, and data (`floorplan_designer.py`)
* **Control Layer** → Manages user interaction and app flow (`main.py`)
* **Render Layer** → Draws everything visually (`widgets.py`)

This separation keeps the project clean, scalable, and easy to extend.

---

## 📝 Usage

### For Users

1. Run the application
2. Drag and place rooms and objects
3. Use auto-layout for instant room generation
4. Rotate and scale items as needed
5. Save your design as a `.json` file

### For Developers

* Modify layout logic in `floorplan_designer.py`
* Update UI controls in `main.py`
* Customize rendering in `widgets.py`

---

## 🔮 Future Improvements

* 3D floor plan visualization
* Grid snapping system upgrade
* Better drag-and-drop physics
* Room templates library
* Export to PDF / image format
* Multi-floor support

---

## 👤 Author

**GDX**

---
📅 Date Created: 08/08/2025
