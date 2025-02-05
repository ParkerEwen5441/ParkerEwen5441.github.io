---
title: "LatentBKI: Open-Dictionary Continuous Mapping in Visual-Language Latent Spaces with Quantifiable Uncertainty"
description: LatentBKI: Open-Dictionary Continuous Mapping in Visual-Language Latent Spaces with Quantifiable Uncertainty.
date: 2025-02-05 00:00:00 +0300
label: 
image: /images/LantentBKI.png
page_cover:
---
![Wireframe](/images/LantentBKI.png)
*For more information, please read our [paper](https://arxiv.org/abs/2410.11783)*

This paper introduces a novel probabilistic mapping algorithm, LatentBKI, which enables open-vocabulary mapping with quantifiable uncertainty. Traditionally, semantic mapping algorithms focus on a fixed set of semantic categories which limits their applicability for complex robotic tasks. Vision-Language (VL) models have recently emerged as a technique to jointly model language and visual features in a latent space, enabling semantic recognition beyond a predefined, fixed set of semantic classes. LatentBKI recurrently incorporates neural embeddings from VL models into a voxel map with quantifiable uncertainty, leveraging the spatial correlations of nearby observations through Bayesian Kernel Inference (BKI). LatentBKI is evaluated against similar explicit semantic mapping and VL mapping frameworks on the popular Matterport3D and Semantic KITTI datasets, demonstrating that LatentBKI maintains the probabilistic benefits of continuous mapping with the additional benefit of open-dictionary queries. Real-world experiments demonstrate applicability to challenging indoor environments. 