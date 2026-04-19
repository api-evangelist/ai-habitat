# AI Habitat (ai-habitat)

AI Habitat is an open-source simulation platform from Meta AI Research for embodied AI research. It provides high-performance 3D simulated environments for training and evaluating AI agents on navigation, manipulation, and human-robot collaboration tasks. Habitat-Sim delivers 10,000+ FPS simulation and Habitat-Lab provides a modular library for defining tasks, training agents, and running benchmarks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ai-habitat/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Artificial Intelligence, Simulation, Embodied AI, Robotics, Computer Vision, Reinforcement Learning, Machine Learning, Open Source, Research

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-04-19

## APIs

### AI Habitat
AI Habitat simulation framework for embodied AI research, including Habitat-Sim (high-performance 3D simulator) and Habitat-Lab (modular training library). Supports navigation, manipulation, and human-robot collaboration tasks across photorealistic 3D indoor environments.

**Human URL:** [https://aihabitat.org/](https://aihabitat.org/)

#### Tags:

 - Embodied AI, Simulation, Robotics, Python, Computer Vision, Reinforcement Learning

#### Properties

- [Documentation](https://aihabitat.org/)
- [API Documentation](https://aihabitat.org/docs/)
- [Habitat-Sim GitHub](https://github.com/facebookresearch/habitat-sim)
- [Habitat-Lab GitHub](https://github.com/facebookresearch/habitat-lab)
- [Habitat-Sim Python Package](https://pypi.org/project/habitat-sim/)
- [Habitat-Lab Python Package](https://pypi.org/project/habitat-lab/)

## Common Properties

- [AI Habitat GitHub Organization](https://github.com/facebookresearch)
- [Habitat-Sim Repository](https://github.com/facebookresearch/habitat-sim)
- [Habitat-Lab Repository](https://github.com/facebookresearch/habitat-lab)
- [Habitat Documentation](https://aihabitat.org/docs/)
- [Habitat Challenge](https://aihabitat.org/challenge/)
- [Habitat Discussions](https://github.com/facebookresearch/habitat-lab/discussions)
- [Habitat HuggingFace](https://huggingface.co/ai-habitat)
- [Python Package (habitat-sim)](https://pypi.org/project/habitat-sim/)
- [Python Package (habitat-lab)](https://pypi.org/project/habitat-lab/)
- [PARTNR Planner](https://github.com/facebookresearch/partnr-planner)

## Features

| Name | Description |
|------|-------------|
| High-Performance Simulation | Habitat-Sim achieves 10,000+ FPS on a single GPU and 8,000+ steps/second for robot simulation, enabling fast RL training. |
| Photorealistic 3D Environments | Supports HM3D, MatterPort3D, Gibson, Replica, and HSSD datasets with high visual fidelity. |
| Physics-Enabled Simulation | Bullet physics engine integration for realistic object interactions and manipulation tasks. |
| Robot Support via URDF | Configurable robot models including Fetch mobile manipulator, Franka arm, and AlienGo quadruped. |
| Configurable Sensors | RGB, depth, semantic, and egomotion sensors for varied agent perception configurations. |
| Modular Task Framework | Habitat-Lab provides modular task definition, agent configuration, and benchmarking tools. |
| Imitation and Reinforcement Learning | Built-in support for IL and RL training pipelines for embodied AI agents. |
| Human-Robot Collaboration | Habitat 3.0 co-habitat supports humans, avatars, and robots sharing simulated environments. |
| Parallelizable Across Clusters | Designed for large-scale distributed training across GPU clusters. |
| Annual Benchmark Challenge | Habitat Challenge on EvalAI provides standardized evaluation of navigation and manipulation agents. |

## Use Cases

| Name | Description |
|------|-------------|
| Embodied Navigation Research | Train and evaluate AI agents on point-goal, object-goal, and image-goal navigation tasks in 3D environments. |
| Robot Manipulation Research | Develop manipulation skills for pick-and-place, rearrangement, and tool use with simulated robot arms. |
| Human-Robot Collaboration | Research human-robot teaming for household tasks using the PARTNR benchmark and Habitat 3.0. |
| Reinforcement Learning Training | Fast simulation enables RL agents to explore millions of environment steps for policy learning. |
| Dataset Creation and Annotation | Generate synthetic data, annotations, and demonstrations for embodied AI training datasets. |

## Integrations

| Name | Description |
|------|-------------|
| PyTorch | Deep learning framework integration for neural network training and inference. |
| HuggingFace | Datasets and models available on HuggingFace Hub at ai-habitat organization. |
| EvalAI | Habitat Challenge evaluation hosted on EvalAI platform for standardized benchmarking. |
| Conda / conda-forge | Conda package distribution via conda-forge and aihabitat channels. |
| Bullet Physics | Bullet physics engine for realistic rigid-body simulation and manipulation. |
| ROS | Robot Operating System integration for sim-to-real transfer research. |

## Artifacts

Machine-readable schema specifications organized by format.

### JSON Schema

- [ai-habitat-agent-config-schema.json](json-schema/ai-habitat-agent-config-schema.json)
- [ai-habitat-agent-observation-schema.json](json-schema/ai-habitat-agent-observation-schema.json)
- [ai-habitat-episode-schema.json](json-schema/ai-habitat-episode-schema.json)
- [ai-habitat-navigation-goal-schema.json](json-schema/ai-habitat-navigation-goal-schema.json)
- [ai-habitat-observation-schema.json](json-schema/ai-habitat-observation-schema.json)
- [ai-habitat-sensor-spec-schema.json](json-schema/ai-habitat-sensor-spec-schema.json)
- [ai-habitat-simulator-config-schema.json](json-schema/ai-habitat-simulator-config-schema.json)
- [ai-habitat-task-config-schema.json](json-schema/ai-habitat-task-config-schema.json)

### JSON Structure

- [ai-habitat-agent-config-structure.json](json-structure/ai-habitat-agent-config-structure.json)
- [ai-habitat-agent-observation-structure.json](json-structure/ai-habitat-agent-observation-structure.json)
- [ai-habitat-episode-structure.json](json-structure/ai-habitat-episode-structure.json)
- [ai-habitat-navigation-goal-structure.json](json-structure/ai-habitat-navigation-goal-structure.json)
- [ai-habitat-observation-structure.json](json-structure/ai-habitat-observation-structure.json)
- [ai-habitat-sensor-spec-structure.json](json-structure/ai-habitat-sensor-spec-structure.json)
- [ai-habitat-simulator-config-structure.json](json-structure/ai-habitat-simulator-config-structure.json)
- [ai-habitat-task-config-structure.json](json-structure/ai-habitat-task-config-structure.json)

### JSON-LD

- [ai-habitat-context.jsonld](json-ld/ai-habitat-context.jsonld)

### Examples

- [ai-habitat-agent-config-example.json](examples/ai-habitat-agent-config-example.json)
- [ai-habitat-agent-observation-example.json](examples/ai-habitat-agent-observation-example.json)
- [ai-habitat-episode-example.json](examples/ai-habitat-episode-example.json)
- [ai-habitat-navigation-goal-example.json](examples/ai-habitat-navigation-goal-example.json)
- [ai-habitat-observation-example.json](examples/ai-habitat-observation-example.json)
- [ai-habitat-sensor-spec-example.json](examples/ai-habitat-sensor-spec-example.json)
- [ai-habitat-simulator-config-example.json](examples/ai-habitat-simulator-config-example.json)
- [ai-habitat-task-config-example.json](examples/ai-habitat-task-config-example.json)

## Vocabulary

- [AI Habitat Vocabulary](vocabulary/ai-habitat-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 5 actions, 1 workflow, and 2 personas across simulation and embodied AI task dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
