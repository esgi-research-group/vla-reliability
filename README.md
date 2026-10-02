# Is Success All You Need? Investigating the Impact of Input Perturbations on VLA Behaviour in Tabletop Manipulation Tasks

## Overview

ArXiv preprint: (https://arxiv.org/abs/2610.01351)

> [!WARNING]
> The manuscript is under review, and the source code and reproduction details will be released after publication.

## Paper Abstract

Vision-Language-Action (VLA) models have achieved high task success rates on robot manipulation task benchmarks. More recently, there has been an emphasis on evaluating the *robustness* of VLA models to perturbations. However, this robustness is still predominantly measured through Task Success Rate (TSR). In this work, we propose a benchmark-agnostic evaluation framework to measure the *behavioural* robustness of models by characterising how *successful* trajectories are executed under perturbation. We implement this methodology by extending the widely-used LIBERO and LIBERO-Plus benchmarks. Across three state-of-the-art VLA models, four LIBERO task suites and seven perturbation conditions, we evaluate changes in both typical successful behaviour and its variability, including metrics of motion smoothness, efficiency and gripper behaviour. We find that perturbations can alter the behaviour of *successful* trajectories, a phenomenon which cannot necessarily be inferred from TSR alone. Across LIBERO suites, we identify cases where state-of-the-art VLA models achieve comparable TSR under the same perturbation condition, yet behaviour on successful trajectories diverges substantially. Therefore, to have a more robust assessment of task performance, we argue that suitable measures of robustness should capture not only whether a task is completed, but also how the robot *behaves* while completing it. When evaluating the robustness of VLA models, TSR may be complemented by *behavioural* evaluation metrics that characterise the nature and variability of successful task execution by robots.

## Citation

```bibtex
@misc{higham2026successneedinvestigatingimpact,
      title={Is Success All You Need? Investigating the Impact of Input Perturbations on VLA Behaviour in Tabletop Manipulation Tasks}, 
      author={Sophie Higham and Riccardo Andrea Izzo and Matteo Matteucci and Alessandro Suglia},
      year={2026},
      journal={arXiv preprint arXiv:2610.01351},
      url={https://arxiv.org/abs/2610.01351}, 
}
```

## Acknowledgement

This project builds on **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**, **[LIBERO-Plus](https://github.com/sylvestf/LIBERO-plus)** and the **[vla-eval](https://github.com/allenai/vla-evaluation-harness)** harness. We thank the teams involved for their contributions to the robotics community.

