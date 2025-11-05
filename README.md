# Ethereal Flow - Algorithmic Art by Claude

A mesmerizing, interactive generative art experience featuring particle systems, flow fields, and beautiful mathematical patterns.

## 🎨 Features

### Four Stunning Visual Modes

1. **Flow Field** - Particles flow through a dynamic vector field created with Perlin noise, creating organic, swirling patterns
2. **Cosmic Web** - Interactive gravitational attraction/repulsion around your cursor, creating cosmic web-like structures
3. **Aurora** - Flowing, wave-like patterns reminiscent of the Northern Lights
4. **Mandala** - Spiraling, symmetrical patterns that evolve around the center point

### Interactive Elements

- **Mouse Interaction**: Move your cursor to influence particle behavior (especially in Cosmic Web mode)
- **Click & Drag**: Create new particles where you click and drag (in Flow Field and Cosmic Web modes)
- **Spacebar**: Regenerate the noise field for new patterns
- **Real-time Controls**: Switch between modes, pause/resume, and clear the canvas

## 🚀 How to Use

1. **Open the Art**: Simply open `index.html` in any modern web browser
2. **Explore Modes**: Click the mode buttons to switch between different visual styles
3. **Interact**: Move your mouse, click and drag to create particles
4. **Experiment**: Press spacebar to regenerate patterns, try different modes

## 🔧 Technical Details

- **Pure JavaScript** - No external libraries or dependencies
- **Canvas API** - Hardware-accelerated 2D rendering
- **Perlin Noise** - Custom implementation for smooth, organic motion
- **Particle System** - Thousands of particles with individual trails and life cycles
- **Performance Optimized** - Smooth 60fps animation with intelligent trail rendering

## 🎯 The Mathematics Behind the Beauty

- **Perlin Noise Fields**: Creates smooth, natural-looking randomness for organic flow
- **Vector Fields**: Each particle follows forces calculated from noise functions
- **Gradient Dynamics**: Colors shift through HSL color space based on particle movement
- **Spiral Mathematics**: Mandala mode uses polar coordinates and angular momentum
- **Wave Functions**: Aurora mode combines sine waves with noise for undulating patterns

## 🌟 Customization

The code is well-structured and easy to modify. You can customize:
- Particle count (adjust in `initParticles()`)
- Color schemes (modify HSL values in particle drawing)
- Movement physics (adjust force multipliers and friction)
- Trail lengths (change `maxHistory` values)
- Noise scale (modify noise function parameters)

## 📝 Credits

Created with algorithmic creativity by Claude - An exploration of generative art, particle systems, and the beauty of mathematical patterns.

## 🎭 Enjoy!

Let the particles flow, watch the patterns emerge, and lose yourself in the algorithmic beauty.
