---
layout: post
title: "Non-Parametric Variational Inference with Graph Convolutional Networks for Gaussian Processes"
date: 2018-09-08 17:20:45
categories: arXiv_AI
tags: arXiv_AI CNN Optimization Inference Relation
author: Linfeng Liu, Liping Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Inference for GP models with non-Gaussian noises is computationally expensive when dealing with large datasets. Many recent inference methods approximate the posterior distribution with a simpler distribution defined on a small number of inducing points. The inference is accurate only when data points have strong correlation with these inducing points. In this paper, we consider the inference problem in a different direction: GP function values in the posterior are mostly correlated in short distance. We construct a variational distribution such that the inference for a data point considers only its neighborhood. With this construction, the variational lower bound is highly decomposible, hence we can run stochastic optimization with very small batches. We then train Graph Convolutional Networks as a reusable model to identify variational parameters for each data point. Model reuse greatly reduces the number of parameters and the number of iterations needed in optimization. The proposed method significantly speeds up the inference and often gets more accurate results than previous methods.

##### Abstract (translated by Google)
在处理大数据集时，对具有非高斯噪声的GP模型的推断在计算上是昂贵的。许多最近的推断方法近似于后验分布，在较少数量的诱导点上定义了更简单的分布。仅当数据点与这些诱导点具有强相关性时，推断才是准确的。在本文中，我们考虑了不同方向的推理问题：后验中的GP函数值大多与短距离相关。我们构造一个变分分布，使得数据点的推断仅考虑其邻域。通过这种结构，变分下界是高度可分解的，因此我们可以用非常小的批次进行随机优化。然后，我们将图形卷积网络作为可重用模型进行训练，以识别每个数据点的变分参数。模型重用大大减少了参数的数量和优化所需的迭代次数。所提出的方法显着加快了推理速度，并且通常比以前的方法获得更准确的结果。

##### URL
[http://arxiv.org/abs/1809.02838](http://arxiv.org/abs/1809.02838)

##### PDF
[http://arxiv.org/pdf/1809.02838](http://arxiv.org/pdf/1809.02838)

