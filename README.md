# Mono: Residential Evil 🏚️🔦

**Residential Evil** is a 3D survival horror game built with Python and PyOpenGL. Take control of **Mono**, a character navigating a haunting environment filled with unnerving mannequins that only move when you aren't looking. Your mission: survive the escalating terror, find the "door of longing," and rescue a trapped soul.

---

## 📸 Overview

The game features a unique 3D environment with dynamic lighting, furniture, and a deep, atmospheric aesthetic. Players must use strategic movement and their trusty flashlight to navigate the house.

> "The long-awaited door revealed itself... the door of longing stood before him."

---

## ✨ Key Features

-   **🔦 Dynamic Flashlight Mechanics**: Your flashlight is your only defense. Shine it on mannequins to freeze them in place, but beware—they are faster than they look.
-   **👁️ Dual Perspective**: Seamlessly toggle between **First-Person** (immersive) and **Third-Person** (tactical) camera views.
-   **🔵 Safe Zones**: Discover glowing blue circles on the floor where you can hide from the mannequins' relentless pursuit.
-   **🗺️ Map Reveal**: Use a special ability to briefly illuminate the entire house and plan your escape.
-   **📈 Escalating Difficulty**: Progress through 3 levels of increasing mannequin speed and density.
-   **🚪 Final Mission**: Once enough mannequins are defeated, find the Red Door to win the game.

---

## 🎮 Controls

| Action | Key |
| :--- | :--- |
| **Movement** | `W` `A` `S` `D` |
| **Shoot / Start Game** | `SPACE` |
| **Toggle Flashlight** | `F` |
| **Reload Ammo** | `V` |
| **Toggle Camera (1st/3rd Person)** | `E` |
| **Adjust Camera Pan** | `Left` / `Right` Arrows |
| **Map Reveal (Ability)** | `K` |
| **Restart Game** | `R` (on GameOver/Win) |

---

## 🛠️ Requirements & Installation

### Prerequisites
- Python 3.8 or higher
- PyOpenGL
- PyOpenGL-accelerate (for better performance)

### Setup
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd "First Program"
   ```
2. Install dependencies:
   ```bash
   pip install PyOpenGL PyOpenGL-accelerate
   ```
3. Run the game:
   ```bash
   python Residential_Evil.py
   ```

---

## 🏗️ Building for Distribution

### Windows
You can package the game into a standalone `.exe` using the provided `.spec` file:
```bash
pip install pyinstaller
pyinstaller --clean ResidentialEvil_Windows.spec
```
The executable will be generated in the `dist/` folder.

### macOS
For macOS, ensure you have a compatible environment for OpenGL. You can run the script directly using Python.

---

## 📜 Credits
Developed as part of the **CSE423 Computer Graphics** course at BRAC University.

---

*Note: This project uses assets and logic inspired by atmospheric horror games to demonstrate 3D rendering and interaction in OpenGL.*
