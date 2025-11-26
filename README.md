# 🌌 3D Solar System Simulation — OpenGL (Python + GLUT)

A visually realistic, interactive **3D Solar System simulation** built using **PyOpenGL**, **GLUT**, **Pillow**, and **numpy**.  
This project features textured planets, axial tilt, orbital motion, lighting, a starfield background, and highly realistic **two-sided Saturn rings** with thickness and transparency.

Perfect for computer graphics learning, OpenGL demos, college projects, or portfolio showcases.

---

## 🚀 Features

### ✔ Realistic Planet Rendering
- High-quality textures for Sun & planets  
- Individual **axial tilt** for each planet  
- Realistic **revolution + self-rotation**  
- Orbital **inclinations** implemented  

### ✔ Saturn Rings (Advanced)
- Two-sided ring geometry  
- Small physical thickness (0.006 units)  
- Accurate lighting on both faces  
- Support for transparent PNG textures  
- No z-fighting or wrong orientation  

### ✔ Atmosphere & Clouds
- Optional Earth cloud layer  
- Soft blue atmosphere glow using blending  

### ✔ Lighting
- Configured Sun as a point light  
- Ambient, diffuse, and specular components  
- Distance-based attenuation  

### ✔ Camera Controls
- **Left mouse drag:** rotate camera  
- **Mouse wheel:** zoom in/out  
- **P key:** pause/resume animation  
- **Q or ESC:** quit program  

### ✔ Background
- Optional starfield sphere for space backdrop  

---

## 📦 Requirements

Install dependencies:

```bash
pip install PyOpenGL PyOpenGL_accelerate Pillow numpy
