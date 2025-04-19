# 3D Glass Cuboid with CSS

This project demonstrates a 3D **glassy cuboid** built using pure HTML and CSS, with realistic 3D transforms and a glassmorphism aesthetic.



## ✨ Features

- CSS `transform-style: preserve-3d` to create a true 3D object.
- Glassmorphism look using:
  - `rgba()` transparency
  - `backdrop-filter: blur()`
- Smooth infinite 360° rotation.
- Fully responsive and lightweight – no JS needed!

## 🧱 How it Works

- The `.scene` container uses CSS `perspective` to give a 3D view.
- Six `.face` elements represent each side of the cuboid (front, back, left, right, top, bottom).
- Each face is positioned in 3D space using `transform: translateZ()` and rotation angles.
- The blur and semi-transparent backgrounds create the **frosted glass** effect.

## 🖥️ Usage

1. Clone or download this repository.
2. Open `
