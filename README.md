<<<<<<< HEAD

# Three.js Earth Visualization 🌍

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Site-green?style=for-the-badge&logo=vercel)](https://ketan1406.github.io/threejs-earth/)

An interactive 3D Earth visualization with realistic textures, atmospheric glow, and dynamic starfield background built with Three.js.

## ✨ Key Features

- **Multi-Layer Earth Model** - Surface, bump, specular, cloud, and atmospheric layers.
- **Custom Shader Effects** - Fresnel-based atmospheric scattering simulation.
- **Procedural Starfield** - Dynamically generated 3D star background.
- **Real-time Interactions** - Orbit controls for rotation/zoom.
- **Responsive Design** - Auto-adjusts to screen size/resolution.
- **Performance Optimized** - Efficient buffer geometry and instancing.

## 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ketan1406/threejs-earth.git

   ```

2. Install dependencies:

   ```bash
   cd threejs-earth && npm install

   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## 💡 Technologies Used

- Three.js - Core 3D rendering engine.
- Vite - Build tool & dev server.
- GLSL - Custom shader programming.
- OrbitControls - Camera interaction.
- gh-pages - Automated deployment.

## 📂 Project Structure

    threejs-earth/
    ├── public/
    │   └── textures/          # Earth surface & cloud maps
    ├── src/
    │   ├── getFresnelMat.js   # Atmospheric shader logic
    │   ├── getStarfield.js    # 3D starfield generator
    │   └── index.js           # Main scene setup
    └── vite.config.js         # Build configuration
