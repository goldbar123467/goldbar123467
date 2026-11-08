# Clark Kitchen

**Computer Science & Robotics teacher · CS master's student at Ball State University · ML systems builder**

Hello! I am a Computer Science and Robotics teacher at an elementary/middle school in the United States. My main goal as a teacher is to instill in my students the love and passion for computer science that I have. Outside of the classroom, I am working on my Master's in Computer Science at Ball State University. In my free time I enjoy competing in Kaggle competitions and working on independent machine learning projects. Below you will find some of my research papers and projects, along with my other work.

## About me

I build measurable AI systems: reinforcement-learning agents, benchmark harnesses, simulation tooling, and GPU-backed ML workflows. I care about reproducible runs, honest baselines, and artifacts that other people can test.

My research direction is high-performance reinforcement learning at the algorithm-systems boundary: PPO-family methods, self-play, GPU-efficient environments, and CUDA optimization.

## Research

### [Training Time? Search versus Self-Play PPO Agent in Checkers](research/training-time-search-vs-self-play-ppo-checkers.pdf)

**Research proposal | CS 681 | October 2026 | 100%**

Is it cheaper to train a neural network once, or to search deeper on every move? This proposal measures the exchange rate between training compute and search compute in checkers. A self-play PPO agent's value head replaces the material-count evaluation inside alpha-beta search, and nine log-spaced checkpoints (0.2M to 50.3M self-play transitions) are each matched against a fixed opponent to find the smallest search budget that reaches a target score. Fitting `log10 n_S*(C) = α − β log10 C` gives the exchange rate `β`, with uncertainty from 1,000 bootstrap resamples of the openings.

Preliminary results: the selected checkpoint scores **0.9005** against Minimax-2 (354 wins, 70 draws, 8 losses over 432 color-balanced games) and **432/0/0** against a random player.

**Full research paper coming soon.**

### [Math Door to Door: The Traveling Salesperson Problem](research/math-door-to-door-traveling-salesperson-problem.pdf)

**CS 681 Applications of Computability | September 2026 | Peer reviewed**

This paper traces how approaches to the NP-hard Traveling Salesperson Problem have evolved: from brute-force enumeration of all `(n − 1)!/2` symmetric tours, to pruning and heuristics that shrink the search space, to a 2026 quantum iterative approach built on Quantum Phase Estimation and Grover-style amplitude amplification.

### [Subsequences, Universality, and the Arch Factorization](research/subsequences-universality-arch-factorization.pdf)

**Reflective essay | Peer reviewed**

This essay builds from strings and subsequences to arch factorization and the universality index `ι(w)`: a word that factors into `k` arches contains every length-`k` word over its alphabet as a subsequence. Worked examples show `SHSSOOHS` factoring as `SHSSO | OHS` with `ι(w) = 2`, and show that `osso` and `osos` are equivalent up to length 2 but separated at length 3 by the witness `sso`.

### [From Static Prompts to Agentic Ranges: A Taxonomy of LLM Cybersecurity Benchmarks](research/from-static-prompts-to-agentic-ranges.pdf)

**Graduate literature review | July 2026 | 93%**

This paper develops a three-dimensional taxonomy for comparing LLM cybersecurity benchmarks: **construct and model role**, **elicitation system**, and **validity controls**. It examines how scaffolding turns some benchmarks into system-level tests, and how contamination, judge choice, and task design limit direct score comparisons.

Instructor evaluation: **strongest literature review in the cohort**.

## Featured work

### [PPO Checkers](https://github.com/goldbar123467/PPO-Checkers)

An end-to-end PPO self-play system for American checkers, covering the rules engine, vectorized training, checkpoint evaluation, model export, and a deployed neural opponent. It is the trained agent behind the checkers research proposal above.

- **470,410-parameter** residual policy/value network
- **50,331,648** training transitions on an RTX 5070
- Selected checkpoint: **354 wins, 70 draws, 8 losses** against the project's Minimax-2 baseline across 432 color-balanced games
- [Play the trained policy](https://checkers.upsidedownatlas.com)

### [NeuroGolf Lab](https://github.com/goldbar123467/GolfWebGUI)

A browser-based ARC task viewer and visual ONNX graph editor. Human solvers and headless agents use the same backend compilation and ONNX Runtime validation gate.

## Kaggle

I have entered 20 Kaggle competitions. Final leaderboard placements:

### Research, featured, and simulation competitions

| Competition | Type | Rank | Top % |
| --- | --- | ---: | ---: |
| The 2026 NeuroGolf Championship | Research | 692 / 2,963 | 23.4% |
| Orbit Wars | Featured · Simulation | 998 / 4,729 | 21.1% |
| BirdCLEF+ 2026 | Research · Code | 1,133 / 4,094 | 27.7% |
| Biohub - Cell Tracking During Development | Research · Code | 1,411 / 3,947 | 35.7% |
| The Pokémon Company - PTCG AI Battle Challenge Simulation | Featured · Simulation | 2,779 / 6,807 | 40.8% |
| ROGII - Wellbore Geology Prediction | Featured · Code | 3,351 / 6,125 | 54.7% |
| Kaggriculture | Featured · Simulation | 4,277 / 10,148 | 42.1% |

### Playground competitions

| Competition | Type | Rank | Top % |
| --- | --- | ---: | ---: |
| Predicting Smartphone Addiction | Playground Series S6E8 | **110 / 3,531** | **3.1%** |
| Predicting Electric Vehicle Purchases | Playground Series S6E9 | 565 / 3,575 | 15.8% |
| Maze Crawler | Playground · Simulation | 117 / 459 | 25.5% |
| Predicting Airline Satisfaction | Playground Series S6E10 | 1,128 / 3,734 | 30.2% |
| Predicting Student Test Scores | Playground Series S6E1 | 1,360 / 4,317 | 31.5% |
| Predicting Student Health Risk | Playground Series S6E7 | 1,343 / 3,355 | 40.0% |
| Predicting F1 Pit Stops | Playground Series S6E5 | 1,324 / 3,022 | 43.8% |
| Predicting Stellar Class | Playground Series S6E6 | 1,251 / 2,816 | 44.4% |
| Autonomous Agent Prediction (Beta) | Playground | 562 / 570 | 98.6% |

## Teaching

I use games, simulation, robotics, reinforcement learning, and local AI systems to make abstract ideas visible and testable for students.

## Technical areas

Python · PyTorch · CUDA workflows · C/C++ · ONNX · FastAPI · React/TypeScript · Linux/WSL2 · Kaggle · Weights & Biases

## Elsewhere

- [Hugging Face](https://huggingface.co/clarkkitchen22)
- [LinkedIn](https://www.linkedin.com/in/clark-kitchen-37540219b/)
