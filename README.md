# 🌌 Tri-Sphere TDA Dynamics

**Tri-Sphere TDA Dynamics** is a real-time 3D particle simulation that visualizes topological data analysis concepts through motion and interaction.  
It uses a **tri-sphere attractor system** to generate emergent particle dynamics while displaying **Betti-0 connectivity** and **center topology** in real time.

---

## 🚀 Live Demo
🎮 **Try it now:** [Tri-Sphere TDA Dynamics on GitHub Pages](https://arcesoftware.github.io/TDA_Dynamics_Simulation/)

---

## 🧠 Features

- 🧩 **Tri-Sphere Gravitational Field** — three dynamic attractors influence thousands of particles  
- ⚙️ **Interactive dat.GUI-style Control Panel** *(fully offline, no CDN)*  
- 🎥 **Camera Controls**
  - Mouse drag — orbit  
  - Mouse wheel — zoom  
  - Ctrl + G — recenter  
- 🌐 **WebGL Renderer** with depth, trails, and glow effects  
- 💡 **Topological Analysis Module**
  - Real-time Betti-0 estimation  
  - Cluster detection via particle adjacency  
- 🧭 **Modern dark-glass GUI** with live toggles:
  - Show/hide sphere centers  
  - Enable/disable auto camera orbit  
  - Reset simulation  

---

## 🧰 Technology Stack

| Component | Description |
|------------|--------------|
| **Language** | HTML5 + JavaScript (ES6) |
| **Rendering** | WebGL via custom shaderless context |
| **Math Engine** | Custom vector + distance field logic |
| **Control Panel** | Inline dat.GUI-like module (no external deps) |
| **Compatibility** | Chrome, Edge, Firefox (desktop + mobile) |

---

## ⚙️ Local Run Instructions

You can run the simulation directly by opening `index.html` in your browser — no server needed.

```bash
# Clone the repository
git clone https://github.com/your-username/Tri-Sphere-TDA-Dynamics.git

# Open the file
cd Tri-Sphere-TDA-Dynamics
start index.html    # (Windows)
# or
open index.html     # (Mac)
