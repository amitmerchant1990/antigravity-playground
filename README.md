# Antigravity Playground

Welcome to the **Antigravity Playground**! This repository serves as a hub for interactive web experiments and challenges.

## 🌟 Doodle Challenge Portal

The main entry point (`index.html`) acts as a portal to various generative art pieces and interactive doodles built during the Antigravity Challenge.

### 🎨 Featured Project: Emergent Typography

Located in the `emergent-doodle/` directory, this is an interactive generative art piece where simulated physics (gravity and noise) organically form a given text.

**Features:**
- **Particle System:** Uses thousands of particles to draw text dynamically.
- **Physics Engine:** Custom implementations of gravitational pull, turbulence (Perlin noise), and viscosity/friction.
- **Interactive Controls:** Real-time parameter tuning for particle count, gravity strength, noise levels, and more.
- **Customizable:** Change the displayed text and the color palette on the fly.
- **Export:** Easily download your generated artwork as a PNG image.

### 🎾 Featured Project: Retro Tennis Doodle

Located in the `retro-tennis-doodle/` directory, this is a classic retro tennis game reimagined with a modern Google Doodle aesthetic.

**Features:**
- **Single File Architecture:** The entire game runs from a single dependency-free `index.html` file.
- **Mobile First Controls:** Playable via mouse drag or touch inputs.
- **AI Opponent:** Features a simple AI paddle to play against.
- **Responsive Canvas:** The game scales gracefully to fit your browser window while maintaining the play area aspect ratio.

## 🚀 How to Run

This project is built using standard web technologies (HTML, CSS, Vanilla JavaScript) and uses the [p5.js](https://p5js.org/) library for canvas rendering. It has **zero build steps** and requires **no package installations**.

To view the project, you can simply open the `index.html` file in any modern web browser:

1. Clone or download this repository.
2. Double-click on `index.html` in the root directory to open the Doodle Challenge Portal.
3. Click on the "Emergent Text" card to launch the interactive art piece.

*Alternatively, if you prefer using a local server (recommended to avoid potential CORS issues with local files in some browsers), you can run:*

```bash
# Using Python 3
python3 -m http.server

# Using Node.js (if you have http-server installed)
npx http-server
```
Then navigate to `http://localhost:8000` (or the port specified by your server).

## 🛠️ Technology Stack

- **HTML5 Canvas:** For high-performance rendering.
- **CSS3:** Modern, responsive design using CSS variables and flexbox/grid layouts.
- **Vanilla JavaScript:** Clean, dependency-free core logic.
- **p5.js:** Utilized within the Emergent Typography project for simplified canvas drawing and vector math.

---
*Built with ❤️ during the Antigravity Challenge.*
