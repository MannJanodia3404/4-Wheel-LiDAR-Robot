# 4-Wheel LiDAR Robot — CAD Design

A 3D CAD model of a **4-wheeled mobile robot equipped with a LiDAR sensor** mounted on top for 360° environmental scanning. Designed for applications in autonomous navigation, SLAM (Simultaneous Localization and Mapping), and robotics research.

![Robot Render](images.png)

---

## Overview

This robot is a compact, four-wheeled mobile platform built for autonomous navigation tasks. The roof-mounted LiDAR provides full 360° awareness of surroundings, making it well-suited for indoor mapping, obstacle avoidance, and autonomous path planning.

---

## Key features

- **4-wheel drive chassis** for stable movement on flat and uneven terrain
- **Top-mounted LiDAR sensor** for 360° distance scanning
- **Internal compartment** for batteries, motor drivers, and a microcontroller / single-board computer
- **Modular design** — components can be modified or replaced independently
- Designed for easy assembly and 3D printing

---

## Files in this repository

| File | Description | View |
|------|-------------|------|
| `4-wheel robot.stl` | Full 3D mesh — viewable in browser | [🔗 View in 3D](4-wheel%20robot.stl) |
| `4-wheel robot.step` | Editable CAD assembly file | [📥 Download](4-wheel%20robot.step) |

> **Note:** The STEP file contains the complete assembly with all components embedded — no need to download individual parts separately.

---

## How to view the design

### Option 1: View in your browser
Click on **[`4-wheel robot.stl`](4-wheel%20robot.stl)** — GitHub will render it as an interactive 3D model. You can:
- **Rotate** by clicking and dragging
- **Zoom** with your scroll wheel
- **Pan** by right-clicking and dragging

### Option 2: Open in CAD software
Download **`robot_assembly.step`** and open it in:
- SolidWorks
- Autodesk Fusion 360
- Autodesk Inventor
- FreeCAD (free & open-source)
- Onshape (free in browser)

---

## Design specifications

| Spec | Value |
|------|-------|
| **Overall dimensions** | [L × W × H — fill in] |
| **Wheel diameter** | [e.g. 65 mm] |
| **Ground clearance** | [e.g. 25 mm] |
| **Weight (estimated)** | [e.g. ~1.2 kg] |
| **LiDAR model** | [e.g. RPLiDAR A1 / YDLiDAR X4 / Slamtec] |
| **CAD software** | [SolidWorks / Fusion 360 / etc.] |

---

## Suggested hardware (for building the real robot)

This is the hardware this CAD model is sized for. Adjust based on your actual build:

- **Microcontroller / SBC:** Raspberry Pi 4 / Jetson Nano / Arduino Mega
- **Motors:** 4× DC geared motors with encoders
- **Motor driver:** L298N or TB6612FNG
- **LiDAR:** RPLiDAR A1 (or similar 360° 2D LiDAR)
- **Battery:** 11.1V LiPo or 12V Li-ion pack
- **Wheels:** Rubber wheels, ~65 mm diameter
- **Chassis material:** 3D printed (PLA / PETG) or laser-cut acrylic

---

## 3D printing notes

If you'd like to 3D print the chassis:
- **Material:** PLA or PETG recommended
- **Layer height:** 0.2 mm
- **Infill:** 30–40% for structural parts
- **Supports:** Required for the LiDAR mount and motor housings
- **Print orientation:** Flat surfaces down for best strength

---

## Possible applications

- Indoor SLAM and mapping
- Obstacle detection and avoidance
- Home automation / autonomous cleaning robot
- Educational robotics projects
- ROS (Robot Operating System) experimentation
- Research platform for navigation algorithms

---

<!--
## 📸 Gallery

![Top View](images/top.png)
![Side View](images/side.png)
![LiDAR Mount Detail](images/lidar_mount.png)
-->

---

## Future improvements

- [ ] Add a camera module for visual SLAM
- [ ] Design a swappable battery compartment
- [ ] Improve suspension for rough terrain
- [ ] Add IMU mounting bracket
- [ ] Add bumper sensors

---

## License

This project is shared for **personal, educational, and research purposes**. Feel free to download, view, modify, and learn from the design. Attribution appreciated if you use or remix it.

---

## Feedback & contributions

Have suggestions, found an issue, or built one yourself? Open an [issue](../../issues) or reach out — I'd love to hear about it!

If you like this project, consider giving it a star!
