<p align="center"><img src="assets/ssrobotics-logo.jpg" alt="SSRobotics — original logo by SSRobotic" width="240"></p>

<h1 align="center">🌐 Simulation</h1>
<p align="center"><b>SSRobotics · Source Code Collection</b></p>

<p align="center">
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Resources-7-f28c28?style=flat-square" alt="7 curated resources"></a>
  <a href="https://ssrobotic.github.io/humanoid-robot-hub/"><img src="https://img.shields.io/badge/Language-TH_%2F_EN-555555?style=flat-square" alt="Thai and English"></a>
  <a href="https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CREDITS.md"><img src="https://img.shields.io/badge/Original_sources-Credited-555555?style=flat-square" alt="Original authors credited"></a>
</p>


**Part of [Humanoid Robot Hub](https://github.com/SSRobotic/humanoid-robot-hub)** · [🔎 Search all resources](https://ssrobotic.github.io/humanoid-robot-hub/)

Physics engines, simulator integrations and humanoid simulation workflows.

เอนจินฟิสิกส์และระบบจำลองสำหรับงาน Humanoid

Curated by **SSRobotic — Robotics Engineer & Open-source Curator**. This repository is a focused resource directory and engineering guide. Linked SDKs, models and research implementations belong to their original creators.

## 🗂️ Resource directory

| Resource | What it provides | Keywords | Original source |
| --- | --- | --- | --- |
| [Unitree MuJoCo](https://github.com/unitreerobotics/unitree_mujoco) | Unitree simulator with C++ / Python implementations and robot MJCF models; focused on low-level controller development. | G1, H1, MuJoCo | [unitreerobotics](https://github.com/unitreerobotics/unitree_mujoco) |
| [Isaac Lab](https://github.com/isaac-sim/IsaacLab) | Framework for robot learning built on Isaac Sim, with environments and training integrations. | RL, Simulation, Isaac Sim | [isaac-sim](https://github.com/isaac-sim/IsaacLab) |
| [MuJoCo](https://github.com/google-deepmind/mujoco) | Physics simulation engine for robotics and control research. Robot-specific setup comes from model and task repositories. | Physics, Python, C++ | [google-deepmind](https://github.com/google-deepmind/mujoco) |
| [TienKung Lab](https://github.com/Open-X-Humanoid/TienKung-Lab) | Isaac Lab workflows for legged-robot learning, including TienKung. | TienKung, RL, Isaac Lab | [Open-X-Humanoid](https://github.com/Open-X-Humanoid/TienKung-Lab) |
| [X-Humanoid VLA Benchmark](https://github.com/Open-X-Humanoid/x-humanoid-vla-simulation-benchmark) | Isaac Sim resources for evaluating vision-language-action policies. | VLA, Benchmark, Isaac Sim | [Open-X-Humanoid](https://github.com/Open-X-Humanoid/x-humanoid-vla-simulation-benchmark) |
| [Isaac Sim](https://github.com/isaac-sim/IsaacSim) | Robot simulation on NVIDIA Omniverse, with physics, sensor simulation and robot integration. | Isaac Sim, USD, RTX | [isaac-sim](https://github.com/isaac-sim/IsaacSim) |
| [Isaac Sim ROS Workspaces](https://github.com/isaac-sim/IsaacSim-ros_workspaces) | ROS workspace packages for Isaac Sim integration; check the supported ROS distribution upstream. | Isaac Sim, ROS 2, Integration | [isaac-sim](https://github.com/isaac-sim/IsaacSim-ros_workspaces) |

## 📦 Code & models in this repository

**718 tracked upstream files** — เปิดโฟลเดอร์ด้านล่างเพื่อดูโค้ดจริง โมเดล และตัวอย่างต้นฉบับ

| Project files | Files | Pinned source | License / notices |
| --- | ---: | --- | --- |
| [unitreerobotics/unitree_mujoco](projects/unitree_mujoco) | 718 | [`1eb6642e3f3f`](https://github.com/unitreerobotics/unitree_mujoco/tree/1eb6642e3f3fdfb7fb13a9794fd6a2dd93ea0e7d) | [LICENSE](projects/unitree_mujoco/LICENSE) |

[Source manifest](source-manifest.json) records commits, file counts, Git LFS pointers and external submodules. [Per-file manifests](source-manifests/) record original Git blob hashes. `projects/` keeps upstream code, README files, licenses and notices; SSRobotics supplies the organization and guides.

```bash
git clone --depth 1 https://github.com/SSRobotic/humanoid-simulation.git
cd humanoid-simulation
```

Open the imported project README for its dependencies, build instructions and supported robot/simulator versions. Each snapshot is collected independently; these projects have not been validated as one combined runnable stack.

The upstream Go2W assets include `terrain.STL` and `terrain.stl` as distinct paths. Both original Git blobs are preserved. Use a case-sensitive checkout (for example Linux) when you need that exact upstream asset layout.

## 🚀 Start here

1. Choose a simulator supported by your robot model and controller.
2. Match the source project’s simulator version, dependencies and GPU requirements.
3. Start with its documented example scene and inspect the initial state before adding a policy.

Read the [engineering guide](GUIDE.md) for a practical selection checklist. [resources.json](resources.json) contains the structured entries.

## 🔗 Explore the ecosystem

<details>
<summary>🌐 Browse all 14 categories</summary>

[🦾 Models & URDF](https://github.com/SSRobotic/humanoid-models) · [🌐 Simulation](https://github.com/SSRobotic/humanoid-simulation) · [🧠 Robot Learning](https://github.com/SSRobotic/humanoid-robot-learning) · [⚙️ Whole-body Control](https://github.com/SSRobotic/humanoid-whole-body-control) · [👁️ Vision & 3D Perception](https://github.com/SSRobotic/humanoid-vision) · [🤏 Manipulation & Planning](https://github.com/SSRobotic/humanoid-manipulation) · [🎮 Teleoperation](https://github.com/SSRobotic/humanoid-teleoperation) · [💾 Datasets & Demonstrations](https://github.com/SSRobotic/humanoid-datasets) · [💬 Vision-Language-Action](https://github.com/SSRobotic/humanoid-vla) · [🔌 Hardware & SDKs](https://github.com/SSRobotic/humanoid-hardware-sdks) · [📡 ROS & Integration](https://github.com/SSRobotic/humanoid-ros2) · [📚 Research & Benchmarks](https://github.com/SSRobotic/humanoid-research) · [🟢 Isaac Sim & Isaac Lab](https://github.com/SSRobotic/humanoid-isaac-sim) · [🧮 Robotics Algorithms](https://github.com/SSRobotic/humanoid-algorithms)

</details>

[🏠 Main Hub](https://github.com/SSRobotic/humanoid-robot-hub) · [🤖 Profile](https://github.com/SSRobotic)

## 🙌 Help this collection grow

⭐ [Star the Hub](https://github.com/SSRobotic/humanoid-robot-hub) · 👤 [Follow SSRobotic](https://github.com/SSRobotic) · 💡 [Suggest a resource](https://github.com/SSRobotic/humanoid-robot-hub/issues/new/choose)

Contribute accurate descriptions and original source links through the [Hub contribution guide](https://github.com/SSRobotic/humanoid-robot-hub/blob/main/CONTRIBUTING.md). Source terms, model compatibility and dataset access conditions remain with each upstream project.
