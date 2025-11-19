# Virtual Tour Viewer

Interactive 3D virtual tour viewer built with Three.js for exploring apartment models in an immersive way.

## Features

- **3D Navigation**: Explore apartment models with realistic first-person controls
- **Interactive Controls**:
  - Mouse for camera rotation
  - WASD or Arrow keys for movement
  - Mouse wheel for zoom
- **Realistic Rendering**: Shadow mapping and professional lighting setup
- **Responsive Design**: Works on all screen sizes
- **Easy Loading**: Simple GLB model loading with progress indicators

## Live Demo

Visit the live demo: [https://nurzhanme.github.io/virtual-tour-viewer/](https://nurzhanme.github.io/virtual-tour-viewer/)

## Usage

Simply open the page and use:
- **Mouse** - Rotate camera view
- **W/A/S/D** or **Arrow Keys** - Move around
- **Mouse Wheel** - Zoom in/out
- **G Key** - Toggle grid (for debugging)

## Technology Stack

- **Three.js** - 3D graphics library
- **GLTFLoader** - For loading 3D models
- **OrbitControls** - Camera control system

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/nurzhanme/virtual-tour-viewer.git
cd virtual-tour-viewer
```

2. Start a local server:
```bash
python3 -m http.server 8000
```

3. Open your browser to `http://localhost:8000`

## Adding Your Own Models

Replace the GLB file and update the model path in `index.html`:
```javascript
const modelUrl = 'your-model.glb';
```

## License

MIT License - feel free to use for your own projects!
