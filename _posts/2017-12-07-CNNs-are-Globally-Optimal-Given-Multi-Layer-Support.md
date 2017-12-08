---
layout: post
title: "CNNs are Globally Optimal Given Multi-Layer Support"
date: 2017-12-07 06:06:52
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Chen Huang, Chen Kong, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
Stochastic Gradient Descent (SGD) is the central workhorse for training modern CNNs. Although giving impressive empirical performance it can be slow to converge. In this paper we explore a novel strategy for training a CNN using an alternation strategy that offers substantial speedups during training. We make the following contributions: (i) replace the ReLU non-linearity within a CNN with positive hard-thresholding, (ii) reinterpret this non-linearity as a binary state vector making the entire CNN linear if the multi-layer support is known, and (iii) demonstrate that under certain conditions a global optima to the CNN can be found through local descent. We then employ a novel alternation strategy (between weights and support) for CNN training that leads to substantially faster convergence rates, nice theoretical properties, and achieving state of the art results across large scale datasets (e.g. ImageNet) as well as other standard benchmarks.

##### Abstract (translated by Google)
随机梯度下降（SGD）是培训现代有线电视网络的主要力量。虽然给人印象深刻的经验表现，它可能是缓慢的趋同。在本文中，我们探索一种新的培训CNN的策略，使用交替策略，在培训期间提供大幅加速。我们做出如下贡献：（i）用正的硬阈值替换CNN内的ReLU非线性，（ii）将该非线性重新解释为二进制状态向量，如果多层支持是已知的，则使整个CNN线性（iii）证明在某些情况下，可以通过当地血统找到对CNN的全球最佳状态。然后，我们采用一种新颖的CNN训练交替策略（加权和支持之间），从而大大加快了收敛速度，获得了理想的性能，并在大规模数据集（如ImageNet）以及其他标准基准测试中获得了最先进的结果。

##### URL
[http://arxiv.org/abs/1712.02501](http://arxiv.org/abs/1712.02501)

##### PDF
[http://arxiv.org/pdf/1712.02501](http://arxiv.org/pdf/1712.02501)

