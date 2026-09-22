# Robust Locomotion Control for Legged Robots

[![GitHub Pages](https://img.shields.io/badge/Project%20Page-GitHub%20Pages-blue?style=flat-square&logo=github)](https://regulussjd.github.io/legged-robot-control/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-brightgreen?style=flat-square&logo=python)](https://www.python.org/)
[![Isaac Gym](https://img.shields.io/badge/Simulator-Isaac%20Gym-orange?style=flat-square)](https://developer.nvidia.com/isaac-gym)

> **Official Project Page & Showcase**:  
> 🌐 **[https://regulussjd.github.io/legged-robot-control/](https://regulussjd.github.io/legged-robot-control/)**

---

## 📖 Overview

This repository contains the codebase and project showcase for **Robust Locomotion Control for Legged Robots under Complex & Unstructured Terrains**.

Key features:
- **Zero-Shot Sim-to-Real Transfer**: Asymmetric actor-critic network trained in Isaac Gym with extensive domain randomization.
- **Robust Disturbance Rejection**: Dynamic push recovery supporting sudden external impacts up to 150 N.
- **High-Rate Low-Latency Control**: 50 Hz high-level RL policy combined with 500 Hz low-level joint PD impedance control.

---

## 🚀 Project Webpage

The project webpage is built with lightweight, responsive HTML5 + Tailwind CSS, hosted for free via GitHub Pages.

To customize the webpage locally:
```bash
# Simply open index.html in any modern browser
# or use a local static server
python -m http.server 8000
```

---

## 📝 Citation

If you find this work helpful in your robotics research, please consider citing:

```bibtex
@article{sjd2026leggedcontrol,
  title   = {Robust Locomotion Control for Legged Robots in Unstructured Terrains},
  author  = {SJD and Collaborators},
  journal = {arXiv preprint arXiv:2609.XXXXX},
  year    = {2026},
  url     = {https://github.com/RegulusSJD/legged-robot-control}
}
```