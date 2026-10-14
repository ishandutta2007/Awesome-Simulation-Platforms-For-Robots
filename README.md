# Awesome-Simulation-Platforms-For-Robots

# Top Simulation Platforms for Robots Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Physics Simulation, Sensor Modeling & Sim-to-Real Transfer*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Robot Simulation**. These tools let engineers test control algorithms, perception systems, and whole-robot behaviors in physically realistic virtual environments before touching real hardware — reducing development cost, catching failures early, and enabling training data generation at scale.

**Examples** include NVIDIA Isaac Sim, Webots, Gazebo, CoppeliaSim, MuJoCo, Drake, PyBullet, CARLA, AirSim, and AWS RoboMaker (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom physics engines, and transparent sim-to-real pipelines — ideal for robotics researchers, RL practitioners, and teams avoiding per-GPU-hour cloud simulation costs.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim)**  
  GPU-accelerated robotics simulation built on Omniverse. Provides physically accurate simulation, photorealistic rendering, ROS 2 integration, synthetic data generation for perception training, and Isaac Lab for RL workloads. Free for individual developers; enterprise licensing and cloud deployment available.

- **[AWS RoboMaker](https://aws.amazon.com/robomaker/)**  
  Cloud-based simulation service for robotics development. Provides managed ROS/Gazebo simulation, fleet management, and CI/CD pipelines for robot applications. Pricing based on simulation compute hours.

- **[Coppelia Robotics (CoppeliaSim Cloud)**  
  Commercial support and cloud simulation options for CoppeliaSim, the robot simulation platform developed by Coppelia Robotics. Offers cloud-based simulation for teams avoiding local GPU infrastructure.

- **[Microsoft AirSim (Azure)](https://microsoft.github.io/AirSim/)**  
  Originally open-source, now available with Azure cloud deployment for large-scale autonomous vehicle and drone simulation. Microsoft provides managed infrastructure for AirSim-based training pipelines.

- **[MathWorks Robotics System Toolbox](https://www.mathworks.com/)**  
  MATLAB/Simulink-based simulation environment with Gazebo co-simulation, robot modeling, and algorithm development. Commercial licensing required.

- **[Altair (EDEM + MotionSolve)](https://altair.com/)**  
  Commercial multibody dynamics and discrete element simulation for robot design validation.

## Open-Source GitHub Projects

- **[Gazebo](https://github.com/gazebosim/gz-sim)**  
  **The most widely used open-source robot simulator.** Gazebo Sim (formerly Ignition Gazebo) provides high-fidelity physics, sensor simulation, and ROS 2 integration. Modular architecture with physics, rendering, sensors, and GUI as separate libraries. Apache 2.0 licensed. The de facto standard for ROS-based robotics development.

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**  
  **The gold standard for contact-rich manipulation and RL research.** Free and open-source physics engine from Google DeepMind. Excels at articulated body dynamics, contact simulation, and fast computation for reinforcement learning. Apache 2.0 licensed. Includes MuJoCo Menagerie for high-quality robot models.

- **[Webots](https://github.com/cyberbotics/webots)**  
  Complete development environment for modeling, programming, and simulating robots. Features a large library of robot models, sensors, actuators, and environments. Cross-platform with Python, C++, Java, MATLAB, and ROS support. Apache 2.0 licensed. Backed by Cyberbotics since 1998.

- **[Drake](https://github.com/RobotLocomotion/drake)**  
  MIT's model-based design and verification framework for robotics. Combines physics simulation, optimization, and control design in one toolbox. Emphasizes correctness and verification — used for manipulation, locomotion, and autonomous systems research. BSD-3-Clause licensed.

- **[PyBullet](https://github.com/bulletphysics/bullet3)**  
  Python module for physics simulation, robotics, and deep reinforcement learning. Built on the Bullet Physics SDK. Fast, easy to install, and widely used for RL benchmarks (MuJoCo-compatible environments). MIT licensed.

- **[CARLA](https://github.com/carla-simulator/carla)**  
  Open-source simulator for autonomous driving research. Provides realistic urban environments, sensor suites (cameras, LiDAR, radar, GPS, IMU), and ScenarioRunner for testing. Supports ROS and Python APIs. MIT licensed. The standard for AV algorithm development.

- **[AirSim](https://github.com/microsoft/AirSim)**  
  Microsoft's open-source simulator for drones, cars, and other vehicles built on Unreal Engine. Provides physically and visually realistic simulation with hardware-in-the-loop support. API for Python/C++. MIT licensed. (Note: project has slowed but remains widely used.)

- **[CoppeliaSim](https://github.com/coppeliaRobotics/coppeliaSim)**  
  Robot simulation platform with integrated development environment, based on a distributed control architecture. Supports multiple programming languages and physics engines (Bullet, ODE, Vortex, Newton). GPL licensed with commercial options. Formerly known as V-REP.

- **[Open 3D Engine (O3DE)](https://github.com/o3de/o3de)**  
  Apache 2.0 licensed 3D engine with robot simulation capabilities. Features Robotec.ai's ROS 2 Gem for robotics development, physically-based rendering, and scalable simulation.

- **[DART](https://github.com/dartsim/dart)**  
  Dynamic Animation and Robotics Toolkit. Open-source library for kinematics, dynamics, collision detection, and motion planning. BSD-2-Clause licensed.

- **[SAPIEN](https://github.com/haosulab/SAPIEN)**  
  GPU-accelerated physical simulation for articulation and manipulation research. Part of the ManiSkill benchmark ecosystem. MIT licensed.

- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)**  
  Emerging open-source physics simulation platform for robotics and embodied AI. Claims extreme speed (43M FPS for Franka arm) and unified physics solver. Under active development. Apache 2.0 licensed.

- **[Brax](https://github.com/google/brax)**  
  Google's differentiable physics engine for JAX. Enables gradient-based optimization and massively parallel RL on TPUs/GPUs. Apache 2.0 licensed.

- **[Isaac Gym](https://github.com/isaac-sim/IsaacGymEnvs)**  
  NVIDIA's precursor to Isaac Lab. GPU-accelerated physics simulation for RL training. Requires NVIDIA GPU. (Now largely superseded by Isaac Lab.)

- **[PyBullet Gym](https://github.com/bulletphysics/bullet3/tree/master/examples/pybullet/gym)**  
  RL environment collection built on PyBullet for robot locomotion and manipulation.

### Additional Strong Open-Source Options

- **[RaiSim](https://github.com/raisimTech/raisimLib)** — Physics engine for robotics with contact-rich simulation. Commercial license for advanced features.
- **[Flexiv RDK Simulator](https://github.com/flexivrobotics)** — Simulation for Flexiv adaptive robots.
- **[RoboSuite](https://github.com/ARISE-Initiative/robosuite)** — Modular simulation framework for robot learning, built on MuJoCo. Used for manipulation benchmarks.
- **[ManiSkill](https://github.com/haosulab/ManiSkill)** — Benchmark and simulation platform for generalizable manipulation skills.
- **[Habitat](https://github.com/facebookresearch/habitat-lab)** — Simulation platform for embodied AI research in photorealistic 3D environments.
- **[AI2-THOR](https://github.com/allenai/ai2thor)** — Interactive 3D environments for visual AI agents.
- **Sim-to-Real Tools** — Domain randomization, SysID, and reality-gap mitigation libraries.
- **Robot Model Libraries** — MuJoCo Menagerie, URDF repositories, and standardized robot descriptions.

**Frameworks for building custom systems**: Combine **MuJoCo** for contact-rich manipulation and RL, **Gazebo** for ROS 2 integration and full-system simulation, **Isaac Sim** for photorealistic perception and synthetic data, **CARLA** for autonomous driving scenarios, and **Drake** for model-based control verification to build a complete robot simulation stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Robot simulation platforms must be validated against real-world behavior before deployment. **Sim-to-real gap remains a fundamental challenge** — simulation success does not guarantee hardware success.
- Self-hosted open-source solutions require proper GPU infrastructure, sensor calibration, and domain randomization strategies.

---

**Made for robotics engineers, RL researchers, autonomous systems developers, and teams building simulation platforms.**  
Let's make robot simulation more open, accurate, and sim-to-real friendly.
