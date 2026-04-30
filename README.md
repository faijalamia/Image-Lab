# 🔬 Image Lab – Professional Edition










A modern, feature-rich desktop image processing application built with Python, OpenCV, and Tkinter.
It provides an intuitive GUI for performing transformations, filtering, enhancement, noise simulation, and edge detection — all in one place.

📸 Preview

(Add screenshots here later for better GitHub engagement)

📁 Tip: Create a /screenshots folder and add UI images
✨ Features
🖼️ Image Management
Load multiple formats: .png, .jpg, .jpeg, .bmp, .tiff, .webp
Save processed images
Reset to original
Live preview rendering
Image metadata panel (size, mode, memory)
✏️ Edit & Transform
🔍 Zoom (0.1x – 5x)
✂️ Smart cropping:
1:1 (Square)
4:3 (Standard)
16:9 (Widescreen)
3:2, 2:3
🔊 Noise Laboratory

Simulate real-world noise:

Gaussian
Salt & Pepper
Rayleigh
Exponential
Uniform
Erlang

✔ Adjustable intensity
✔ Interactive preview

🔧 Filters
Mean Filters
Arithmetic Mean
Geometric Mean
Harmonic Mean
Contra-harmonic Mean (Q parameter)
Order Filters
Median
Max
Min
Midpoint
✨ Enhancement
Brightness control (-100 → +100)
Contrast scaling (0.1 → 3.0)
Presets:
Auto
Vivid
Warm
Cool
Dramatic
⚡ Live update mode
🤖 Auto-enhance (intensity-based)
🔍 Edge Detection
Canny (adjustable thresholds)
Sobel
Laplacian
Prewitt
Overlay edges on original image
📊 Extra Features
🕘 Action history panel
📋 Sidebar with image info
🎨 Modern styled UI (custom Tkinter widgets)
📑 Tab-based workflow
🛠️ Tech Stack
Technology	Purpose
Python	Core language
OpenCV	Image processing
NumPy	Numerical operations
Pillow (PIL)	Image rendering
Tkinter	GUI framework
📁 Project Structure
ImageLab/
│
├── main.py                  # Main GUI application
├── modules/
│   └── processing.py        # Image processing functions
├── screenshots/             # (Add UI images here)
└── README.md
🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/yourusername/image-lab.git
cd image-lab
2️⃣ Install Dependencies
pip install opencv-python numpy pillow
3️⃣ Run Application
python main.py
🧑‍💻 Usage Guide
Click 📁 Load Image
Choose a tab:
Edit
Noise
Filters
Enhance
Edge
Apply operations using controls
Save using 💾 Save
📌 Roadmap
 Custom kernel editor
 Histogram visualization
 Undo/Redo system
 Batch image processing
 AI-based enhancement
🤝 Contributing

Contributions are welcome!

# Fork the repo
# Create a new branch
git checkout -b feature-name

# Commit changes
git commit -m "Added new feature"

# Push
git push origin feature-name

Then open a Pull Request 🚀

📄 License

This project is licensed under the MIT License.

👩‍💻 Author

Faija Lamia
CSE Undergraduate | Image Processing Enthusiast

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
🧑‍💻 Share with others
