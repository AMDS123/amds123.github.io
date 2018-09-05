---
layout: post
title: "Memory-Efficient Global Refinement of Decision-Tree Ensembles and its Application to Face Alignment"
date: 2018-09-03 08:49:21
categories: arXiv_CV
tags: arXiv_CV Face
author: Nenad Marku&#x161;, Ivan Gogi&#x107;, Igor S. Pand&#x17e;i&#x107;, J&#xf6;rgen Ahlberg
mathjax: true
---

* content
{:toc}

##### Abstract
Ren et al. recently introduced a method for aggregating multiple decision trees into a strong predictor by interpreting a path taken by a sample down each tree as a binary vector and performing linear regression on top of these vectors stacked together. They provided experimental evidence that the method offers advantages over the usual approaches for combining decision trees (random forests and boosting). The method truly shines when the regression target is a large vector with correlated dimensions, such as a 2D face shape represented with the positions of several facial landmarks. However, we argue that their basic method is not applicable in many practical scenarios due to large memory requirements. This paper shows how this issue can be solved through the use of quantization and architectural changes of the predictor that maps decision tree-derived encodings to the desired output.

##### Abstract (translated by Google)
任等人。最近推出了一种方法，通过将每个树下采样的路径解释为二元向量并在堆叠在一起的这些向量之上执行线性回归，将多个决策树聚合成强预测器。他们提供了实验证据，证明该方法优于结合决策树（随机森林和增强）的常规方法。当回归目标是具有相关尺寸的大矢量时，该方法真正闪耀，例如用几个面部标志的位置表示的2D面部形状。但是，我们认为由于存储器需求量大，它们的基本方法在许多实际场景中都不适用。本文展示了如何通过使用预测器的量化和架构变化来解决这个问题，该预测器将决策树派生的编码映射到所需的输出。

##### URL
[http://arxiv.org/abs/1702.08481](http://arxiv.org/abs/1702.08481)

##### PDF
[http://arxiv.org/pdf/1702.08481](http://arxiv.org/pdf/1702.08481)

