---
layout: post
title: "De-noising, Stabilizing and Completing 3D Reconstructions On-the-go using Plane Priors"
date: 2017-03-28 01:45:24
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation
author: Maksym Dzitsiuk, Jürgen Sturm, Robert Maier, Lingni Ma, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Creating 3D maps on robots and other mobile devices has become a reality in recent years. Online 3D reconstruction enables many exciting applications in robotics and AR/VR gaming. However, the reconstructions are noisy and generally incomplete. Moreover, during onine reconstruction, the surface changes with every newly integrated depth image which poses a significant challenge for physics engines and path planning algorithms. This paper presents a novel, fast and robust method for obtaining and using information about planar surfaces, such as walls, floors, and ceilings as a stage in 3D reconstruction based on Signed Distance Fields. Our algorithm recovers clean and accurate surfaces, reduces the movement of individual mesh vertices caused by noise during online reconstruction and fills in the occluded and unobserved regions. We implemented and evaluated two different strategies to generate plane candidates and two strategies for merging them. Our implementation is optimized to run in real-time on mobile devices such as the Tango tablet. In an extensive set of experiments, we validated that our approach works well in a large number of natural environments despite the presence of significant amount of occlusion, clutter and noise, which occur frequently. We further show that plane fitting enables in many cases a meaningful semantic segmentation of real-world scenes.

##### Abstract (translated by Google)
在机器人和其他移动设备上创建3D地图近年来已成为现实。在线三维重建使机器人和AR / VR游戏中的许多激动人心的应用成为可能。然而，重建是嘈杂的，通常是不完整的。而且，在重建的过程中，每一个新的整合的深度图像都会随着表面的变化而变化，这对于物理引擎和路径规划算法是一个很大的挑战。本文提出了一种新颖，快速和鲁棒的方法，用于获取和使用平面曲面的信息，如墙壁，地板和天花板作为基于有符号距离场的三维重建的一个阶段。我们的算法恢复干净和准确的表面，减少网上重建期间由噪声引起的单个网格顶点的移动，并填充遮挡和未观察的区域。我们实施和评估了两种不同的策略来生成飞机候选者和两种合并策略。我们的实施经过优化，可以在Tango平板电脑等移动设备上实时运行。在一系列广泛的实验中，我们验证了我们的方法在大量的自然环境中工作良好，尽管经常出现大量的遮挡，杂波和噪声。我们进一步表明，平面拟合在许多情况下使真实世界场景有意义的语义分割。

##### URL
[https://arxiv.org/abs/1609.08267](https://arxiv.org/abs/1609.08267)

##### PDF
[https://arxiv.org/pdf/1609.08267](https://arxiv.org/pdf/1609.08267)

