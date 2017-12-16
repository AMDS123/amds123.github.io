---
layout: post
title: "Distributed Bundle Adjustment"
date: 2017-08-26 09:13:11
categories: arXiv_CV
tags: arXiv_CV
author: Karthikeyan Natesan Ramamurthy, Chung-Ching Lin, Aleksandr Aravkin, Sharath Pankanti, Raphael Viguier
mathjax: true
---

* content
{:toc}

##### Abstract
Most methods for Bundle Adjustment (BA) in computer vision are either centralized or operate incrementally. This leads to poor scaling and affects the quality of solution as the number of images grows in large scale structure from motion (SfM). Furthermore, they cannot be used in scenarios where image acquisition and processing must be distributed. We address this problem with a new distributed BA algorithm. Our distributed formulation uses alternating direction method of multipliers (ADMM), and, since each processor sees only a small portion of the data, we show that robust formulations improve performance. We analyze convergence of the proposed algorithm, and illustrate numerical performance, accuracy of the parameter estimates, and scalability of the distributed implementation in the context of synthetic 3D datasets with known camera position and orientation ground truth. The results are comparable to an alternate state-of-the-art centralized bundle adjustment algorithm on synthetic and real 3D reconstruction problems. The runtime of our implementation scales linearly with the number of observed points.

##### Abstract (translated by Google)
计算机视觉中的束调整（BA）的大多数方法是集中式的或者增量式操作。这导致缩放差，并且随着图像的数量以运动的大规模结构（SfM）增长而影响解决方案的质量。此外，它们不能用于必须分发图像采集和处理的情况。我们用一个新的分布式BA算法来解决这个问题。我们的分布式公式使用乘法器（ADMM）的交替方向方法，并且由于每个处理器只能看到一小部分数据，所以我们展示了强大的公式可以提高性能。我们分析了所提出的算法的收敛性，并且说明了数值性能，参数估计的准确性以及在具有已知摄像机位置和方向地面实况的合成三维数据集的情况下的分布式实现的可扩展性。这个结果与另一种先进的集中式光束调整算法在合成和真实三维重建问题上相当。我们实现的运行时间与观察点的数量呈线性关系。

##### URL
[https://arxiv.org/abs/1708.07954](https://arxiv.org/abs/1708.07954)

##### PDF
[https://arxiv.org/pdf/1708.07954](https://arxiv.org/pdf/1708.07954)

