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

Please [subscribe to the course mailing list](https://sympa.inria.fr/sympa/subscribe/robotics-mva26) to receive announcements and updates about the class.

The tutorials are available in [this repository](https://github.com/TheotimeLH/2026_MVA_Robotics_Exercises).

### Course overview

The class covers nine complementary topics, connecting the mathematical foundations of robot motion with perception, learning, and responsible deployment:

1. **Introduction to robotics (J. Carpentier)** ([slides](https://mybox.inria.fr/f/ac842a7d1c944d869f54/?dl=1)): an overview of robotic systems, their applications, and the challenges of interacting with the physical world. We introduce robot modeling, dynamical systems, and feedback control as the foundations for perception and action.
2. **Kinematics (Y. de Mont-Marin)** ([slides](https://mybox.inria.fr/f/2ceacb0f26ac4429a235/?dl=1)): representing the configuration and motion of articulated robots using rotations, rigid transformations, and velocities. Forward and inverse kinematics, Jacobians, and task-space descriptions connect joint motions to end-effector objectives.
3. **Robot dynamics and simulation (J. Carpentier)** ([slides](https://mybox.inria.fr/f/48e517f593df47bc806d/?dl=1)): understanding how forces and torques generate motion. Topics include rigid-body dynamics, forward and inverse dynamics, contact and friction, and numerical integration for simulating robot–environment interactions.
4. **Motion planning (Y. de Mont-Marin)** ([slides](https://mybox.inria.fr/f/100be28029d240cfb1f3/?dl=1)): finding collision-free motions subject to geometric and kinematic constraints. We study configuration spaces, collision checking, and sampling-based methods such as probabilistic roadmaps (PRM) and rapidly exploring random trees (RRT), with applications to navigation and manipulation.
5. **Optimal control and optimization (J. Carpentier)** ([slides](https://mybox.inria.fr/f/a27f8aefc8bf4727be32/?dl=1)): computing motions and control inputs that minimize an objective while respecting system dynamics and constraints. We connect numerical optimization with trajectory optimization, differential dynamic programming, and model predictive control for feedback-based execution.
6. **Perception and estimation (S. Bonnabel)** ([slides](https://mybox.inria.fr/f/cdca3a3581d4492ca836/?dl=1)): estimating a robot's state and surroundings from noisy sensor measurements. We introduce sensor fusion, Kalman and extended Kalman filtering, and their use in localization, visual–inertial odometry, and simultaneous localization and mapping (SLAM).
7. **Reinforcement learning for robotics (T. Le Hellard):** learning control policies through interaction and reward. Topics include policy and value functions, policy optimization, reward design, and the challenges of transferring policies from simulation to physical robots, including robustness and domain randomization.
8. **Responsible robotics (P.-B. Wieber):** examining the ethical responsibilities of robotics research and deployment. Discussions address human oversight, safety and robustness, accountability, and the societal and environmental consequences of autonomous systems.
9. **World models and vision–language–action models (J. Carpentier and T. Le Hellard):** learning predictive models of the environment and policies that connect visual observations and language instructions to robot actions. We discuss how world models can support planning, how vision–language–action (VLA) models can support instruction following, and the challenges of generalization, physical grounding, and evaluation.

### Class locations and schedule

Classes will take place mainly at **[Mines de Paris][mines-map]**, from **09:00 to 12:00 (Paris time)** on the dates below. The exam (poster session) on **3 December** will take place at **[Inria Paris, 48 rue Barrault][inria-map]**. The session on 10 December will take place at the **[Maison des Mines, rue Saint-Jacques][maison-map]**. Rooms with limited seating are marked in the table; the other rooms are larger.

<div class="class-schedule" role="region" aria-label="Class locations and schedule" tabindex="0" markdown="0">
  <table role="table" aria-label="Class locations and schedule for 2026">
    <caption>Class schedule (2026)</caption>
    <thead role="rowgroup">
      <tr role="row">
        <th scope="col" role="columnheader">Date (2026)</th>
        <th scope="col" role="columnheader">Time (Paris)</th>
        <th scope="col" role="columnheader">Room</th>
        <th scope="col" role="columnheader">Location</th>
      </tr>
    </thead>
    <tbody role="rowgroup">
      <tr role="row">
        <th scope="row" role="rowheader">1 October</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>L106 <span class="class-schedule-note">Limited seats: 48</span></span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">8 October</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>L108_B</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">15 October</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>L109</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">22 October</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>L109</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">29 October</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>V107</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader"><s>5 November</s> <span class="class-schedule-note">Class cancelled</span></th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>—</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>—</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span>—</span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">12 November</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>FORGE_haut <span class="class-schedule-note">Limited seats: 48</span></span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">19 November</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>L106 <span class="class-schedule-note">Limited seats: 48</span></span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">26 November</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>FORGE_haut <span class="class-schedule-note">Limited seats: 48</span></span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris">Mines de Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">3 December <span class="class-schedule-note">Exam (poster session)</span></th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>—</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Inria+Paris+48+rue+Barrault+75013+Paris">Inria Paris</a></span></td>
      </tr>
      <tr role="row">
        <th scope="row" role="rowheader">10 December</th>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Time (Paris): </span> <span>09:00–12:00</span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Room: </span> <span>MDM_F <span class="class-schedule-note">Limited seats: 48</span></span></td>
        <td role="cell"><span class="class-schedule-label" aria-hidden="true">Location: </span> <span><a href="https://www.google.com/maps/search/?api=1&query=Maison+des+Mines+rue+Saint-Jacques+Paris">Maison des Mines, rue Saint-Jacques</a></span></td>
      </tr>
    </tbody>
  </table>
</div>

[inria-map]: https://www.google.com/maps/search/?api=1&query=Inria+Paris+48+rue+Barrault+75013+Paris
[mines-map]: https://www.google.com/maps/search/?api=1&query=Mines+Paris+PSL+boulevard+Saint-Michel+Paris
[maison-map]: https://www.google.com/maps/search/?api=1&query=Maison+des+Mines+rue+Saint-Jacques+Paris

**Directions to FORGE_haut:** turn left after reception and continue to the far end, walking parallel to boulevard Saint-Michel. Go down the stairs, then continue in the same direction; the room is on your right.

### Assessment

The exam (poster session) will take place on **3 December 2026 at [Inria Paris, 48 rue Barrault][inria-map]**.

In previous years, the tutorials were graded, but we decided to stop grading them due to coding assistants (we still strongly encourage you to complete the notebooks). Instead, there will be a quiz during the last session covering the topics seen in the course. The quiz will account for 25% of the final grade; the remaining 75% will come from a research article study, completed individually or in pairs and presented through a report and a poster. You will need to select three papers from [this list](/teaching/papers/), ranked by preference, and send your choice by **Monday 9 November 2026**. Each paper can be studied by at most two projects, on a first-come, first-served basis. Students are expected to understand the paper and then either reimplement it or try extending it. To pass the course, students must obtain a final grade of at least 10/20.
