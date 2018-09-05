---
layout: post
title: "Leveraging Deep Visual Descriptors for Hierarchical Efficient Localization"
date: 2018-09-04 14:25:17
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Deep_Learning
author: Paul-Edouard Sarlin (1), Fr&#xe9;d&#xe9;ric Debraine (1), Marcin Dymczyk (1), Roland Siegwart (1), Cesar Cadena (1) ((1) Autonomous Systems Lab, ETH Zurich)
mathjax: true
---

* content
{:toc}

##### Abstract
Many robotics applications require precise pose estimates despite operating in large and changing environments. This can be addressed by visual localization, using a pre-computed 3D model of the surroundings. The pose estimation then amounts to finding correspondences between 2D keypoints in a query image and 3D points in the model using local descriptors. However, computational power is often limited on robotic platforms, making this task challenging in large-scale environments. Binary feature descriptors significantly speed up this 2D-3D matching, and have become popular in the robotics community, but also strongly impair the robustness to perceptual aliasing and changes in viewpoint, illumination and scene structure. In this work, we propose to leverage recent advances in deep learning to perform an efficient hierarchical localization. We first localize at the map level using learned image-wide global descriptors, and subsequently estimate a precise pose from 2D-3D matches computed in the candidate places only. This restricts the local search and thus allows to efficiently exploit powerful non-binary descriptors usually dismissed on resource-constrained devices. Our approach results in state-of-the-art localization performance while running in real-time on a popular mobile platform, enabling new prospects for robotics research.

##### Abstract (translated by Google)
尽管在大型且不断变化的环境中操作，但许多机器人应用程这可以通过使用预先计算的周围环境的3D模型的视觉定位来解决。然后，姿势估计相当于使用局部描述符找到查询图像中的2D关键点与模型中的3D点之间的对应关系。然而，计算能力通常限制在机器人平台上，使得该任务在大规模环境中具有挑战性。二进制特征描述符显着加速了这种2D-3D匹配，并且在机器人社区中变得流行，但也强烈损害了感知混叠的稳健性以及视点，照明和场景结构的变化。在这项工作中，我们建议利用深度学习的最新进展来执行有效的分层本地化。我们首先使用学习的图像范围的全局描述符在地图级别进行本地化，然后仅根据在候选位置计算的2D-3D匹配来估计精确的姿势。这限制了本地搜索，因此允许有效地利用通常在资源受限设备上被解雇的强大的非二进制描述符。我们的方法可以在流行的移动平台上实时运行，从而实现最先进的本地化性能，从而为机器人研究提供新的前景。

##### URL
[http://arxiv.org/abs/1809.01019](http://arxiv.org/abs/1809.01019)

##### PDF
[http://arxiv.org/pdf/1809.01019](http://arxiv.org/pdf/1809.01019)

