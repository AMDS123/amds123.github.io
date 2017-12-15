---
layout: post
title: "High-Performance and Tunable Stereo Reconstruction"
date: 2016-02-17 17:29:14
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Sudeep Pillai, Srikumar Ramalingam, John J. Leonard
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional stereo algorithms have focused their efforts on reconstruction quality and have largely avoided prioritizing for run time performance. Robots, on the other hand, require quick maneuverability and effective computation to observe its immediate environment and perform tasks within it. In this work, we propose a high-performance and tunable stereo disparity estimation method, with a peak frame-rate of 120Hz (VGA resolution, on a single CPU-thread), that can potentially enable robots to quickly reconstruct their immediate surroundings and maneuver at high-speeds. Our key contribution is a disparity estimation algorithm that iteratively approximates the scene depth via a piece-wise planar mesh from stereo imagery, with a fast depth validation step for semi-dense reconstruction. The mesh is initially seeded with sparsely matched keypoints, and is recursively tessellated and refined as needed (via a resampling stage), to provide the desired stereo disparity accuracy. The inherent simplicity and speed of our approach, with the ability to tune it to a desired reconstruction quality and runtime performance makes it a compelling solution for applications in high-speed vehicles.

##### Abstract (translated by Google)
传统的立体声算法把重点放在重建质量上，而且在很大程度上避免了运行时间性能的优先级。另一方面，机器人需要快速的机动性和有效的计算来观察其周围环境并执行其中的任务。在这项工作中，我们提出了一个高性能和可调的立体视差估计方法，峰值帧速率为120Hz（VGA分辨率，在单个CPU线程上），可能使机器人能够快速重建其周围环境和机动在高速。我们的主要贡献是视差估计算法，通过立体影像中的分段平面网格迭代近似场景深度，以及用于半密集重建的快速深度验证步骤。该网格最初采用稀疏匹配的关键点进行播种，并根据需要进行递归细分和精化（通过重采样阶段），以提供所需的立体声视差精度。我们的方法具有固有的简单性和速度，能够将其调整到所需的重建质量和运行时性能，这使其成为高速车辆应用的引人注目的解决方案。

##### URL
[https://arxiv.org/abs/1511.00758](https://arxiv.org/abs/1511.00758)

##### PDF
[https://arxiv.org/pdf/1511.00758](https://arxiv.org/pdf/1511.00758)

