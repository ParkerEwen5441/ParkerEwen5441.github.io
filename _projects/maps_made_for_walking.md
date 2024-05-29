---
title: "These Maps Are Made For Walking: Real-Time Terrain Property Estimation for Mobile Robots"
description: This paper proposes a Bayesian inference framework for real-time semantic mapping that uses RGB-D camera data to estimate terrain properties and their probability distributions, outperforming state-of-the-art methods and successfully predicting terrain properties in both simulated and real-world environments.
date: 2024-05-27 00:00:00 +0300
label: 
image: /images/maps_made_for_walking.png
page_cover:
---
![Wireframe](/images/maps_made_for_walking.png)
*For more information, see the [project webpage](https://roahmlab.github.io/sel_map/)*

The equations of motion governing mobile robots are dependent on terrain properties such as the coefficient of friction, and contact model parameters. Estimating these properties is thus essential for robotic navigation. Ideally any map estimating terrain properties should run in real time, mitigate sensor noise, and provide probability distributions of the aforementioned properties, thus enabling risk-mitigating navigation and planning. This paper addresses these needs and proposes a Bayesian inference framework for semantic mapping which recursively estimates both the terrain surface profile and a probability distribution for terrain properties using data from a single RGB-D camera. The proposed framework is evaluated in simulation against other semantic mapping methods and is shown to outperform these state-of-the-art methods in terms of correctly estimating simulated ground-truth terrain properties when evaluated using a precision-recall curve and the Kullback-Leibler divergence test. Additionally, the proposed method is deployed on a physical legged robotic platform in both indoor and outdoor environments, and we show our method correctly predicts terrain properties in both cases.  The proposed framework runs in real-time and includes a ROS interface for easy integration.