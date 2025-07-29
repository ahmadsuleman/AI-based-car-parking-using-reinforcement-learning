
# Reward-Augmented Reinforcement Learning for Continuous Control in Precision Autonomous Parking via Policy Optimization Methods

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
- Project Files contain the Prefeb for Unity Simulation
- Related scripts are provided in the scripts folder
- Pretrained weights for SAC and PPO along with training configuations are given with filenames SAC_MBR and PPO_MBR respectively.

## Cite 
@misc{suleman2025rewardaugmentedreinforcementlearningcontinuous,
      title={Reward-Augmented Reinforcement Learning for Continuous Control in Precision Autonomous Parking via Policy Optimization Methods}, 
      author={Ahmad Suleman and Misha Urooj Khan and Zeeshan Kaleem and Ali H. Alenezi and Iqra Shabbir Sinem Coleri and Chau Yuen},
      year={2025},
      eprint={2507.19642},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2507.19642}, 
}
  
