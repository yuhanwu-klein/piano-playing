# 3D Modeling Room

An interactive 3D room visualization built with Three.js, featuring custom textures for the floor and walls.

## Features

- **Textured Floor**: Uses `WechatIMG541.jpg` as the floor texture
- **Textured Walls**: Uses `WechatIMG542.jpg` as the wall texture
- **Interactive Controls**:
  - Left Click + Drag: Rotate the camera view
  - Right Click + Drag: Pan the camera
  - Mouse Wheel: Zoom in/out
- **Dynamic Lighting**: Includes ambient, directional, and point lights
- **Sample Objects**: Includes a cube, sphere, and cylinder with animations
- **Shadows**: Real-time shadow rendering for enhanced realism

## Room Specifications

- **Dimensions**: 12 x 6 x 12 units (width x height x depth)
- **Four walls** with textured surfaces
- **Ceiling** with neutral color
- **Semi-transparent front wall** for better viewing

## How to Run

1. Open `index.html` in a modern web browser (Chrome, Firefox, Edge, or Safari)
2. The 3D room will load automatically
3. Use mouse controls to navigate and explore the room

## Technology Stack

- **Three.js**: 3D graphics library
- **OrbitControls**: Camera control system
- **WebGL**: Hardware-accelerated 3D rendering

## File Structure

```
.
├── index.html           # Main HTML file with 3D scene
├── WechatIMG541.jpg    # Floor texture
├── WechatIMG542.jpg    # Wall texture
└── README.md           # This file
```

## Browser Compatibility

This project requires a modern browser with WebGL support:
- Chrome 9+
- Firefox 4+
- Safari 5.1+
- Edge (all versions)

## Customization

To modify the room:
- **Room size**: Edit `roomWidth`, `roomHeight`, and `roomDepth` variables in `index.html`
- **Texture repeat**: Adjust the `repeat.set()` values for floor and wall textures
- **Lighting**: Modify the light positions and intensities
- **Objects**: Add or remove objects in the scene

## Note

This is a client-side only application - no server required. Simply open the HTML file in your browser to run.
