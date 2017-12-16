---
layout: post
title: "Parse Geometry from a Line: Monocular Depth Estimation with Partial Laser Observation"
date: 2016-10-17 21:12:07
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Classification
author: Yiyi Liao, Lichao Huang, Yue Wang, Sarath Kodagoda, Yinan Yu, Yong Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Many standard robotic platforms are equipped with at least a fixed 2D laser range finder and a monocular camera. Although those platforms do not have sensors for 3D depth sensing capability, knowledge of depth is an essential part in many robotics activities. Therefore, recently, there is an increasing interest in depth estimation using monocular images. As this task is inherently ambiguous, the data-driven estimated depth might be unreliable in robotics applications. In this paper, we have attempted to improve the precision of monocular depth estimation by introducing 2D planar observation from the remaining laser range finder without extra cost. Specifically, we construct a dense reference map from the sparse laser range data, redefining the depth estimation task as estimating the distance between the real and the reference depth. To solve the problem, we construct a novel residual of residual neural network, and tightly combine the classification and regression losses for continuous depth estimation. Experimental results suggest that our method achieves considerable promotion compared to the state-of-the-art methods on both NYUD2 and KITTI, validating the effectiveness of our method on leveraging the additional sensory information. We further demonstrate the potential usage of our method in obstacle avoidance where our methodology provides comprehensive depth information compared to the solution using monocular camera or 2D laser range finder alone.

##### Abstract (translated by Google)
许多标准的机器人平台至少配备了一个固定的2D激光测距仪和一个单眼相机。虽然这些平台没有3D深度感应功能的传感器，但深度知识是许多机器人活动的重要组成部分。因此，近来，使用单目图像进行深度估计的兴趣越来越大。由于这个任务本质上是模棱两可的，在机器人应用中，数据驱动的估计深度可能是不可靠的。在本文中，我们试图通过从剩余的激光测距仪引入二维平面观测来提高单眼深度估计的精度，而不需要额外的成本。具体来说，我们从稀疏的激光距离数据构造一个密集的参考图，重新定义深度估计任务，估计真实和参考深度之间的距离。为了解决这个问题，我们构造了一个新的残差神经网络，并紧密结合分类和回归损失进行连续深度估计。实验结果表明，与NYUD2和KITTI最先进的方法相比，我们的方法获得了相当大的提升，验证了我们的方法在利用附加感官信息方面的有效性。我们进一步证明了我们的方法在避障中的潜在用途，其中我们的方法提供了全面的深度信息，与单独使用单目照相机或2D激光测距仪的解决方案相比。

##### URL
[https://arxiv.org/abs/1611.02174](https://arxiv.org/abs/1611.02174)

##### PDF
[https://arxiv.org/pdf/1611.02174](https://arxiv.org/pdf/1611.02174)

