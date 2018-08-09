---
layout: post
title: "Omnidirectional DSO: Direct Sparse Odometry with Fisheye Cameras"
date: 2018-08-08 13:34:31
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Hidenobu Matsuki, Lukas von Stumberg, Vladyslav Usenko, J&#xf6;rg St&#xfc;ckler, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel real-time direct monocular visual odometry for omnidirectional cameras. Our method extends direct sparse odometry (DSO) by using the unified omnidirectional model as a projection function, which can be applied to fisheye cameras with a field-of-view (FoV) well above 180 degrees. This formulation allows for using the full area of the input image even with strong distortion, while most existing visual odometry methods can only use a rectified and cropped part of it. Model parameters within an active keyframe window are jointly optimized, including the intrinsic/extrinsic camera parameters, 3D position of points, and affine brightness parameters. Thanks to the wide FoV, image overlap between frames becomes bigger and points are more spatially distributed. Our results demonstrate that our method provides increased accuracy and robustness over state-of-the-art visual odometry algorithms.

##### Abstract (translated by Google)
我们为全向摄像机提出了一种新颖的实时直接单眼视觉测距仪。我们的方法通过使用统一的全向模型作为投影函数来扩展直接稀疏测距（DSO），其可以应用于具有远大于180度的视场（FoV）的鱼眼摄像机。该配方允许使用输入图像的整个区域，即使具有强烈的失真，而大多数现有的视觉测距方法只能使用其整理和裁剪的部分。共同优化活动关键帧窗口内的模型参数，包括内部/外部相机参数，点的3D位置和仿射亮度参数。由于宽的FoV，帧之间的图像重叠变得更大并且点在空间上更加分散。我们的结果表明，我们的方法提供了比最先进的视觉测距算法更高的准确性和鲁棒性。

##### URL
[http://arxiv.org/abs/1808.02775](http://arxiv.org/abs/1808.02775)

##### PDF
[http://arxiv.org/pdf/1808.02775](http://arxiv.org/pdf/1808.02775)

