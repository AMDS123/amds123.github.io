---
layout: post
title: "MonoPerfCap: Human Performance Capture from Monocular Video"
date: 2017-08-07 14:43:57
categories: arXiv_CV
tags: arXiv_CV Sparse Face Pose_Estimation CNN Quantitative Detection
author: Weipeng Xu, Avishek Chatterjee, Michael Zollhöfer, Helge Rhodin, Dushyant Mehta, Hans-Peter Seidel, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first marker-less approach for temporally coherent 3D performance capture of a human with general clothing from monocular video. Our approach reconstructs articulated human skeleton motion as well as medium-scale non-rigid surface deformations in general scenes. Human performance capture is a challenging problem due to the large range of articulation, potentially fast motion, and considerable non-rigid deformations, even from multi-view data. Reconstruction from monocular video alone is drastically more challenging, since strong occlusions and the inherent depth ambiguity lead to a highly ill-posed reconstruction problem. We tackle these challenges by a novel approach that employs sparse 2D and 3D human pose detections from a convolutional neural network using a batch-based pose estimation strategy. Joint recovery of per-batch motion allows to resolve the ambiguities of the monocular reconstruction problem based on a low dimensional trajectory subspace. In addition, we propose refinement of the surface geometry based on fully automatically extracted silhouettes to enable medium-scale non-rigid alignment. We demonstrate state-of-the-art performance capture results that enable exciting applications such as video editing and free viewpoint video, previously infeasible from monocular video. Our qualitative and quantitative evaluation demonstrates that our approach significantly outperforms previous monocular methods in terms of accuracy, robustness and scene complexity that can be handled.

##### Abstract (translated by Google)
我们提出了第一个无标记的方法，用于从单眼视频获得一般服装的时间一致的3D性能捕捉。我们的方法重建关节人体骨骼运动以及一般场景中的中等程度的非刚性表面变形。由于大范围的发音，潜在的快速运动和相当多的非刚性变形，即使是从多视角数据，人类的表演捕捉也是一个具有挑战性的问题。单眼视频单独重建显得更具挑战性，因为强遮挡和内在的深度模糊导致了高度不适的重建问题。我们采用一种新颖的方法来处理这些挑战，该方法使用基于批处理的姿态估计策略从卷积神经网络采用稀疏的二维和三维人体姿态检测。每批运动的联合恢复允许解决基于低维轨迹子空间的单目重建问题的模糊性。此外，我们建议基于完全自动提取的轮廓来优化曲面几何图形，以实现中等比例的非刚性对齐。我们展示了最先进的性能捕获结果，使视频编辑和免费视点视频等令人兴奋的应用成为可能，这些视频之前在单眼视频中是不可行的。我们的定性和定量评估表明，我们的方法在精度，稳健性和可处理的场景复杂度方面明显优于以前的单眼方法。

##### URL
[https://arxiv.org/abs/1708.02136](https://arxiv.org/abs/1708.02136)

##### PDF
[https://arxiv.org/pdf/1708.02136](https://arxiv.org/pdf/1708.02136)

