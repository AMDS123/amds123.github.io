---
layout: post
title: "Fast Piecewise-Affine Motion Estimation Without Segmentation"
date: 2018-02-06 10:15:30
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Optimization
author: Denis Fortun, Martin Storath, Dennis Rickert, Andreas Weinmann, Michael Unser
mathjax: true
---

* content
{:toc}

##### Abstract
Current algorithmic approaches for piecewise affine motion estimation are based on alternating motion segmentation and estimation. We propose a new method to estimate piecewise affine motion fields directly without intermediate segmentation. To this end, we reformulate the problem by imposing piecewise constancy of the parameter field, and derive a specific proximal splitting optimization scheme. A key component of our framework is an efficient one-dimensional piecewise-affine estimator for vector-valued signals. The first advantage of our approach over segmentation-based methods is its absence of initialization. The second advantage is its lower computational cost which is independent of the complexity of the motion field. In addition to these features, we demonstrate competitive accuracy with other piecewise-parametric methods on standard evaluation benchmarks. Our new regularization scheme also outperforms the more standard use of total variation and total generalized variation.

##### Abstract (translated by Google)
当前用于分段仿射运动估计的算法方法基于交替运动分割和估计。我们提出了一种直接估计分段仿射运动场的新方法，没有中间分割。为此，我们通过对参数域进行分段不变性来重构问题，并导出一个特定的近端分裂优化方案。我们框架的一个关键组成部分是矢量值信号的一个有效的一维分段仿射估计器。我们的基于分段的方法的第一个优点是缺少初始化。第二个优点是它的计算成本更低，而且与运动场的复杂性无关。除了这些特征之外，我们还用标准评估基准上的其他分段参数方法来证明其有竞争力。我们的新的正则化方案也超越了总体变化和总体广义变化的更加标准的使用。

##### URL
[http://arxiv.org/abs/1802.01872](http://arxiv.org/abs/1802.01872)

##### PDF
[http://arxiv.org/pdf/1802.01872](http://arxiv.org/pdf/1802.01872)

