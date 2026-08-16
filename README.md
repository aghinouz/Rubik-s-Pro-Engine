<div align="right">
  <strong>🇬🇧 English</strong> | <a href="README_zh.md">🇨🇳 简体中文</a>
</div>

# Rubik's Pro Engine: 3D-2D Topological Simulation 🧊

A highly optimized, dependency-free, and high-performance N-order Rubik's Cube topological visualization engine. 

## ✨ Core Features

*   **Unlimited N-Order Support**: Seamlessly switch and render anything from a 1x1x1 to a 50x50x50 cube and beyond.
*   **Extreme Performance (GPU Instancing)**: Powered by Three.js `InstancedMesh`. No matter how high the order is, the Draw Call is strictly locked to `2`. Eliminates CPU/GPU bottlenecks, ensuring 60FPS even on a 50-order cube.
*   **Continuous Topological Mapping**: The 2D topological diagram on the left strictly maps the 3D spatial deflection in real-time based on 3D polar coordinate focal calculations.
*   **WCA Algebraic Engine**: Natively parses standard Singmaster notation (e.g., `U`, `M`, `3Rw`, `2L'`, `x`). Supports asynchronous queue execution, allowing continuous "blind typing" during animations without losing input focus.
*   **Reversible Edit Mode**: Built-in painting palette with strict topological physics validation (total color conservation, face-color mutual exclusion, opposite-color mutual exclusion).
*   **History & Causal Backtracking**: Complete two-way timeline (Undo / Redo), one-click WCA random scrambling, and history wiping.

## 🚀 Live Demo

This project is deployed on GitHub Pages. Click to play:
**[👉 Live Demo Here](https://aghinouz.github.io/Rubik-s-Pro-Engine/)**

## 🛠️ Local Usage

Pure front-end, single-file architecture. No `npm install` needed.
Simply clone this repository and double-click `index.html` in any modern browser.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
