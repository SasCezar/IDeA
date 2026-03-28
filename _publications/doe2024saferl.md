---
layout: publication
title: "Constrained Policy Optimization with Adaptive Safety Boundaries"
authors:
  - Jane Doe
  - John Smith
venue: NeurIPS 2024
year: 2024
type: conference
abstract: >
  We propose an adaptive constraint-tightening scheme for safe reinforcement
  learning that reduces constraint violations during training by 60% compared
  to state-of-the-art baselines while preserving task performance.
pdf: https://arxiv.org/abs/2401.00000
code: https://github.com/idea-group/safe-rl
arxiv: "2401.00000"
doi:
tags:
  - Reinforcement Learning
  - Safety
plotly: false
---

## Key Contributions

- An adaptive Lagrange multiplier schedule that tightens safety constraints as training progresses
- A safety critic architecture that predicts future constraint violations with 85% accuracy
- Empirical validation across six Safety-Gym benchmarks and a physical manipulator

## Method Overview

```mermaid
graph LR
    S[State] --> AC[Actor-Critic]
    AC --> A[Action]
    A --> ENV[Environment]
    ENV -->|reward, cost| AC
    AC --> LAG[Adaptive\nLagrangian]
    LAG -->|constraint weight| AC
```

## BibTeX

```bibtex
@inproceedings{doe2024saferl,
  title     = {Constrained Policy Optimization with Adaptive Safety Boundaries},
  author    = {Doe, Jane and Smith, John},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2024}
}
```
