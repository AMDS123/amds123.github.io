---
layout: post
title: "Tensor Canonical Correlation Analysis for Multi-view Dimension Reduction"
date: 2015-02-09 01:58:27
categories: arXiv_CV
tags: arXiv_CV Classification Prediction Relation
author: Yong Luo, Dacheng Tao, Yonggang Wen, Kotagiri Ramamohanarao, Chao Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Canonical correlation analysis (CCA) has proven an effective tool for two-view dimension reduction due to its profound theoretical foundation and success in practical applications. In respect of multi-view learning, however, it is limited by its capability of only handling data represented by two-view features, while in many real-world applications, the number of views is frequently many more. Although the ad hoc way of simultaneously exploring all possible pairs of features can numerically deal with multi-view data, it ignores the high order statistics (correlation information) which can only be discovered by simultaneously exploring all features. Therefore, in this work, we develop tensor CCA (TCCA) which straightforwardly yet naturally generalizes CCA to handle the data of an arbitrary number of views by analyzing the covariance tensor of the different views. TCCA aims to directly maximize the canonical correlation of multiple (more than two) views. Crucially, we prove that the multi-view canonical correlation maximization problem is equivalent to finding the best rank-1 approximation of the data covariance tensor, which can be solved efficiently using the well-known alternating least squares (ALS) algorithm. As a consequence, the high order correlation information contained in the different views is explored and thus a more reliable common subspace shared by all features can be obtained. In addition, a non-linear extension of TCCA is presented. Experiments on various challenge tasks, including large scale biometric structure prediction, internet advertisement classification and web image annotation, demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)
典型相关分析（CCA）由于其深厚的理论基础和在实际应用中的成功，已被证明是一种有效的二维降维工具。然而，在多视角学习方面，由于其仅处理以二视角特征为代表的数据的能力是有限的，而在许多现实世界的应用中，视角的数量往往更多。尽管同时探索所有可能的特征对的临时方式可以在数值上处理多视图数据，但忽略了只能通过同时探索所有特征才能发现的高阶统计量（相关信息）。因此，在本文中，我们开发了张量CCA（TCCA），它通过分析不同视角的协方差张量，直观地自然推广了CCA，以处理任意数量的视图的数据。 TCCA旨在直接最大化多个（多于两个）观点的典型相关性。至关重要的是，我们证明了多视图典型相关最大化问题等价于找到数据协方差张量的最佳秩-1近似，这可以使用众所周知的交替最小二乘（ALS）算法来有效地解决。因此，探索了包含在不同视图中的高阶相关信息，从而可以获得由所有特征共享的更可靠的公共子空间。另外还介绍了TCCA的非线性扩展。在大规模生物特征结构预测，网络广告分类和网络图像标注等多种挑战任务上的实验验证了所提方法的有效性。

##### URL
[https://arxiv.org/abs/1502.02330](https://arxiv.org/abs/1502.02330)

##### PDF
[https://arxiv.org/pdf/1502.02330](https://arxiv.org/pdf/1502.02330)

