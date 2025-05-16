# Orthogonal 3D Path Generator

A web-based tool for generating and visualizing 3D paths with 90-degree turns, exportable as STL files for 3D printing or further processing.

![Orthogonal Path Example](https://via.placeholder.com/800x400?text=Orthogonal+Path+Generator)

## 🎮 Live Demo

[Check out the live demo here](https://your-project-url.vercel.app/)

## ✨ Features

- Generate self-avoiding 3D paths with exact 90-degree turns
- Customize parameters:
  - Number of segments
  - Tube radius
  - Cube boundary size
  - Random seed for reproducible results
- Interactive 3D visualization with multiple camera views
- Export to STL format for use in 3D modeling software
- Perfect for creating abstract 3D sculptures and silhouettes

## 🚀 Use Cases

- Generate abstract sculptures for 3D printing
- Create interesting silhouettes for laser cutting
- Experiment with procedural 3D design
- Educational tool for exploring 3D geometric paths

## 🛠️ How to Use

1. Adjust the parameters using the sliders:
   - **Number of Segments**: Controls the complexity of the path
   - **Tube Radius**: Sets the thickness of the tube
   - **Cube Size**: Defines the boundary that contains the path
   - **Random Seed**: Change to get different path patterns while keeping other settings the same

2. Click "Generate New Path" to create a new path with your parameters

3. Use the camera controls to navigate the 3D view:
   - **Left-click + drag**: Rotate the view
   - **Right-click + drag**: Pan the view
   - **Scroll**: Zoom in/out
   - **View Preset**: Select predefined camera positions

4. When satisfied with your design, click "Export STL" to download the 3D model

5. Import the STL into your favorite 3D modeling software for further processing

## 🔧 Technical Implementation

This generator uses:

- **Three.js** for 3D rendering and geometry creation
- **Custom path generation algorithm** that ensures:
  - Only 90-degree turns
  - Self-avoiding paths (no self-intersections)
  - Containment within the specified cubic boundary
- **STLExporter** for converting the 3D geometry to STL format

## 🖥️ Local Development

To run this project locally:

1. Clone the repository:
   ```
   git clone https://github.com/your-username/orthogonal-path-generator.git
   cd orthogonal-path-generator
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. Open your browser to `http://localhost:3000`

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [Three.js](https://threejs.org/) for the 3D rendering engine
- Inspired by concepts from orthogonal art, pipe puzzles, and self-avoiding walks

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
