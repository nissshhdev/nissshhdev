<div align="center">

# 🚀 nissshhdev

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Mono&size=22&duration=4000&pause=1000&color=00D4FF&center=true&vCenter=true&width=800&lines=RETRO+TECH+MEETS+MODERN+DESIGN;3D+Animations+%26+Smooth+Interactions;Building+the+Future.+One+Line+of+Code." alt="Typing SVG" />

</div>

---

## 🎮 3D Interactive Section

```
╔══════════════════════════════════════════════════════════════╗
║                   THREE.JS EXPERIENCE                        ║
║                                                              ║
║  This section features:                                      ║
║  • Rotating 3D cube with retro neon wireframe               ║
║  • Floating particles system                                ║
║  • Smooth camera animations                                 ║
║  • Interactive mouse tracking                               ║
║  • Retro scanline effects overlay                           ║
║                                                              ║
║  👉 Add this to your portfolio:                            ║
║  https://github.com/nissshhdev/3d-retro-portfolio          ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

### 🛠️ Three.js Implementation Guide

```javascript
// Core Setup for Your Portfolio
import * as THREE from 'three';

const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
const renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });

// Retro Color Palette
const COLORS = {
  neon_cyan: 0x00D4FF,
  neon_pink: 0xFF006E,
  neon_purple: 0xB537F2,
  retro_green: 0x39FF14,
  dark_bg: 0x0a0e27
};

// Create Animated Cube with Neon Wireframe
const geometry = new THREE.BoxGeometry(2, 2, 2);
const material = new THREE.MeshPhongMaterial({ 
  color: COLORS.neon_cyan,
  wireframe: true,
  emissive: COLORS.neon_cyan,
  emissiveIntensity: 0.3
});
const cube = new THREE.Mesh(geometry, material);
scene.add(cube);

// Animation Loop
function animate() {
  requestAnimationFrame(animate);
  
  // Smooth rotation
  cube.rotation.x += 0.005;
  cube.rotation.y += 0.007;
  
  // Pulsing effect
  cube.scale.set(
    1 + Math.sin(Date.now() * 0.003) * 0.1,
    1 + Math.cos(Date.now() * 0.003) * 0.1,
    1 + Math.sin(Date.now() * 0.003) * 0.1
  );
  
  renderer.render(scene, camera);
}
animate();
```

---

<table>
  <tr>
    <td width="50%" valign="top">

## 💻 About This Design

A fusion of **retro computing aesthetics** with **modern web technologies**:

```
┌─ RETRO ELEMENTS ──────────┐
│ • CRT scanlines           │
│ • Neon glow effects       │
│ • Terminal typography     │
│ • Pixel art inspiration   │
│ • 8-bit color palette     │
│ • Wireframe 3D shapes     │
└──────────────────────────┘
```

**Modern Tech Stack:**
- Three.js for 3D animations
- GSAP for smooth tweening
- Particles.js for floating effects
- Canvas-based rendering
- WebGL optimization

    </td>
    <td width="50%" valign="top">

## 🎯 Features

✨ **Smooth Animations**
- GPU-accelerated 3D rendering
- Easing functions for fluid motion
- Mouse tracking interactions
- Scroll-triggered animations

🌈 **Retro-Modern Fusion**
- Neon color gradients
- CRT monitor effects
- Glitch animations
- Scanline overlays
- Vaporwave vibes

⚡ **Performance**
- Optimized WebGL
- LOD (Level of Detail)
- Request Animation Frame
- Efficient particle systems

    </td>
  </tr>
</table>

---

## 🎨 Retro Tech Stack

<div align="center">

| Layer | Technologies |
|-------|---|
| **3D Engine** | ![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-FF0000?style=for-the-badge) |
| **Animation** | ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge) ![Canvas API](https://img.shields.io/badge/Canvas-DD0031?style=for-the-badge) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| **Styling** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) |

</div>

---

## 🎬 Animation Showcase

```
┌────────────────────────────────────────────┐
│  ANIMATION EFFECTS AVAILABLE:              │
├────────────────────────────────────────────┤
│                                            │
│  1️⃣  Rotating 3D Wireframe Cube           │
│      └─ Neon glow, pulsing scale          │
│                                            │
│  2️⃣  Particle Field Background            │
│      └─ Floating, interactive particles   │
│                                            │
│  3️⃣  CRT Scanline Overlay                 │
│      └─ Retro monitor effect              │
│                                            │
│  4️⃣  Glitch Transitions                   │
│      └─ Section transitions                │
│                                            │
│  5️⃣  Smooth Scroll Animations             │
│      └─ GSAP timeline sequences           │
│                                            │
│  6️⃣  Mouse Tracking Effect                │
│      └─ 3D object follows cursor          │
│                                            │
└────────────────────────────────────────────┘
```

---

## 📊 Stats & Analytics

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nissshhdev&show_icons=true&theme=dark&hide_border=true&bg_color=0a0e27&text_color=00D4FF&title_color=FF006E)](https://github.com/nissshhdev)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nissshhdev&layout=compact&theme=dark&hide_border=true&bg_color=0a0e27&text_color=00D4FF&title_color=FF006E)](https://github.com/nissshhdev)

</div>

---

## 🗂️ Featured Projects

<div align="center">

| 🎮 Project | 📝 Description | 🔗 Link |
|-----------|---|---|
| **3D Retro Portfolio** | Interactive Three.js portfolio with neon animations | [View →](https://github.com) |
| **Particle System** | Custom particle effects with Retro vibes | [View →](https://github.com) |
| **Glitch Generator** | Dynamic glitch effects for web design | [View →](https://github.com) |
| **CRT Monitor Sim** | Authentic CRT scanline simulator | [View →](https://github.com) |

</div>

---

## 🔧 Advanced Animation Techniques

### Particle System
```javascript
// Floating retro particles
class ParticleSystem {
  constructor(count = 100) {
    this.particles = [];
    for (let i = 0; i < count; i++) {
      this.particles.push({
        x: Math.random() * window.innerWidth,
        y: Math.random() * window.innerHeight,
        vx: (Math.random() - 0.5) * 2,
        vy: (Math.random() - 0.5) * 2,
        size: Math.random() * 3,
        color: this.getRetroColor()
      });
    }
  }
  
  getRetroColor() {
    const colors = ['#00D4FF', '#FF006E', '#39FF14', '#B537F2'];
    return colors[Math.floor(Math.random() * colors.length)];
  }
  
  update() {
    this.particles.forEach(p => {
      p.x += p.vx;
      p.y += p.vy;
      // Boundary wrapping
      if (p.x < 0) p.x = window.innerWidth;
      if (p.y < 0) p.y = window.innerHeight;
    });
  }
}
```

### CRT Scanline Effect
```css
/* Retro CRT Monitor */
.crt-effect {
  position: relative;
  overflow: hidden;
}

.crt-effect::after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: repeating-linear-gradient(
    0deg,
    rgba(0, 0, 0, 0.15),
    rgba(0, 0, 0, 0.15) 1px,
    transparent 1px,
    transparent 2px
  );
  pointer-events: none;
  animation: scanlines 8s linear infinite;
}

@keyframes scanlines {
  0% { transform: translateY(0); }
  100% { transform: translateY(10px); }
}
```

---

## 🌐 Interactive Elements

```
╔════════════════════════════════════════════╗
║  MOUSE INTERACTIONS ENABLED                ║
║                                            ║
║  • Hover: 3D object reacts to mouse        ║
║  • Click: Triggers animation sequence      ║
║  • Scroll: Parallax & scroll animations    ║
║  • Move: Particle attraction/repulsion     ║
║                                            ║
╚════════════════════════════════════════════╝
```

---

## 💡 Get Started With Your Own 3D Portfolio

**Installation:**
```bash
npm install three gsap
```

**Basic Template:**
```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body { margin: 0; overflow: hidden; background: #0a0e27; }
    canvas { display: block; }
  </style>
</head>
<body>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
```

---

## 📫 Connect & Collaborate

<div align="center">

```
RETRO_TERMINAL_v1.0 // CONNECTION_GATEWAY
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📧 Email: contact@example.com
🐦 Twitter: @yourhandle
💼 LinkedIn: /in/yourprofile
🌐 Portfolio: yoursite.com
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

---

<div align="center">

```
╔════════════════════════════════════════════════╗
║                                                ║
║  "The future is retro. The past is modern."   ║
║                                                ║
║  Thanks for visiting my digital space! 🎮    ║
║  Let's create something extraordinary.        ║
║                                                ║
╚════════════════════════════════════════════════╝
```

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Mono&size=14&duration=5000&pause=1000&color=39FF14&center=true&vCenter=true&width=700&lines=Building+3D+experiences+with+retro+vibes.;Smooth+animations+meet+classic+aesthetics.;Let's+ship+it." alt="Footer" />

</div>

---

<div align="center">

![Visitor Badge](https://komarev.com/ghpvc/?username=nissshhdev&color=00D4FF&style=flat-square)

**[↑ back to top](#)**

</div>
