---
layout: post
title: "Mass Displacement Networks"
date: 2017-08-12 19:42:44
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Deep_Learning
author: Natalia Neverova, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the large improvements in performance attained by using deep learning in computer vision, one can often further improve results with some additional post-processing that exploits the geometric nature of the underlying task. This commonly involves displacing the posterior distribution of a CNN in a way that makes it more appropriate for the task at hand, e.g. better aligned with local image features, or more compact. In this work we integrate this geometric post-processing within a deep architecture, introducing a differentiable and probabilistically sound counterpart to the common geometric voting technique used for evidence accumulation in vision. We refer to the resulting neural models as Mass Displacement Networks (MDNs), and apply them to human pose estimation in two distinct setups: (a) landmark localization, where we collapse a distribution to a point, allowing for precise localization of body keypoints and (b) communication across body parts, where we transfer evidence from one part to the other, allowing for a globally consistent pose estimate. We evaluate on large-scale pose estimation benchmarks, such as MPII Human Pose and COCO datasets, and report systematic improvements when compared to strong baselines.

##### Abstract (translated by Google)
尽管通过在计算机视觉中使用深度学习获得的性能有了很大的提高，人们通常可以进一步改进结果，并进行一些额外的后期处理，利用基本任务的几何特性。这通常涉及以使其更适合于手头任务的方式来置换CNN的后向分布。更好地与本地图像特征对齐，或更紧凑。在这项工作中，我们将这种几何后处理集成在一个深层次的体系结构中，引入了一种可区分的概率声音对应于用于视觉证据积累的常见几何投票技术。我们将所得到的神经模型称为质量位移网络（MDNs），并将它们应用于两个不同设置的人体姿态估计：（a）地标定位，其中我们将分布折叠到一个点，允许精确定位身体关键点（b）跨身体部位的沟通，我们将证据从一个部分转移到另一个部分，从而允许全球一致的姿势估计。我们评估大型姿态估计基准，如MPII人体姿态和COCO数据集，并与强基线相比，报告系统性改进。

##### URL
[https://arxiv.org/abs/1708.03816](https://arxiv.org/abs/1708.03816)

##### PDF
[https://arxiv.org/pdf/1708.03816](https://arxiv.org/pdf/1708.03816)

