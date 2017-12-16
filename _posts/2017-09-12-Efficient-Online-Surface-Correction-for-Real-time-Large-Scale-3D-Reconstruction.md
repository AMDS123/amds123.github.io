---
layout: post
title: "Efficient Online Surface Correction for Real-time Large-Scale 3D Reconstruction"
date: 2017-09-12 09:44:23
categories: arXiv_CV
tags: arXiv_CV Sparse Face Tracking Optimization Quantitative SLAM
author: Robert Maier, Raphael Schaller, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art methods for large-scale 3D reconstruction from RGB-D sensors usually reduce drift in camera tracking by globally optimizing the estimated camera poses in real-time without simultaneously updating the reconstructed surface on pose changes. We propose an efficient on-the-fly surface correction method for globally consistent dense 3D reconstruction of large-scale scenes. Our approach uses a dense Visual RGB-D SLAM system that estimates the camera motion in real-time on a CPU and refines it in a global pose graph optimization. Consecutive RGB-D frames are locally fused into keyframes, which are incorporated into a sparse voxel hashed Signed Distance Field (SDF) on the GPU. On pose graph updates, the SDF volume is corrected on-the-fly using a novel keyframe re-integration strategy with reduced GPU-host streaming. We demonstrate in an extensive quantitative evaluation that our method is up to 93% more runtime efficient compared to the state-of-the-art and requires significantly less memory, with only negligible loss of surface quality. Overall, our system requires only a single GPU and allows for real-time surface correction of large environments.

##### Abstract (translated by Google)
用于RGB-D传感器的大规模三维重建的最先进的方法通常通过实时地全面优化估计的相机姿态而不同时更新姿态变化上的重构表面来减少相机跟踪中的漂移。我们提出了一个高效的飞行表面修正方法，用于大规模场景的全局一致密集三维重建。我们的方法使用密集的Visual RGB-D SLAM系统，可以在CPU上实时估计摄像机运动，并在全局姿态图优化中对其进行优化。连续的RGB-D帧被本地融合到关键帧中，这些关键帧被并入GPU上的稀疏体素散列签名距离场（SDF）。在姿态图更新上，使用减少GPU主机流式传输的新颖关键帧重新集成策略，SDF量被即时修正。我们在广泛的定量评估中证明，与最先进的技术相比，我们的方法运行效率高出93％，并且只需要更少的内存，而且表面质量的损失可以忽略不计。总的来说，我们的系统只需要一个GPU，并且可以对大型环境进行实时表面校正。

##### URL
[https://arxiv.org/abs/1709.03763](https://arxiv.org/abs/1709.03763)

##### PDF
[https://arxiv.org/pdf/1709.03763](https://arxiv.org/pdf/1709.03763)

