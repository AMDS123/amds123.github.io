---
layout: post
title: "Hyperparameter Optimization: A Spectral Approach"
date: 2018-01-20 03:49:23
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Elad Hazan, Adam Klivans, Yang Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
We give a simple, fast algorithm for hyperparameter optimization inspired by techniques from the analysis of Boolean functions. We focus on the high-dimensional regime where the canonical example is training a neural network with a large number of hyperparameters. The algorithm --- an iterative application of compressed sensing techniques for orthogonal polynomials --- requires only uniform sampling of the hyperparameters and is thus easily parallelizable. 
 Experiments for training deep neural networks on Cifar-10 show that compared to state-of-the-art tools (e.g., Hyperband and Spearmint), our algorithm finds significantly improved solutions, in some cases better than what is attainable by hand-tuning. In terms of overall running time (i.e., time required to sample various settings of hyperparameters plus additional computation time), we are at least an order of magnitude faster than Hyperband and Bayesian Optimization. We also outperform Random Search 8x. 
 Additionally, our method comes with provable guarantees and yields the first improvements on the sample complexity of learning decision trees in over two decades. In particular, we obtain the first quasi-polynomial time algorithm for learning noisy decision trees with polynomial sample complexity.

##### Abstract (translated by Google)
我们给出了一个简单，快速的超参数优化算法，这个算法受布尔函数分析技术的启发。我们关注的是典型例子是训练具有大量超参数的神经网络的高维体系。该算法---正交多项式的压缩传感技术的迭代应用---仅需要对超参数进行均匀采样，因此易于并行化。
 在Cifar-10上进行深度神经网络训练的实验表明，与最先进的工具（例如Hyperband和Spearmint）相比，我们的算法找到了显着改进的解决方案，在某些情况下，优于手工优化的解决方案。就总体运行时间（即，对超参数的各种设置进行采样所需的时间加上额外的计算时间）而言，我们至少比超频带和贝叶斯优化快一个数量级。我们也胜过随机搜索8倍。
 此外，我们的方法带有可证明的保证，并在二十多年来对学习决策树的样本复杂性进行了首次改进。具体而言，我们获得了用于学习具有多项式样本复杂度的噪声决策树的第一个准多项式时间算法。

##### URL
[http://arxiv.org/abs/1706.00764](http://arxiv.org/abs/1706.00764)

##### PDF
[http://arxiv.org/pdf/1706.00764](http://arxiv.org/pdf/1706.00764)

