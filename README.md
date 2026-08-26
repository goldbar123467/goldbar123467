# Clark Kitchen

**Computer science teacher, CS master's student, and ML systems builder**

I build measurable AI systems: reinforcement-learning agents, benchmark harnesses, simulation tooling, and GPU-backed ML workflows. I care about reproducible runs, honest baselines, and artifacts that other people can test.

My research direction is high-performance reinforcement learning at the algorithm-systems boundary: PPO-family methods, self-play, GPU-efficient environments, and CUDA optimization.

## Featured work

### [PPO Checkers](https://github.com/goldbar123467/PPO-Checkers)

An end-to-end PPO self-play system for American checkers, covering the rules engine, vectorized training, checkpoint evaluation, model export, and a deployed neural opponent.

- **470,410-parameter** residual policy/value network
- **50,331,648** training transitions on an RTX 5070
- Selected checkpoint: **354 wins, 70 draws, 8 losses** against the project's Minimax-2 baseline across 432 color-balanced games
- [Play the trained policy](https://checkers.upsidedownatlas.com)

### [ptcg-meta-bench](https://github.com/goldbar123467/ptcg-meta-bench)

A local, meta-weighted benchmark harness for Pokemon TCG AI Battle agents. It runs the official Kaggle engine against a weighted 10-deck panel and exposes the workflow through CLI, JSON, and MCP interfaces.

### [NeuroGolf Lab](https://github.com/goldbar123467/GolfWebGUI)

A browser-based ARC task viewer and visual ONNX graph editor. Human solvers and headless agents use the same backend compilation and ONNX Runtime validation gate.

### [Biohub Cell Tracking Library](https://github.com/goldbar123467/biohub-celltracking-lib)

A reproducible Kaggle competition library with lazy Zarr/GEFF access, offline inference tooling, metric probes, and exact submission-schema validation.

## Research

### [From Static Prompts to Agentic Ranges: A Taxonomy of LLM Cybersecurity Benchmarks](research/from-static-prompts-to-agentic-ranges.pdf)

**Graduate literature review | July 2026 | 93%**

This paper develops a three-dimensional taxonomy for comparing LLM cybersecurity benchmarks: **construct and model role**, **elicitation system**, and **validity controls**. It examines how scaffolding turns some benchmarks into system-level tests, and how contamination, judge choice, and task design limit direct score comparisons.

Instructor evaluation: **strongest literature review in the cohort**.

## Current questions

- How can PPO self-play systems become more sample-efficient and compute-efficient?
- Which environment operations belong on the GPU, and when do custom CUDA kernels justify their complexity?
- How should evaluations separate base-model capability from scaffolding, tools, and judges?
- How can research-grade AI systems become meaningful computer science learning experiences?

## Teaching

I teach computer science while completing my master's degree. I use games, simulation, reinforcement learning, and local AI systems to make abstract ideas visible and testable for students.

## Technical areas

Python · PyTorch · CUDA workflows · C/C++ · ONNX · FastAPI · React/TypeScript · Linux/WSL2 · Kaggle · Weights & Biases

## Elsewhere

- [Hugging Face](https://huggingface.co/clarkkitchen22)
- [LinkedIn](https://www.linkedin.com/in/clark-kitchen-37540219b/)
