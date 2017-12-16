---
layout: post
title: "SeDAR - Semantic Detection and Ranging: Humans can localise without LiDAR, can robots?"
date: 2017-09-05 17:35:07
categories: arXiv_CV
tags: arXiv_CV Face Detection
author: Oscar Mendez, Simon Hadfield, Nicolas Pugeault, Richard Bowden
mathjax: true
---

* content
{:toc}

##### Abstract
How does a person work out their location using a floorplan? It is probably safe to say that we do not explicitly measure depths to every visible surface and try to match them against different pose estimates in the floorplan. And yet, this is exactly how most robotic scan-matching algorithms operate. Similarly, we do not extrude the 2D geometry present in the floorplan into 3D and try to align it to the real-world. And yet, this is how most vision-based approaches localise. Humans do the exact opposite. Instead of depth, we use high level semantic cues. Instead of extruding the floorplan up into the third dimension, we collapse the 3D world into a 2D representation. Evidence of this is that many of the floorplans we use in everyday life are not accurate, opting instead for high levels of discriminative landmarks. In this work, we use this insight to present a global localisation approach that relies solely on the semantic labels present in the floorplan and extracted from RGB images. While our approach is able to use range measurements if available, we demonstrate that they are unnecessary as we can achieve results comparable to state-of-the-art without them.

##### Abstract (translated by Google)
一个人如何使用平面图计算他们的位置？可以肯定地说，我们没有明确测量每个可见表面的深度，并尝试将它们与平面图中的不同姿态估计进行匹配。然而，这正是大多数机器人扫描匹配算法的工作原理。同样，我们也不会将平面布局中的2D几何体挤压成3D，并尝试将其与现实世界对齐。然而，这是大多数基于视觉的方法本地化的方式。人类完全相反。我们不使用深度，而是使用高级语义提示。我们将3D世界折叠成二维表示，而不是将平面布局拉伸到第三维。这方面的证据是，我们在日常生活中使用的许多平面布置图是不准确的，而是选择高水平的区分性地标。在这项工作中，我们使用这种洞察力来展示一种全球化的定位方法，它完全依赖于平面图中存在的语义标签，并从RGB图像中提取出来。虽然我们的方法能够使用范围测量（如果有的话），但是我们证明它们是不必要的，因为我们可以在没有它们的情况下获得与最新技术相媲美的结果。

##### URL
[https://arxiv.org/abs/1709.01500](https://arxiv.org/abs/1709.01500)

##### PDF
[https://arxiv.org/pdf/1709.01500](https://arxiv.org/pdf/1709.01500)

