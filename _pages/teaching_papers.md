---
layout: page
permalink: /teaching/papers/
title: Project papers
description: Research papers for the MVA Robotics article study.
nav: false
---

This page lists the research papers for the article study of the [MVA Robotics class](/teaching/). The study accounts for 75% of the final grade and can be completed individually or in pairs. You will need to select three papers from the list below, ranked by preference. Each paper can be studied by at most two projects, and papers are assigned on a first-come, first-served basis. You are expected to understand your paper, then either reimplement it or try extending it. The work is presented through a poster and a report:

- **Poster:** A1 format, presented at the poster session on **3 December 2026, 09:00–12:00** at [Inria Paris, 48 rue Barrault](https://www.google.com/maps/search/?api=1&query=Inria+Paris+48+rue+Barrault+75013+Paris). Tip: you can easily print an A1 poster on eight A4 sheets and tape them together.
- **Report:** 5–8 pages, due by **18 December 2026**. We will provide a LaTeX template.

**Sending your choice:** please email your three ranked papers to [justin.carpentier@inria.fr](mailto:justin.carpentier@inria.fr), [yann.dubois-de-mont-marin@inria.fr](mailto:yann.dubois-de-mont-marin@inria.fr) and [theotime.le-hellard@inria.fr](mailto:theotime.le-hellard@inria.fr) by **Monday 9 November 2026**, using the template below. Pairs only need to send one email.

```text
To: justin.carpentier@inria.fr, yann.dubois-de-mont-marin@inria.fr, theotime.le-hellard@inria.fr
Subject: [MVA Robotics] Paper choice - <last name(s)>

Hello,

Here is my/our paper choice for the MVA Robotics article study.

Project members (one or two):
- <first name> <last name>, <email>
- <first name> <last name>, <email>

Ranked papers (number and title from the list):
1. <first choice>
2. <second choice>
3. <third choice>

Best regards,
<name(s)>
```

The papers are grouped by topic. Short introductions place each group in context and can help you find a subject that interests you.

### Motion planning and optimal control

How can a robot compute motions that avoid obstacles, satisfy an objective, and make use of contact? These papers represent several approaches: convex optimization over a graph of collision-free regions, sampling-based planning with a focused search, sampling-based model predictive control applied directly to torque-level locomotion, hierarchical quadratic programming for online humanoid motion generation, and optimization and inverse-dynamics methods that reason directly about contact. They build on the motion planning and optimal control sessions of the class.

<ol>
  <li><a href="https://arxiv.org/abs/2205.04422">Motion Planning around Obstacles with Convex Optimization</a></li>
  <li><a href="https://arxiv.org/abs/2409.15610">Full-Order Sampling-Based MPC for Torque-Level Locomotion Control via Diffusion-Style Annealing</a></li>
  <li><a href="https://arxiv.org/abs/1404.2334">Informed RRT*: Optimal Sampling-based Path Planning Focused via Direct Sampling of an Admissible Ellipsoidal Heuristic</a></li>
  <li><a href="https://hal.science/hal-00751924/document">Hierarchical quadratic programming: Fast online humanoid-robot motion generation</a></li>
  <li><a href="https://roboti.us/lab/papers/MordatchSIGGRAPH12.pdf">Discovery of complex behaviors through contact-invariant optimization</a></li>
  <li><a href="https://hal.science/hal-05201780v3/file/Frictional%20Contact-Implicit%20Inverse%20Dynamics.pdf">Frictional Contact-Implicit Inverse Dynamics</a></li>
</ol>

### Simulation, contact and sim-to-real

Simulators let robots be tested and trained safely and at scale, but their results depend on how contact is modeled and solved, and on how well behaviors transfer to the real world. The first two papers focus on contact models and solvers. The others study the transfer of learned controllers to physical robots through dynamics randomization, online adaptation, and the choice of controller gains.

<ol start="7">
  <li><a href="https://arxiv.org/abs/2304.06372">Contact Models in Robotics: a Comparative Analysis</a></li>
  <li><a href="https://arxiv.org/abs/2405.17020">From Compliant to Rigid Contact Simulation: a Unified and Efficient Approach</a></li>
  <li><a href="https://arxiv.org/abs/1710.06537">Sim-to-Real Transfer of Robotic Control with Dynamics Randomization</a></li>
  <li><a href="https://arxiv.org/abs/2107.04034">RMA: Rapid Motor Adaptation for Legged Robots</a></li>
  <li><a href="https://arxiv.org/abs/2604.02523">Tune to Learn: How Controller Gains Shape Robot Policy Learning</a></li>
</ol>

### Reinforcement learning

Reinforcement learning obtains control policies from interaction and reward, but scaling it to high-dimensional robots while keeping it stable remains difficult. This group covers model-based control with world models, scalable network architectures and fast off-policy algorithms, as well as settings that go beyond standard online reinforcement learning: skill discovery without a reward function, offline learning, and goal-conditioned learning.

<ol start="12">
  <li><a href="https://arxiv.org/abs/2310.16828">TD-MPC2: Scalable, Robust World Models for Continuous Control</a></li>
  <li><a href="https://arxiv.org/abs/2410.09754">SimBa: Simplicity Bias for Scaling Up Parameters in Deep Reinforcement Learning</a></li>
  <li><a href="https://arxiv.org/abs/2604.04539">FlashSAC: Fast and Stable Off-Policy Reinforcement Learning for High-Dimensional Robot Control</a></li>
  <li><a href="https://arxiv.org/abs/1802.06070">Diversity is All You Need: Learning Skills without a Reward Function</a></li>
  <li><a href="https://arxiv.org/abs/2512.03973">Guided Flow Policy: Learning from High-Value Actions in Offline Reinforcement Learning</a></li>
  <li><a href="https://arxiv.org/abs/2604.17551">SVL: Goal-Conditioned Reinforcement Learning as Survival Learning</a></li>
  <li><a href="https://arxiv.org/abs/2506.08902">Intention-Conditioned Flow Occupancy Models</a></li>
</ol>

### Imitation learning

Imitation learning trains policies from demonstrations instead of a hand-designed reward. Several of these papers use generative models, particularly diffusion, to represent actions, and explore 3D scene representations, faster inference, and refinement through policy optimization. Others address low-cost bimanual manipulation, open and scalable behavior cloning, and what actually makes generative control effective.

<ol start="19">
  <li><a href="https://arxiv.org/abs/2303.04137">Diffusion Policy: Visuomotor Policy Learning via Action Diffusion</a></li>
  <li><a href="https://arxiv.org/abs/2304.13705">Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware</a></li>
  <li><a href="https://arxiv.org/abs/2403.03954">3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations</a></li>
  <li><a href="https://arxiv.org/abs/2605.21414">PointACT: Vision-Language-Action Models with Multi-Scale Point-Action Interaction</a></li>
  <li><a href="https://arxiv.org/abs/2512.01809">Much Ado About Noising: Dispelling the Myths of Generative Robotic Control</a></li>
  <li><a href="https://arxiv.org/abs/2606.27375">Scalable Behavior Cloning with Open Data, Training, and Evaluation</a></li>
  <li><a href="https://roboticsconference.org/2026/program/papers/160/">Muninn: Your Trajectory Diffusion Model But Faster</a></li>
  <li><a href="https://arxiv.org/abs/2409.00588">Diffusion Policy Policy Optimization</a></li>
</ol>

### Benchmarks, bigger models and world models

As robot learning moves toward general-purpose systems, it needs larger models and shared ways to evaluate them. This group covers vision–language–action models and action tokenization, general-purpose reward models, benchmarks for robot learning and manipulation, and world models that learn from visual observations to support planning.

<ol start="27">
  <li><a href="https://arxiv.org/abs/2603.02115">Robometer: Scaling General-Purpose Robotic Reward Models via Trajectory Comparisons</a></li>
  <li><a href="https://arxiv.org/abs/2504.16054">π<sub>0.5</sub>: a Vision-Language-Action Model with Open-World Generalization</a></li>
  <li><a href="https://arxiv.org/abs/2501.09747">FAST: Efficient Action Tokenization for Vision-Language-Action Models</a></li>
  <li><a href="https://arxiv.org/abs/2306.03310">LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning</a></li>
  <li><a href="https://arxiv.org/abs/2607.04434">RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies</a></li>
  <li><a href="https://arxiv.org/abs/2603.19312">LeWorldModel: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels</a></li>
  <li><a href="https://arxiv.org/abs/2411.04983">DINO-WM: World Models on Pre-trained Visual Features enable Zero-shot Planning</a></li>
</ol>

### Humanoids and physics-based characters

Producing natural, versatile whole-body motion is a shared challenge for humanoid robotics and physics-based character animation. These papers combine reference motions with reinforcement learning, through motion tracking, adversarial motion priors, reusable skill embeddings, and masked motion inpainting, and extend these ideas to whole-body humanoid locomotion.

<ol start="34">
  <li><a href="https://arxiv.org/abs/1804.02717">DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills</a></li>
  <li><a href="https://arxiv.org/abs/2104.02180">AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control</a></li>
  <li><a href="https://arxiv.org/abs/2205.01906">ASE: Large-Scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters</a></li>
  <li><a href="https://arxiv.org/abs/2604.17335">Learning Whole-Body Humanoid Locomotion via Motion Generation and Motion Tracking</a></li>
  <li><a href="https://arxiv.org/abs/2409.14393">MaskedMimic: Unified Physics-Based Character Control Through Masked Motion Inpainting</a></li>
</ol>
