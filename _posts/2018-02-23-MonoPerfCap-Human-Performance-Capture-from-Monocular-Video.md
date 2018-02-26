---
layout: post
title: "MonoPerfCap: Human Performance Capture from Monocular Video"
date: 2018-02-23 12:40:25
categories: arXiv_CV
tags: arXiv_CV Sparse Face Pose_Estimation CNN Quantitative Detection
author: Weipeng Xu, Avishek Chatterjee, Michael Zollh&#xf6;fer, Helge Rhodin, Dushyant Mehta, Hans-Peter Seidel, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first marker-less approach for temporally coherent 3D performance capture of a human with general clothing from monocular video. Our approach reconstructs articulated human skeleton motion as well as medium-scale non-rigid surface deformations in general scenes. Human performance capture is a challenging problem due to the large range of articulation, potentially fast motion, and considerable non-rigid deformations, even from multi-view data. Reconstruction from monocular video alone is drastically more challenging, since strong occlusions and the inherent depth ambiguity lead to a highly ill-posed reconstruction problem. We tackle these challenges by a novel approach that employs sparse 2D and 3D human pose detections from a convolutional neural network using a batch-based pose estimation strategy. Joint recovery of per-batch motion allows to resolve the ambiguities of the monocular reconstruction problem based on a low dimensional trajectory subspace. In addition, we propose refinement of the surface geometry based on fully automatically extracted silhouettes to enable medium-scale non-rigid alignment. We demonstrate state-of-the-art performance capture results that enable exciting applications such as video editing and free viewpoint video, previously infeasible from monocular video. Our qualitative and quantitative evaluation demonstrates that our approach significantly outperforms previous monocular methods in terms of accuracy, robustness and scene complexity that can be handled.

##### Abstract (translated by Google)
我们提出了第一种无标记方法，用于从单眼视频获得一般服装的时间一致性3D性能。我们的方法重建关节式人体骨骼运动以及一般场景中的中等非刚性表面变形。由于大范围的关节运动，潜在的快速运动和相当大的非刚性变形，即使是从多视角数据，人类表现捕捉也是一个具有挑战性的问题。单眼视频单独重建显然更具挑战性，因为强遮挡和内在深度模糊导致高度不适的重建问题。我们通过采用基于批处理的姿态估计策略的卷积神经网络采用稀疏2D和3D人体姿势检测的新颖方法来应对这些挑战。每批运动的联合恢复允许解决基于低维轨迹子空间的单眼重建问题的模糊性。此外，我们建议基于完全自动提取的轮廓来优化曲面几何图形，以实现中等比例的非刚性对齐。我们展示了最先进的性能捕获结果，能够激发视频编辑和免费视点视频等令人兴奋的应用，而这些应用以前在单眼视频中是不可行的。我们的定性和定量评估表明，我们的方法在准确性，鲁棒性和可处理的场景复杂度方面明显优于以前的单眼方法。

##### URL
[http://arxiv.org/abs/1708.02136](http://arxiv.org/abs/1708.02136)

##### PDF
[http://arxiv.org/pdf/1708.02136](http://arxiv.org/pdf/1708.02136)

