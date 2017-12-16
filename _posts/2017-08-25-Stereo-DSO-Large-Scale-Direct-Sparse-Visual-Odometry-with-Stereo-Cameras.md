---
layout: post
title: "Stereo DSO: Large-Scale Direct Sparse Visual Odometry with Stereo Cameras"
date: 2017-08-25 20:50:54
categories: arXiv_CV
tags: arXiv_CV Sparse Tracking Optimization Quantitative
author: Rui Wang, Martin Schwörer, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Stereo Direct Sparse Odometry (Stereo DSO) as a novel method for highly accurate real-time visual odometry estimation of large-scale environments from stereo cameras. It jointly optimizes for all the model parameters within the active window, including the intrinsic/extrinsic camera parameters of all keyframes and the depth values of all selected pixels. In particular, we propose a novel approach to integrate constraints from static stereo into the bundle adjustment pipeline of temporal multi-view stereo. Real-time optimization is realized by sampling pixels uniformly from image regions with sufficient intensity gradient. Fixed-baseline stereo resolves scale drift. It also reduces the sensitivities to large optical flow and to rolling shutter effect which are known shortcomings of direct image alignment methods. Quantitative evaluation demonstrates that the proposed Stereo DSO outperforms existing state-of-the-art visual odometry methods both in terms of tracking accuracy and robustness. Moreover, our method delivers a more precise metric 3D reconstruction than previous dense/semi-dense direct approaches while providing a higher reconstruction density than feature-based methods.

##### Abstract (translated by Google)
我们提出立体声直接稀疏测距（立体声DSO）作为一种新颖的方法，用于从立体相机进行大规模环境的高精度实时视觉测距估计。它共同优化了活动窗口内的所有模型参数，包括所有关键帧的内在/外在摄像机参数以及所有选定像素的深度值。具体来说，我们提出了一种将静态立体声的约束条件整合到时间多视点立体声束调整流水线中的新方法。通过从具有足够强度梯度的图像区域均匀地采样像素来实现实时优化。固定基线立体声解决了比例漂移。它也降低了大光流的灵敏度和卷帘快门效应，这是已知的直接图像对准方法的缺点。定量评估表明，所提出的立体声DSO在跟踪精度和鲁棒性方面都优于现有的最新视觉测距方法。此外，我们的方法比先前的密集/半密集直接方法提供更精确的度量3D重建，同时提供比基于特征的方法更高的重建密度。

##### URL
[https://arxiv.org/abs/1708.07878](https://arxiv.org/abs/1708.07878)

##### PDF
[https://arxiv.org/pdf/1708.07878](https://arxiv.org/pdf/1708.07878)

