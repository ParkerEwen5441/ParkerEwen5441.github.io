---
title: "ConvBKI: Real-Time Probabilistic Semantic Mapping Network with Quantifiable Uncertainty"
description: We develop a modular neural network for real-time semantic mapping in uncertain environments.
date: 2024-05-28 00:00:00 +0300
label: 
image: /images/convbki.png
page_cover:
---
![Wireframe](/images/convbki.png)
*For more information, please read our [paper](https://arxiv.org/abs/2310.16020)*

In this paper, we develop a modular neural network for real-time semantic mapping in uncertain environments, which explicitly updates per-voxel probabilistic distributions within a neural network layer. Our approach combines the reliability of classical probabilistic algorithms with the performance and efficiency of modern neural networks. Although robotic perception is often divided between modern differentiable methods and classical explicit methods, a union of both is necessary for real-time and trustworthy performance. We introduce a novel Convolutional Bayesian Kernel Inference (ConvBKI) layer which incorporates semantic segmentation predictions online into a 3D map through a depthwise convolution layer by leveraging conjugate priors. We compare ConvBKI against state-of-the-art deep learning approaches and probabilistic algorithms for mapping to evaluate reliability and performance. We also create a Robot Operating System (ROS) package of ConvBKI and test it on real-world perceptually challenging off-road driving data.