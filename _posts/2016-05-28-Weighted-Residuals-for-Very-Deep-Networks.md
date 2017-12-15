---
layout: post
title: "Weighted Residuals for Very Deep Networks"
date: 2016-05-28 02:13:32
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Falong Shen, Gang Zeng
mathjax: true
---

* content
{:toc}

##### Abstract
Deep residual networks have recently shown appealing performance on many challenging computer vision tasks. However, the original residual structure still has some defects making it difficult to converge on very deep networks. In this paper, we introduce a weighted residual network to address the incompatibility between \texttt{ReLU} and element-wise addition and the deep network initialization problem. The weighted residual network is able to learn to combine residuals from different layers effectively and efficiently. The proposed models enjoy a consistent improvement over accuracy and convergence with increasing depths from 100+ layers to 1000+ layers. Besides, the weighted residual networks have little more computation and GPU memory burden than the original residual networks. The networks are optimized by projected stochastic gradient descent. Experiments on CIFAR-10 have shown that our algorithm has a \emph{faster convergence speed} than the original residual networks and reaches a \emph{high accuracy} at 95.3\% with a 1192-layer model.

##### Abstract (translated by Google)
最近，深度残留网络在许多具有挑战性的计算机视觉任务上表现出令人满意的性能但是，原有的残差结构仍然存在一些缺陷，难以在很深的网络上进行融合。在本文中，我们引入了一个加权残差网络来解决ReLU和元素加法之间的不兼容以及深度网络初始化问题。加权残差网络能够学习将不同层次的残差有效地组合起来。所提出的模型在准确性和收敛性方面有着一致的改进，随着深度从100+层增加到1000+层。此外，加权残差网络的计算量和GPU内存负担要比原有的剩余网络少得多。网络通过投影随机梯度下降进行优化。在CIFAR-10上的实验表明，我们的算法具有比原始残差网络更快的收敛速度，并且在1192层模型下达到了95.3％的高精度。

##### URL
[https://arxiv.org/abs/1605.08831](https://arxiv.org/abs/1605.08831)

##### PDF
[https://arxiv.org/pdf/1605.08831](https://arxiv.org/pdf/1605.08831)

