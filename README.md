# VR Drone Flying Simulator

## Overview

VR Drone Flying Simulator is an immersive virtual reality training environment developed using Unreal Engine. The project is designed to help beginners learn and practice drone piloting skills without requiring access to a physical drone.

By simulating real-world drone controls and flight behavior in a safe virtual environment, users can develop confidence and operational skills while eliminating the risks associated with damaging expensive drone hardware during training.

---

## Features

* Virtual Reality drone flight training
* Realistic drone movement and control mechanics
* First-Person Drone POV and User View switching
* Interactive VR controller support
* Drone altitude control using controller grip inputs
* Camera rotation and viewpoint management
* Mission-based training environment
* Safe and cost-effective learning platform
* Large urban simulation environment
* Optimized for PCVR systems

---

## Controls

### Movement

| Action                                 | Control       |
| -------------------------------------- | ------------- |
| Move Forward / Backward / Left / Right | Left Joystick |
| Increase Altitude                      | Grip Button   |
| Decrease Altitude                      | Grip Button   |

### Camera Controls

| Action                       | Control                     |
| ---------------------------- | --------------------------- |
| Toggle User View / Drone POV | A Button (Right Controller) |
| Rotate Drone Camera          | Right Thumbstick / D-Pad    |

### Other Controls

| Action       | Control                    |
| ------------ | -------------------------- |
| Reset View   | X Button (Left Controller) |
| Quit Mission | Y Button (Left Controller) |

---

## Technology Stack

* Unreal Engine 5
* OpenXR
* Virtual Reality (VR)
* Blueprint System
* PCVR Compatible Headsets

---

## Project Structure

```text
Config/          - Project configuration files
Content/         - Maps, Blueprints, Assets, Materials, Meshes
Source/          - C++ source code (if applicable)
Plugins/         - Unreal Engine plugins
```

---

## Getting Started

### Prerequisites

* Unreal Engine 5.x
* VR Headset compatible with OpenXR
* Windows 10/11
* VR-ready GPU

### Installation

```bash
git clone https://github.com/your-username/VR-Drone-Flying-Simulator.git
```

Open the `.uproject` file using Unreal Engine and allow any required assets or shaders to compile.

---

## Purpose

The primary objective of this project is to provide a practical and accessible training platform for learning drone operations in a risk-free virtual environment. Users can practice navigation, altitude control, camera management, and mission execution before operating real-world drones.

---

## Future Improvements

* Advanced drone physics simulation
* Obstacle avoidance training
* Waypoint navigation missions
* Flight performance analytics
* Multiplayer training scenarios
* AI-assisted flight guidance


## License

This project is intended for educational and research purposes.
