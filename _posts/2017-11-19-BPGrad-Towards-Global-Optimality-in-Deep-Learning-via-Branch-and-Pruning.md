---
layout: post
title: "BPGrad: Towards Global Optimality in Deep Learning via Branch and Pruning"
date: 2017-11-19 02:44:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Deep_Learning Detection Recognition
author: Ziming Zhang, Yuanwei Wu, Guanghui Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding the global optimality in deep learning (DL) has been attracting more and more attention recently. Conventional DL solvers, however, have not been developed intentionally to seek for such global optimality. In this paper we propose a novel approximation algorithm, BPGrad, towards optimizing deep models globally via branch and pruning. Our BPGrad algorithm is based on the assumption of Lipschitz continuity in DL, and as a result it can adaptively determine the step size for current gradient given the history of previous updates, wherein theoretically no smaller steps can achieve the global optimality. We prove that, by repeating such branch-and-pruning procedure, we can locate the global optimality within finite iterations. Empirically an efficient solver based on BPGrad for DL is proposed as well, and it outperforms conventional DL solvers such as Adagrad, Adadelta, RMSProp, and Adam in the tasks of object recognition, detection, and segmentation.

##### Abstract (translated by Google)
了解深度学习（DL）的全局最优性已经引起越来越多的关注。然而，传统的DL解算器并没有被有意地开发来寻求这样的全局最优性。在本文中，我们提出了一种新的逼近算法，BPGrad，通过分支和修剪来优化全局深度模型。我们的BPGrad算法是基于DL中Lipschitz连续性的假设，因此在给定历史更新的前提下，它可以自适应地确定当前梯度的步长，理论上没有更小的步骤可以达到全局最优。我们证明，通过重复这种分枝剪枝程序，我们可以在有限迭代内定位全局最优性。经验性地提出了一种基于BPGrad for DL的高效求解器，它在对象识别，检测和分割任务中优于传统的DL解算器，如Adagrad，Adadelta，RMSProp和Adam。

##### URL
[https://arxiv.org/abs/1711.06959](https://arxiv.org/abs/1711.06959)

##### PDF
[https://arxiv.org/pdf/1711.06959](https://arxiv.org/pdf/1711.06959)

