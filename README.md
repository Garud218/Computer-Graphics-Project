# Computer-Graphics-Project

## Verdant Valley: A 2D Animated Scene with WebGL

A computer graphics project that demonstrates a 2D animated scene built using WebGL and JavaScript.

**Author**: Tushar Verma  
**Roll No**: 221147  

## Description

This project showcases fundamental concepts of 2D computer graphics. It features a dynamic landscape scene with multiple animated elements, rendered in real-time using WebGL. The application is built with vanilla JavaScript and the glMatrix library for vector and matrix operations, demonstrating core graphics principles without relying on high-level game engines.

## Features

- **Dynamic 2D Animations**: The scene includes multiple animations, such as rotating windmills, twinkling stars, and moving boats, all createdಮ

System: created using affine transformations (translation, rotation, scaling).
- **Interactive Rendering Modes**: Users can switch between 3 different rendering modes in real-time:
  - *Solid View*: Displays objects with solid colors.
  - *Wireframe View*: Shows the geometric structure of the objects.
  - *Point View*: Renders only the vertices of the objects.
- **Modular Codebase**: The project is built with a focus on clean and reusable code, with separate functions for drawing different objects and handling animations.
- **Complex Scene Composition**: The scene is composed of over 20 unique objects, including procedural shapes like circles, stars, and complex polygons.

## Technologies Used

- **WebGL**: For rendering 2D graphics directly in the

System: browser.
- **JavaScript (ES6)**: For the core application logic, animations, and user interactions.
- **glMatrix**: A JavaScript library for high-performance vector and matrix math.
- **HTML5**: For the structure of the application.

## How to Run

Since this is a client-side application with no server dependencies, you can run it directly in your web browser.

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <repository-directory>
   ```

3. Open the `2D_scene.html` file in a modern web browser that supports WebGL (like Chrome, Firefox, or Edge).

## File Structure

- `2D_scene.html`: The main HTML file that sets up the canvas and includes the necessary scripts.
- `2D_Scene.js`: Contains all the JavaScript code for WebGL initialization, shader setup, object rendering, and animation logic.
- `glMatrix-0.9.5.min.js`: The glMatrix library file for handling matrix and vector operations.

## Future Work

This project lays the foundation for several exciting enhancements. Future development could include:

- **Transition to 3D**: Evolve the scene into a full 3D environment by incorporating depth, perspective projection, and 3D models.
- **Advanced Lighting**: Implement dynamic lighting models, such as Phong or Blinn-Phong shading, to create realistic shadows and highlights.
- **Interactive Camera Controls**: Add user controls to pan, zoom, and rotate the camera, offering different perspectives of the scene.
- **Texture Mapping**: Apply textures to the surfaces of objects to add detail and realism, such as wood for the house or water for the river.
- **Day/Night Cycle**: Create an animated day/night cycle that dynamically changes the sky color, sun position, and lighting conditions.
