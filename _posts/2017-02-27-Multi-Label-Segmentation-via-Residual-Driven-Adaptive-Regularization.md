---
layout: post
title: "Multi-Label Segmentation via Residual-Driven Adaptive Regularization"
date: 2017-02-27 15:50:35
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization Relation
author: Byung-Woo Hong, Ja-Keoung Koo, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We present a variational multi-label segmentation algorithm based on a robust Huber loss for both the data and the regularizer, minimized within a convex optimization framework. We introduce a novel constraint on the common areas, to bias the solution towards mutually exclusive regions. We also propose a regularization scheme that is adapted to the spatial statistics of the residual at each iteration, resulting in a varying degree of regularization being applied as the algorithm proceeds: the effect of the regularizer is strongest at initialization, and wanes as the solution increasingly fits the data. This minimizes the bias induced by the regularizer at convergence. We design an efficient convex optimization algorithm based on the alternating direction method of multipliers using the equivalent relation between the Huber function and the proximal operator of the one-norm. We empirically validate our proposed algorithm on synthetic and real images and offer an information-theoretic derivation of the cost-function that highlights the modeling choices made.

##### Abstract (translated by Google)
我们提出了一个基于稳健胡贝尔损失的数据和正则化的变分多标签分割算法，在一个凸优化框架内最小化。我们在公共领域引入新的约束，将解决方案偏向于互斥的区域。我们还提出了适应每次迭代的残差的空间统计的正则化方案，随着算法的进行，正则化的程度也不同：正规化的效果在初始化时最强，随着解决方案的增加适合数据。这最小化了正规化器在收敛时引起的偏差。利用Huber函数与一范数近似算子之间的等价关系，设计了一种基于乘子交替方向法的高效凸优化算法。我们凭经验验证了我们提出的合成和真实图像算法，并提供了信息理论推导的成本函数，突出了建模的选择。

##### URL
[https://arxiv.org/abs/1702.08336](https://arxiv.org/abs/1702.08336)

##### PDF
[https://arxiv.org/pdf/1702.08336](https://arxiv.org/pdf/1702.08336)

