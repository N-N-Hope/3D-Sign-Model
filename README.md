# 3D-Sign-Model
This has codes that display 3d animation according to user speech
# 3D Alphabet Visualizer

An interactive 3D visualization tool that displays alphabet letters in 3D when spoken. The application uses speech recognition to capture spoken letters and renders corresponding 3D models in real-time.

## Features

- 🎤 Real-time speech recognition for alphabet letters
- 🖥️ 3D visualization of recognized letters using Three.js
- 🎮 Interactive camera controls (orbit, zoom, pan)
- 📊 Visual feedback for recognized letters
- 🧹 Clear results functionality
- 📱 Responsive design that works on desktop and mobile

## Technologies Used

- [Three.js](https://threejs.org/) - 3D rendering library
- Web Speech API - For speech recognition
- GLTF/GLB - 3D model format
- HTML5/CSS3 - User interface

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/N-N-Hope/3d-alphabet-visualizer.git
   cd 3d-alphabet-visualizer
   
2.Model Setup:
Place your 3D models in an alphabet/ directory
Each letter should be named accordingly (e.g., a.glb, b.glb, etc.)
The main model should be named lady.glb in the root directory

3.Run the Application:
Open index.html in a modern web browser
Chrome or Edge recommended for best speech recognition support

How to Use
1.Click "Start Listening" to enable speech recognition
2.Speak individual letters (A-Z)
3.The application will:
     .Display recognized letters in the queue
     .Show 3D models of recognized letters
     .Provide visual feedback for each recognition

4.Use mouse/touch to:
     .Orbit: Click and drag
     .Zoom: Scroll or pinch
     .Pan: Right-click and drag or two-finger drag

3d-alphabet-visualizer folder/

├── index.html            # Main application file
├── lady.glb              # Main 3D model
├── alphabet/             # Directory for letter models
│   ├── a.glb             # Letter A model
│   ├── b.glb             # Letter B model
│   └── ...               # Other letter models
└── README.md             # This documentation

Browser Support
 Chrome (recommended)
 Edge
 Firefox
 Safari (limited speech recognition support)
Note: Speech recognition requires HTTPS in production or localhost for development.

Known Limitations
Speech recognition accuracy varies by browser and environment

Requires modern browser with WebGL and Web Speech API support

Performance may vary based on device capabilities

Credits
  Nezerwa Ndayisenga hope
  Keza Michelle
   
