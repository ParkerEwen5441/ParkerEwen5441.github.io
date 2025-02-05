---
title: "Modeling Uncertainty in 3D Gaussian Splatting through Continuous Semantic Splatting"
description: Quantifying uncertainty in 3D Gaussian Splatting models for closed-set semantic estimates.
date: 2025-02-05 00:00:00 +0300
label: 
image: /images/3DGS_Uncertainty.png
page_cover:
---
![Wireframe](/images/3DGS_Uncertainty.png)
*For more information, please read our [paper](https://arxiv.org/abs/2411.02547)*

In this paper, we present a novel algorithm for probabilistically updating and rasterizing semantic maps within 3D Gaussian Splatting (3D-GS). Although previous methods have introduced algorithms which learn to rasterize features in 3D-GS for enhanced scene understanding, 3D-GS can fail without warning which presents a challenge for safety-critical robotic applications. To address this gap, we propose a method which advances the literature of continuous semantic mapping from voxels to ellipsoids, combining the precise structure of 3D-GS with the ability to quantify uncertainty of probabilistic robotic maps. Given a set of images, our algorithm performs a probabilistic semantic update directly on the 3D ellipsoids to obtain an expectation and variance through the use of conjugate priors. We also propose a probabilistic rasterization which returns per-pixel segmentation predictions with quantifiable uncertainty. We compare our method with similar probabilistic voxel-based methods to verify our extension to 3D ellipsoids, and perform ablation studies on uncertainty quantification and temporal smoothing. 