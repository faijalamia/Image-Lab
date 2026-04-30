# 🔬 Image Lab – Professional Edition

A modern, feature-rich desktop image processing application built with Python, OpenCV, and Tkinter. It provides an intuitive GUI for performing transformations, filtering, enhancement, noise simulation, and edge detection — all in one place.

---

## 📸 Preview

<img width="1918" height="997" alt="image" src="https://github.com/user-attachments/assets/9ba2c5ed-f0b3-4df2-b5b0-282f88d252f4" />


> 📁 **Tip:** Create a `/screenshots` folder and add UI images here.

---

## ✨ Features

### 🖼️ Image Management
- Load multiple formats: `.png`, `.jpg`, `.jpeg`, `.bmp`, `.tiff`, `.webp`
- Save processed images
- Reset to original
- Live preview rendering
- Image metadata panel (size, mode, memory)

### ✏️ Edit & Transform
- 🔍 Zoom (0.1× – 5×)
- ✂️ Smart cropping with preset ratios:
  - 1:1 (Square)
  - 4:3 (Standard)
  - 16:9 (Widescreen)
  - 3:2, 2:3

### 🔊 Noise Laboratory
Simulate real-world noise with adjustable intensity and interactive preview:
- Gaussian
- Salt & Pepper
- Rayleigh
- Exponential
- Uniform
- Erlang

### 🔧 Filters

**Mean Filters**
- Arithmetic Mean
- Geometric Mean
- Harmonic Mean
- Contra-harmonic Mean (Q parameter)

**Order Filters**
- Median
- Max
- Min
- Midpoint

### ✨ Enhancement
- Brightness control (−100 → +100)
- Contrast scaling (0.1 → 3.0)
- Presets: Auto, Vivid, Warm, Cool, Dramatic
- ⚡ Live update mode
- 🤖 Auto-enhance (intensity-based)

### 🔍 Edge Detection
- Canny (adjustable thresholds)
- Sobel
- Laplacian
- Prewitt
- Overlay edges on original image

### 📊 Extra Features
- 🕘 Action history panel
- 📋 Sidebar with image info
- 🎨 Modern styled UI (custom Tkinter widgets)
- 📑 Tab-based workflow

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core language |
| OpenCV | Image processing |
| NumPy | Numerical operations |
| Pillow (PIL) | Image rendering |
| Tkinter | GUI framework |

---

## 📁 Project Structure

```
ImageLab/
│
├── main.py                  # Main GUI application
├── modules/
│   └── processing.py        # Image processing functions
├── screenshots/             # UI preview images
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/faijalamia/Image-Lab.git
cd Image-Lab
```

### 2️⃣ Install Dependencies

```bash
pip install opencv-python numpy pillow
```

### 3️⃣ Run the Application

```bash
python main.py
```

---

## 🧑‍💻 Usage Guide

1. Click **📁 Load Image** to open an image file
2. Choose a processing tab:
   - **Edit** — zoom and crop
   - **Noise** — simulate noise
   - **Filters** — apply mean/order filters
   - **Enhance** — adjust brightness, contrast, and presets
   - **Edge** — detect edges
3. Apply operations using the controls in each tab
4. Save your result using **💾 Save**

---

## 📌 Roadmap

- [ ] Custom kernel editor
- [ ] Histogram visualization
- [ ] Undo/Redo system
- [ ] Batch image processing
- [ ] AI-based enhancement

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

```bash
# Fork the repo, then:
git checkout -b feature-name
git commit -m "Add new feature"
git push origin feature-name
```

Then open a **Pull Request** 🚀

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Faija Lamia**  
CSE Undergraduate | Image Processing Enthusiast  
[GitHub Profile](https://github.com/faijalamia)

---

## ⭐ Support

If you find this project useful:
- ⭐ **Star** the repository
- 🍴 **Fork** it
- 🧑‍💻 **Share** it with others
