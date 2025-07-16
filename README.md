# Farm-NG-Project

A modular robotics and computer vision platform developed by the MU Precision Agriculture and Automation Lab (MU-PAAL). This project aims to enable intelligent navigation, perception, and control for autonomous agricultural machines using open-source tools.

## 🚜 Project Overview

This repository contains code and configuration files for:

- Vehicle control (manual and autonomous)
- Path planning using RTK GPS
- Real-time image processing (e.g. path detection)
- Sensor integration (IMU, camera, GPS)
- Web interface for remote operation and monitoring
- Docker-based deployment (local and robot-side)

---

## 🏗️ Directory Structure

```bash
farm-ng-project/
├── local_side/            # Control logic, UI, path planning
├── robot_side/            # Onboard hardware interaction
├── docker/                # Dockerfiles and compose configs
├── models/                # DL models and scripts
├── utils/                 # Helper scripts and tools
├── data/                  # Optional data samples
├── LICENSE
└── README.md
