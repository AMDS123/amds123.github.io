---
layout: post
title: "Efficient 2D-3D Matching for Multi-Camera Visual Localization"
date: 2018-09-17 21:02:48
categories: arXiv_RO
tags: arXiv_RO Pose_Estimation
author: Marcel Geppert, Peidong Liu, Zhaopeng Cui, Marc Pollefeys, Torsten Sattler
mathjax: true
---

* content
{:toc}

##### Abstract
Visual localization, i.e., determining the position and orientation of a vehicle with respect to a map, is a key problem in autonomous driving. We present a multi-camera visual inertial localization algorithm for large scale environments. To efficiently and effectively match features against a pre-built global 3D map, we propose a prioritized feature matching scheme for multi-camera systems. In contrast to existing works, designed for monocular cameras, we (1) tailor the prioritization function to the multi-camera setup and (2) run feature matching and pose estimation in parallel. This significantly accelerates the matching and pose estimation stages and allows us to dynamically adapt the matching efforts based on the surrounding environment. In addition, we show how pose priors can be integrated into the localization system to increase efficiency and robustness. Finally, we extend our algorithm by fusing the absolute pose estimates with motion estimates from a multi-camera visual inertial odometry pipeline (VIO). This results in a system that provides reliable and drift-less pose estimations for high speed autonomous driving. Extensive experiments show that our localization runs fast and robust under varying conditions, and that our extended algorithm enables reliable real-time pose estimation.

##### Abstract (translated by Google)
视觉定位，即确定车辆相对于地图的位置和方向，是自动驾驶中的关键问题。我们提出了一种适用于大规模环境的多摄像机视觉惯性定位算法。为了有效地将特征与预先建立的全局3D地图进行匹配，我们提出了用于多相机系统的优先特征匹配方案。与针对单目相机设计的现有作品相比，我们（1）为多相机设置定制优先级功能，以及（2）并行地运行特征匹配和姿势估计。这显着加速了匹配和姿势估计阶段，并允许我们根据周围环境动态调整匹配工作。此外，我们还展示了如何将姿势先验集成到本地化系统中，以提高效率和稳健性。最后，我们通过将绝对姿态估计与来自多摄像机视觉惯性测距管道（VIO）的运动估计融合来扩展我们的算法。这导致系统为高速自动驾驶提供可靠且无漂移的姿态估计。大量实验表明，我们的定位在不同条件下运行快速且稳健，并且我们的扩展算法可实现可靠的实时姿态估计。

##### URL
[http://arxiv.org/abs/1809.06445](http://arxiv.org/abs/1809.06445)

##### PDF
[http://arxiv.org/pdf/1809.06445](http://arxiv.org/pdf/1809.06445)

