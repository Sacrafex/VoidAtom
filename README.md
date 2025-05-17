# VoidAtom

VoidAtom is an interactive particle simulation inspired by particle life algorithms. It creates colorful atoms that interact based on customizable rules, forming dynamic clusters and patterns.

![VoidAtom Screenshot](https://via.placeholder.com/800x500/111111/cccccc?text=VoidAtom+Simulation)

## Features

- Customizable particle physics with color-based interaction rules
- Real-time parameter adjustment via GUI
- Cluster detection and visualization
- Interactive controls:
  - Click to create attraction/repulsion pulses
  - Mouse movement affects nearby particles
  - Keyboard shortcuts for quick adjustments
- Export functionality for images and videos
- Seed-based randomization for reproducible simulations

## How to Use

1. Open `index.html` in a modern browser
2. Use the GUI to adjust simulation parameters:
   - Change interaction rules between colors
   - Adjust physics parameters (gravity, viscosity, etc.)
   - Toggle visual elements (clusters, trails, etc.)
3. Interact with the simulation:
   - Click to create pulses
   - Move mouse to attract/repel particles
   - Use keyboard shortcuts (see below)

## Keyboard Shortcuts

- `R`: Randomize rules
- `T`: Toggle cluster visualization
- `O`: Reset particles
- `S`: Make rules symmetric
- `P`: Pause simulation
- `F`: Toggle Fullscreen
- `Space`: Randomize particle positions

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- Uses lil-gui for parameter controls
- Canvas API for rendering
- MediaRecorder API for video export

## Installation

No installation required - just open the HTML file in a browser. For local development:

1. Clone this repository
2. Open `index.html` in your browser

## Customization

The simulation can be extensively customized through:
- The interactive GUI
- Modifying the source code:
  - Change color palette in `predefinedColors`
  - Adjust maximum particle count and radii
  - Modify physics constants

## License

MIT License - feel free to use and modify as you like.

---

**Note**: For best performance, use a modern browser with hardware acceleration enabled.
