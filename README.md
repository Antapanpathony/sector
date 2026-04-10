# Project Title: Asteroid RTS Engine

## 1. Project Title and Description
**Project Title:** RTS Game Engine & Core Module  
**Description:** A JavaScript-based real-time strategy (RTS) engine core designed for asteroid mining simulations. It provides a high-level game loop, a rendering system using HTML5 Canvas for units and map features, and input handling logic. The project focuses on unit mechanics like health bars, ownership capture zones, and visual effects.

## 2. Tech Stack
*   **Language:** Vanilla JavaScript (ES6+)
*   **Rendering:** HTML5 Canvas API (`<canvas>`, `Context` methods)
*   **DOM:** Browser Event Listeners (`mousedown`, `mousemove`, etc.)
*   **Framework:** None (Pure Vanilla JS implementation)

## 3. Prerequisites
*   A modern web browser (Chrome, Firefox, Safari, or Edge) supporting ES6 syntax and Canvas 2D context.
*   No external build tools, compilers, or package managers (npm/node) are required to run the core logic provided in this snippet.

## 4. Installation & Setup
To set up the project locally without a build process:

1.  Create a new folder on your computer.
2.  Inside the folder, create a file named `index.html`.
3.  Paste the following content into `index.html` (the provided code block). Ensure global constants like `NCOL`, `ASHAPES`, and `GAME_CONSTS` are defined elsewhere or within this script context.

## 5. Usage
1.  Open the `index.html` file in your local web server. **Do not** open the raw HTML file directly from disk (double-clicking) to avoid cross-origin errors, though modern browsers may handle it if resources are loaded locally.
2.  Click the canvas area to initiate a battle or map generation.
3.  Use `Mouse` for selecting units and `Keyboard` for actions (e.g., 'F5' for restart).

### Command Examples
```bash
# Option 1: Open directly (may have resource loading warnings)
$ open index.html

# Option 2: Serve locally (Recommended for production)
$ python3 -m http.server 8000
# Visit http://localhost:8000/
```

## 6. Configuration
*   **Environment Variables:** None detected in this core module.
*   **Config Files:** No external configuration files are used; variables like `NCOL` (Node Colors), `CAP_FULL` (Capture Full capacity), and unit definitions (`ASHAPES`, `DEFS`) must be defined globally before the script executes.
*   **CLI Flags:** None detected.


## 7. Contributing
If you wish to contribute improvements:
1.  **Fork** the repository.
2.  **Create a feature branch** (`git checkout -b feature/new-unit`).
3.  **Commit** your changes (`git commit -m 'Add new unit shape'`).
4.  **Push** to the branch (`git push origin feature/new-unit`).
5.  **Open a Pull Request**.

*Note: Changes should maintain compatibility with `requestAnimationFrame` loops and avoid introducing build steps not present in this vanilla JS setup.*
