# 🌌 3D Solar System Engine

A high-performance 3D rendering engine built with **Modern OpenGL** and **C++**, 
simulating 4,000+ interactive celestial bodies in real time.

> Built as a graphics exploration project | Nov 2025

---

## ✨ Features
- **4000+ celestial bodies** rendered in real time
- **Phong lighting model** with vertex and fragment shaders (GLSL)
- **Texture mapping** for realistic planet surfaces
- **Procedural generation** for asteroid belts and smaller bodies
- **6-DOF Camera System** — fly through the solar system freely
- **VBO/VAO optimized** GPU memory management for high throughput

## 🛠️ Tech Stack
| Component | Technology |
|---|---|
| Language | C++ |
| Graphics API | OpenGL (Modern / Core Profile) |
| Shaders | GLSL |
| Math Library | GLM |
| Build System | Visual Studio (MSVC) |

## 🚀 How to Run

### Prerequisites
- Windows with Visual Studio 2022
- OpenGL 3.3+ compatible GPU
- GLFW and GLAD libraries

### Steps
```bash
1. Clone the repo
   git clone https://github.com/Shreya3048/Solar-System-Model

2. Open SolarSystem.slnx in Visual Studio

3. Make sure GLFW and GLAD are linked in project properties

4. Build & Run (Ctrl+F5)
```

## 🎮 Controls
| Key | Action |
|---|---|
| W/A/S/D | Move camera |
| Mouse | Look around |
| Scroll | Zoom in/out |

## 📸 Screenshots
<!-- Add screenshots here after capturing them -->
*Coming soon — run the project to see it in action!*

## 📁 Project Structure
```
Solar-System-Model/
├── main.cpp              # Main rendering loop & scene setup
├── SolarSystem.vcxproj   # Visual Studio project config
└── SolarSystem.slnx      # Solution file
```
