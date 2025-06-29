
# RARLAP: Reward-Augmented Reinforcement Learning for Autonomous Parking

## Overview

This work introduces a novel framework called **RARLAP** (Reward-Augmented Reinforcement Learning for Autonomous Parking), developed to address the highly constrained and precision-critical task of autonomous vehicle parking. Parking is unlike other autonomous driving challenges—it requires fine-grained steering control, tight spatial awareness, and real-time adaptation to complex environments. Traditional rule-based or purely supervised methods often fall short in handling the dynamic, continuous control requirements of real-world parking scenarios.

To address this, RARLAP leverages deep reinforcement learning with structured reward augmentation and a custom Unity-based 3D simulation environment that is fully compatible with Unity ML-Agents.

---

## Features

- 🧠 **Reward-Augmented RL**: Supports sparse, dense, and milestone-based reward shaping strategies to guide training behavior in complex parking scenarios.
- 🎮 **Unity 3D Simulation**: High-fidelity simulation environment with realistic physics, Ackermann steering, and customizable parking configurations.
- 🔄 **Continuous Control**: Designed for continuous action spaces, suitable for real-world precision steering tasks.
- ⚙️ **ML-Agents Integration**: Fully compatible with Unity ML-Agents Toolkit for seamless agent training and evaluation.
- 📂 **Modular & Extensible**: Codebase structured for easy extension, benchmarking, and integration with new algorithms or tasks.

---
![Car_Parking_Project](Car_Parking_Project.jpg)
![Inference](PPO-MBR_inference.gif)


## Project Strcture
- A complete environment in inference mood is provided that can be run without any installations on linux. [https://github.com/ahmadsuleman/AI-based-car-parking-using-reinforcement-learning](https://github.com/ahmadsuleman/AI-based-car-parking-using-reinforcement-learning)
