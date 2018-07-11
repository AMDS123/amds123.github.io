---
layout: post
title: "Parallax Bundle Adjustment on Manifold with Convexified Initialization"
date: 2018-07-10 10:11:05
categories: arXiv_RO
tags: arXiv_RO
author: Liyang Liu, Teng Zhang, Yi Liu, Brenton Leighton, Liang Zhao, Shoudong Huang, Gamini Dissanayake
mathjax: true
---

* content
{:toc}

##### Abstract
Bundle adjustment (BA) with parallax angle based feature parameterization has been shown to have superior performance over BA using inverse depth or XYZ feature forms. In this paper, we propose an improved version of the parallax BA algorithm (PMBA) by extending it to the manifold domain along with observation-ray based objective function. With this modification, the problem formulation faithfully mimics the projective nature in a camera's image formation, BA is able to achieve better convergence, accuracy and robustness. This is particularly useful in handling diverse outdoor environments and collinear motion modes. Capitalizing on these properties, we further propose a pose-graph simplification to PMBA, with significant dimensionality reduction. This pose-graph model is convex in nature, easy to solve and its solution can serve as a good initial guess to the original BA problem which is intrinsically non-convex. We provide theoretical proof that our global initialization strategy can guarantee a near-optimal solution. Using a series of experiments involving diverse environmental conditions and motions, we demonstrate PMBA's superior convergence performance in comparison to other BA methods. We also show that, without incremental initialization or via third-party information, our global initialization process helps to bootstrap the full BA successfully in various scenarios, sequential or out-of-order, including some datasets from the "Bundle Adjustment in the Large" database.

##### Abstract (translated by Google)
基于视差角的特征参数化的束调整（BA）已被证明具有优于使用逆深度或XYZ特征形式的BA的性能。在本文中，我们提出了视差BA算法（PMBA）的改进版本，通过将其扩展到流形域以及基于观察射线的目标函数。通过这种修改，问题公式忠实地模仿了相机图像形成中的投射性质，BA能够实现更好的收敛性，准确性和鲁棒性。这在处理各种户外环境和共线运动模式时特别有用。利用这些属性，我们进一步提出了对PMBA的姿势图简化，显着降低了维数。该姿势图模型本质上是凸的，易于求解，并且其解决方案可以作为原始BA问题的良好初始猜测，其本质上是非凸的。我们提供理论证明，我们的全局初始化策略可以保证近乎最优的解决方案。通过一系列涉及不同环境条件和运动的实验，我们证明了PMBA与其他BA方法相比具有卓越的收敛性能。我们还表明，在没有增量初始化或通过第三方信息的情况下，我们的全局初始化过程有助于在各种情况下顺序或无序地成功引导完整的BA，包括来自“大型捆绑调整”中的一些数据集数据库。

##### URL
[http://arxiv.org/abs/1807.03556](http://arxiv.org/abs/1807.03556)

##### PDF
[http://arxiv.org/pdf/1807.03556](http://arxiv.org/pdf/1807.03556)

