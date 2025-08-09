# Mini Drone Project

![Mini Drone Banner](media/banner.jpg)

A **DIY mini drone** built with Arduino, 615 coreless motors, and a custom lightweight frame.  
This repository contains **firmware**, **hardware designs**, **wiring diagrams**, and a **step-by-step build guide** to help you make your own.
This project has been referenced from MAX IMAGINATION. All the circuit diagram, BOM, CAD files have been referenced from his yt channel.

---

## Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Project Structure](#-project-structure)
- [Bill of Materials](#-bill-of-materials)
- [Wiring Diagram](#-wiring-diagram)
- [Build Instructions](#-build-instructions)
- [Demo Video](#-demo-video)
- [License](#-license)

---

## Overview
This mini drone was designed for **fun, learning, and experimentation** in micro UAV building.  
The goal was to create a **lightweight, affordable** drone using easy-to-source components, with an **Arduino Nano** as the flight controller and an **NRF24L01+** module for wireless control.

**Flight Controller:** Arduino Pro Mini
**Motors:** 615 Coreless (37,000 RPM)  
**Props:** 31mm, 4-blade  
**Battery:** 1 3.7V 380 mAh 25C Lipo Battery 
**Frame:** DIY Popsticle stics and Plastic

---

## Features
- Compact, **lightweight micro quadcopter**
- 2.4GHz NRF24L01 wireless control
- **PID tuning** for stable flight
- Fully open-source firmware & hardware files
- Modular design for easy repairs and upgrades

---

## Project Structure

---

## Bill of Materials
| Part | Quantity | Notes |
|------|----------|-------|
| 615 coreless motor | 4 | 37,000 RPM |
| 31mm 4-blade props | 4 | High lift |
| Arduino Nano | 1 | Flight controller |
| NRF24L01+ PA+LNA | 1 | Radio module |
| LiPo 380mAh 3.7V | 1 | Series connection |
| 3D-printed frame | 1 | PopSticle Sticks |
| Prop guards | 4 | Optional safety |

---

## Wiring Diagram
![Wiring Diagram](docs/wiring-diagram.png)  
*(See `docs/` folder for high-resolution version)*

---

## 🛠 Build Instructions
1. **3D Print the Frame** – STL files in `hardware/`
2. **Mount the Motors** – Secure using motor mounts
3. **Assemble Electronics** – Follow wiring diagram
4. **Flash Firmware** – Upload `firmware/main.ino` to Arduino Nano
5. **Test Without Props** – Verify motor direction & connections
6. **Attach Props & Fly** – Tune PID if needed

---

## Demo Video
[▶ Watch the Drone in Action](https://youtu.be/your-video-link)  

---

## License
This Entire project has been referenced from MAX IMAGINATION. 

---

## Contributing
Got ideas for improvements? Fork this repo, make changes, and submit a pull request!  
Issues & suggestions are welcome.

---

> **Disclaimer:** This drone has sharp, fast-moving propellers. Fly responsibly and comply with your local laws.


