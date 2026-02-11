# 3D City Exploration - Computer Graphics 2024

[![C++](https://img.shields.io/badge/C++-17-blue?style=flat-square&logo=c%2B%2B)](https://isocpp.org/)
[![OpenGL](https://img.shields.io/badge/OpenGL-4.x-red?style=flat-square&logo=opengl)](https://www.opengl.org/)
[![Visual Studio](https://img.shields.io/badge/IDE-Visual%20Studio-purple?style=flat-square&logo=visual-studio)](https://visualstudio.microsoft.com/)

This project is the final assignment for the **Computer Graphics** course at **Politecnico di Milano** (A.Y. 2023/2024). It features an interactive 3D urban environment where users can explore, interact with buildings, and drive a vehicle with realistic camera projections.

**Teacher**: Marco Gribaudo  
**Final Score**: 30 / 30

---

## 📋 Official Documentation
For a detailed look at the project requirements and the technical guidelines provided by the university, you can consult the official assignment file:

👉 [**Project Assignment (PDF)**](./Projects_rules.pdf)

---

## 🚀 Key Technical Features

### 🏙️ Environment & Rendering
* **3D Urban Simulation**: A detailed virtual city featuring modular buildings and navigable streets.
* **Interactive Interiors**: Seamless transition and interaction with specific building interiors, such as a shop and an apartment.
* **Advanced Lighting**: Real-time lighting implementation using custom **GLSL shaders** (Phong/Blinn-Phong) for realistic surface reflections.

### 🎥 Sophisticated Camera System
The project implements a versatile camera system with real-time switching between:
* **Standard Views**: First-person and Third-person perspectives for immersive exploration.
* **Axonometric Projections**: Mathematically precise implementation of **Isometric**, **Dimetric**, and **Trimetric** views for the vehicle mechanics.
* **Spectator Mode**: Free-roaming camera for environment inspection.

### 🚗 Mechanics & Input Integration
* **Vehicle System**: Complex state management for entering, driving, and exiting vehicles.
* **Player Physics**: Core movement mechanics including walking, running, and jumping with collision handling.
* **Dual Input Support**: Full integration of **Keyboard** and **Gamepad (Joypad)** for all actions, from navigation to UI management.

---

## 🎮 Controls
Press <kbd>H</kbd> (Keyboard) or <kbd>START</kbd> (Gamepad) to see the command list.

### Keyboard:
* **Movement**: <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd>
* **Run / Jump**: <kbd>SHIFT</kbd> / <kbd>SPACE</kbd>
* **Coordinates**: Press <kbd>L</kbd> to print current coordinates.
* **Spectator Mode**: <kbd>P</kbd> to enter, <kbd>O</kbd> to exit.
* **Interactions**: <kbd>K</kbd> to enter car/check doors, <kbd>J</kbd> to exit car.
* **Vehicle Views**: <kbd>B</kbd> (1st Person), <kbd>V</kbd> (3rd Person), <kbd>1</kbd>/<kbd>2</kbd>/<kbd>3</kbd> (Axonometric).
* **UI**: <kbd>G</kbd> to close overlay text, <kbd>ESC</kbd> to exit.

### Gamepad:
* **Movement**: <kbd>Left Stick</kbd>
* **Run / Jump**: <kbd>RB</kbd> / <kbd>LB</kbd>
* **Spectator Mode**: <kbd>D-PAD UP</kbd> to enter, <kbd>D-PAD DOWN</kbd> to exit.
* **Interactions**: <kbd>A</kbd> to enter car, <kbd>B</kbd> to exit car.
* **Vehicle Views**: <kbd>D-PAD LEFT/RIGHT</kbd>, <kbd>X</kbd>, <kbd>Y</kbd>, <kbd>Right Thumb (Click)</kbd>.

---

## 🛠️ Software Stack
* **Language**: C++17
* **API**: OpenGL 4.x
* **IDE**: Visual Studio 2022

---

## 👥 Team Composition
* [Alessandro Fornara](https://github.com/AlessandroFornara)
* [Donato Fiore](https://github.com/DoneyMoney)
* [Riccardo Figini](https://github.com/RiccardoFigini)

---

## ⚖️ License
This project is for educational purposes as part of the Politecnico di Milano curriculum.
