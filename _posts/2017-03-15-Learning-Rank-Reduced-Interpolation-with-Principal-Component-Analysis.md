---
layout: post
title: "Learning Rank Reduced Interpolation with Principal Component Analysis"
date: 2017-03-15 10:22:21
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Tracking Optimization
author: Matthias Ochs, Henry Bradler, Rudolf Mester
mathjax: true
---

* content
{:toc}

##### Abstract
In computer vision most iterative optimization algorithms, both sparse and dense, rely on a coarse and reliable dense initialization to bootstrap their optimization procedure. For example, dense optical flow algorithms profit massively in speed and robustness if they are initialized well in the basin of convergence of the used loss function. The same holds true for methods as sparse feature tracking when initial flow or depth information for new features at arbitrary positions is needed. This makes it extremely important to have techniques at hand that allow to obtain from only very few available measurements a dense but still approximative sketch of a desired 2D structure (e.g. depth maps, optical flow, disparity maps, etc.). The 2D map is regarded as sample from a 2D random process. The method presented here exploits the complete information given by the principal component analysis (PCA) of that process, the principal basis and its prior distribution. The method is able to determine a dense reconstruction from sparse measurement. When facing situations with only very sparse measurements, typically the number of principal components is further reduced which results in a loss of expressiveness of the basis. We overcome this problem and inject prior knowledge in a maximum a posterior (MAP) approach. We test our approach on the KITTI and the virtual KITTI datasets and focus on the interpolation of depth maps for driving scenes. The evaluation of the results show good agreement to the ground truth and are clearly better than results of interpolation by the nearest neighbor method which disregards statistical information.

##### Abstract (translated by Google)
在计算机视觉中，大多数迭代优化算法都是稀疏和密集的，都依靠粗糙和可靠的密集初始化来引导他们的优化过程。例如，如果在所使用的损失函数收敛的盆地中进行初始化，密集的光流算法将在速度和鲁棒性方面获得巨大的收益。当需要在任意位置的新特征的初始流动或深度信息时，稀疏特征跟踪的方法也是如此。这使得具有手头技术是非常重要的，所述技术允许仅从非常少的可用测量中获得期望2D结构（例如深度图，光学流，视差图等）的密集但仍然近似的草图。 2D图被认为是2D随机过程的样本。这里介绍的方法利用了该过程的主成分分析（PCA）给出的完整信息，主要依据及其先前分布。该方法能够从稀疏测量中确定密集重建。当面对只有非常稀疏测量的情况时，通常主要分量的数量进一步减少，导致基础表达的损失。我们克服了这个问题，并以最大后验（MAP）方法注入先验知识。我们在KITTI和虚拟KITTI数据集上测试我们的方法，并着重于驾驶场景的深度图插值。结果的评估显示与实际情况很好的一致，明显优于不考虑统计信息的最近邻方法的内插结果。

##### URL
[https://arxiv.org/abs/1703.05061](https://arxiv.org/abs/1703.05061)

##### PDF
[https://arxiv.org/pdf/1703.05061](https://arxiv.org/pdf/1703.05061)

