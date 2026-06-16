# CesiumJS 3D Model Alignment Sandbox

An interactive CesiumJS sandbox built with Vite, designed to load and precisely align custom 3D models (`.glb` / `.gltf`) on a 3D globe with high-resolution satellite imagery, terrain, and custom controls.

## Getting Started

Follow these steps to run the project locally after cloning it from GitHub:

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed (version 18 or higher recommended).

### Installation & Launch

1. **Clone the repository:**
   ```bash
   git clone <your-repository-url>
   cd cesium-globe-test
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Open the URL printed in the terminal (usually `http://localhost:5173` or similar).

---

## Features

- **Custom Model Loading**: Loads a high-quality custom 3D model of the British Museum (`1-2.glb`).
- **Interactive Calibration UI**: Real-time sliders to adjust the model's Scale, Heading, Height Offset, Latitude, and Longitude.
- **Custom Viewports**: Starts in a beautiful Northwest-facing "hero view" focusing on the main columns and entrance.
- **D-Pad Camera Controls**: Smooth camera panning, zooming, looking, and tilting.
- **Performance Monitor**: Real-time stats showing FPS, draw calls, triangles, and camera height.
