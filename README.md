# AI Habitat (ai-habitat)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
