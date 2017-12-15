---
layout: post
title: "Adaptable Precomputation for Random Walker Image Segmentation and Registration"
date: 2016-07-14 15:59:56
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation
author: Shawn Andrews, Ghassan Hamarneh
mathjax: true
---

* content
{:toc}

##### Abstract
The random walker (RW) algorithm is used for both image segmentation and registration, and possesses several useful properties that make it popular in medical imaging, such as being globally optimizable, allowing user interaction, and providing uncertainty information. The RW algorithm defines a weighted graph over an image and uses the graph's Laplacian matrix to regularize its solutions. This regularization reduces to solving a large system of equations, which may be excessively time consuming in some applications, such as when interacting with a human user. Techniques have been developed that precompute eigenvectors of a Laplacian offline, after image acquisition but before any analysis, in order speed up the RW algorithm online, when segmentation or registration is being performed. However, precomputation requires certain algorithm parameters be fixed offline, limiting their flexibility. In this paper, we develop techniques to update the precomputed data online when RW parameters are altered. Specifically, we dynamically determine the number of eigenvectors needed for a desired accuracy based on user input, and derive update equations for the eigenvectors when the edge weights or topology of the image graph are changed. We present results demonstrating that our techniques make RW with precomputation much more robust to offline settings while only sacrificing minimal accuracy.

##### Abstract (translated by Google)
随机游走（RW）算法被用于图像分割和配准，并且具有几个有用的性质，使其在医学成像中受到欢迎，诸如全局优化，允许用户交互以及提供不确定性信息。 RW算法定义图像上的加权图，并使用图的拉普拉斯矩阵对其解进行正则化。这种正则化减少到解决一个大型的方程组，这在一些应用中可能是非常耗时的，例如当与人类用户交互时。已经开发了一些技术，在图像采集之后但在任何分析之前，预先计算拉普拉斯算子的特征向量，以便在进行分割或注册时在线加速RW算法。但是，预计算需要某些算法参数脱机修复，限制了它们的灵活性。在本文中，我们开发了在RW参数改变时在线更新预计算数据的技术。具体来说，我们根据用户输入动态地确定所需精度所需的特征向量的数量，并在图像图形的边缘权重或拓扑发生变化时导出特征向量的更新方程。我们提供的结果证明了我们的技术使得RW的预计算更加稳健的离线设置，而只牺牲最小的精度。

##### URL
[https://arxiv.org/abs/1607.04174](https://arxiv.org/abs/1607.04174)

##### PDF
[https://arxiv.org/pdf/1607.04174](https://arxiv.org/pdf/1607.04174)

