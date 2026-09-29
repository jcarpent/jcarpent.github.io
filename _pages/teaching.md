---
layout: page
permalink: /teaching/
title: Teaching
description: Materials for the MVA Robotics class.
nav: true
nav_order: 6
---

## Robotics — Master MVA

The robotics class in the [MVA master's program](https://www.master-mva.com/) explores how modeling, optimization, machine learning, and computer vision enable robots to perceive their surroundings and act in the physical world. It connects the mathematical foundations of robotics with practical exercises using robotics software, including [Pinocchio](https://github.com/stack-of-tasks/pinocchio).

The teaching team brings together Justin Carpentier, [Yann Dubois De Mont Marin](https://ymontmarin.github.io/), [Silvère Bonnabel](https://sites.google.com/view/silvere-bonnabel/), and [Pierre-Brice Wieber](https://scholar.google.com/citations?user=zSSrBp4AAAAJ), with [Théotime Le Hellard](https://theotimelh.github.io/) as teaching assistant.

### Course overview

The class covers nine complementary topics, connecting the mathematical foundations of robot motion with perception, learning, and responsible deployment:

1. **Introduction to robotics (J. Carpentier):** an overview of robotic systems, their applications, and the challenges of interacting with the physical world. We introduce robot modeling, dynamical systems, and feedback control as the foundations for perception and action.
2. **Kinematics (Y. de Mont-Marin):** representing the configuration and motion of articulated robots using rotations, rigid transformations, and velocities. Forward and inverse kinematics, Jacobians, and task-space descriptions connect joint motions to end-effector objectives.
3. **Robot dynamics and simulation (J. Carpentier):** understanding how forces and torques generate motion. Topics include rigid-body dynamics, forward and inverse dynamics, contact and friction, and numerical integration for simulating robot–environment interactions.
4. **Motion planning (Y. de Mont-Marin):** finding collision-free motions subject to geometric and kinematic constraints. We study configuration spaces, collision checking, and sampling-based methods such as probabilistic roadmaps (PRM) and rapidly exploring random trees (RRT), with applications to navigation and manipulation.
5. **Optimal control and optimization (J. Carpentier):** computing motions and control inputs that minimize an objective while respecting system dynamics and constraints. We connect numerical optimization with trajectory optimization, differential dynamic programming, and model predictive control for feedback-based execution.
6. **Reinforcement learning for robotics (J. Carpentier and T. Le Hellard):** learning control policies through interaction and reward. Topics include policy and value functions, policy optimization, reward design, and the challenges of transferring policies from simulation to physical robots, including robustness and domain randomization.
7. **Perception and estimation (S. Bonnabel):** estimating a robot's state and surroundings from noisy sensor measurements. We introduce sensor fusion, Kalman and extended Kalman filtering, and their use in localization, visual–inertial odometry, and simultaneous localization and mapping (SLAM).
8. **Responsible robotics (P.-B. Wieber):** examining the ethical responsibilities of robotics research and deployment. Discussions address human oversight, safety and robustness, accountability, and the societal and environmental consequences of autonomous systems.
9. **World models and vision–language–action models (J. Carpentier and T. Le Hellard):** learning predictive models of the environment and policies that connect visual observations and language instructions to robot actions. We discuss how world models can support planning, how vision–language–action (VLA) models can support instruction following, and the challenges of generalization, physical grounding, and evaluation.

### Class locations and schedule

Classes will take place mainly at **[Mines de Paris][mines-map]**, from **09:00 to 12:00 (Paris time)** on the dates below. The session on 10 December will take place at the **[Maison des Mines, rue Saint-Jacques][maison-map]**. Rooms with limited seating are marked in the table; the other rooms are larger.

| Date (2026) | Time (Paris)    | Room       | Location                                          | Capacity / notes                             |
| ----------- | --------------- | ---------- | ------------------------------------------------- | -------------------------------------------- |
| 1 October   | 09:00–12:00     | L106       | [Mines de Paris][mines-map]                       | **Limited: 48 seats**                        |
| 8 October   | 09:00–12:00     | L108_B     | [Mines de Paris][mines-map]                       |                                              |
| 15 October  | 09:00–12:00     | L109       | [Mines de Paris][mines-map]                       |                                              |
| 22 October  | 09:00–12:00     | L109       | [Mines de Paris][mines-map]                       |                                              |
| 5 November  | To be confirmed |            | To be confirmed                                   | **Alternative arrangements to be confirmed** |
| 12 November | 09:00–12:00     | FORGE_haut | [Mines de Paris][mines-map]                       | **Limited: 48 seats**; directions below      |
| 19 November | 09:00–12:00     | L106       | [Mines de Paris][mines-map]                       | **Limited: 48 seats**                        |
| 26 November | 09:00–12:00     | FORGE_haut | [Mines de Paris][mines-map]                       | **Limited: 48 seats**; directions below      |
| 3 December  | 09:00–12:00     | L117       | [Mines de Paris][mines-map]                       | **Limited: 46 seats**                        |
| 10 December | 09:00–12:00     | MDM_F      | [Maison des Mines, rue Saint-Jacques][maison-map] | **Limited: 48 seats**                        |

[mines-map]: https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris
[maison-map]: https://www.google.com/maps/search/?api=1&query=Maison+des+Mines+rue+Saint-Jacques+Paris

**Directions to FORGE_haut:** turn left after reception and continue to the far end, walking parallel to boulevard Saint-Michel. Go down the stairs, then continue in the same direction; the room is on your right.

### Materials and assessment

In that edition, homework accounted for 20% of the grade; a project or research article study, completed in pairs and presented through a report and poster, accounted for 80%.
