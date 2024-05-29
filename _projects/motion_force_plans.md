---
title: "Generating Continuous Motion and Force Plans in Real-Time for Legged Mobile Manipulation"
description: This paper introduces STORMMAP, a real-time planner for legged manipulators that optimizes center-of-mass motion and manipulation force trajectories to ensure dynamic stability and task completion, running significantly faster than existing methods by assuming pre-determined contact locations.
date: 2024-05-26 00:00:00 +0300
label: 
image: /images/motion_force_plans.png
page_cover:
---
![Wireframe](/images/motion_force_plans.png)
*For more information, please read our [paper](https://arxiv.org/abs/2104.11685)*

Manipulators can be added to legged robots, allowing them to interact with and change their environment. Legged mobile manipulation planners must consider how contact forces generated by these manipulators affect the system. Current planning strategies either treat these forces as immutable during planning or are unable to optimize over these contact forces while operating in real-time. This paper presents the Stability and Task Oriented Receding-Horizon Motion and Manipulation Autonomous Planner (STORMMAP) that is able to generate continuous plans for the robot's motion and manipulation force trajectories that ensure dynamic feasibility and stability of the platform, and incentivizes accomplishing manipulation and motion tasks specified by a user. STORMMAP uses a nonlinear optimization problem to compute these plans and is able to run in real-time by assuming contact locations are given a-priori, either by a user or an external algorithm. A variety of simulated experiments on a quadruped with a manipulator mounted to its torso demonstrate the versatility of STORMMAP. In contrast to existing state of the art methods, the approach described in this paper generates continuous plans in under ten milliseconds, an order of magnitude faster than previous strategies.