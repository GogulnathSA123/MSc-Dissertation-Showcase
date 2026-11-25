# MSc Robotics Dissertation Showcase — RoboMamba-DINO-ACT

**Live GitHub Page:** [https://gogulnathsa123.github.io/MSc-Dissertation-Showcase/](https://gogulnathsa123.github.io/MSc-Dissertation-Showcase/)

**Title:** *Latency-Aware Visuomotor Policies for Robotic Manipulation: A Comparative Simulation and Physical Study on the SO-101 Arm*  
**Author:** Gogulnath Sathish Amuthavalli  
**Institution:** University of Bristol & University of the West of England (Bristol Robotics Laboratory)  
**Supervisor:** Mark Hansen  

## Contents Hosted on This Page
- **Interactive Policy Slide Show (`interactive-reel.html`)** — 6-slide HTML5 Canvas reel (*"Look once. Act ×16."*) with live 2-link IK + 16-step ghost chunk poses, DINOv2 `512 → 32` spatial token pooling animation, and temporal ensembling registration curves.
- **Demonstration & Evaluation Videos (`assets/videos/`)**:
  - Physical 6-DoF SO-101 closed-loop autonomous pick-and-place manipulation (Hardware-in-the-Loop over 1M-baud UART with dual USB cameras).
  - NVIDIA Isaac Sim 5.1 (`LeIsaac-SO101-CustomTask-v0`) visuomotor policy rollout.
- **Engineering & Safety Guides (`assets/docs/`)**:
  - Visual System Architecture & Workflows Guide PDF
  - Technical Implementation Manual PDF
  - Signed University of Bristol SO-101 Hardware Safety Risk Register PDF
- **Code Repositories**:
  - Training, Isaac Sim Multi-Seed Benchmark & Physical SO-101 Evaluation: [GogulnathSA123/RoboMamba_DINO_ACT_Policy](https://github.com/GogulnathSA123/RoboMamba_DINO_ACT_Policy)
  - Containerized CPU/GPU Inference Stack: [GogulnathSA123/RoboMamba_Policy_Inference](https://github.com/GogulnathSA123/RoboMamba_Policy_Inference)
