---
layout: post
title: "2PFPCE: Two-Phase Filter Pruning Based on Conditional Entropy"
date: 2018-09-06 21:13:00
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference Classification
author: Chuhan Min, Aosen Wang, Yiran Chen, Wenyao Xu, Xin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks~(CNNs) offer remarkable performance of classifications and regressions in many high-dimensional problems and have been widely utilized in real-word cognitive applications. However, high computational cost of CNNs greatly hinder their deployment in resource-constrained applications, real-time systems and edge computing platforms. To overcome this challenge, we propose a novel filter-pruning framework, two-phase filter pruning based on conditional entropy, namely \textit{2PFPCE}, to compress the CNN models and reduce the inference time with marginal performance degradation. In our proposed method, we formulate filter pruning process as an optimization problem and propose a novel filter selection criteria measured by conditional entropy. Based on the assumption that the representation of neurons shall be evenly distributed, we also develop a maximum-entropy filter freeze technique that can reduce over fitting. Two filter pruning strategies -- global and layer-wise strategies, are compared. Our experiment result shows that combining these two strategies can achieve a higher neural network compression ratio than applying only one of them under the same accuracy drop threshold. Two-phase pruning, that is, combining both global and layer-wise strategies, achieves 10 X FLOPs reduction and 46% inference time reduction on VGG-16, with 2% accuracy drop.

##### Abstract (translated by Google)
深度卷积神经网络〜（CNNs）在许多高维问题中提供了显着的分类和回归性能，并已广泛应用于实际单词认知应用中。然而，CNN的高计算成本极大地阻碍了它们在资源受限的应用，实时系统和边缘计算平台中的部署。为了克服这一挑战，我们提出了一种新颖的滤波器修剪框架，基于条件熵的两相滤波器修剪，即\ textit {2PFPCE}，用于压缩CNN模型并减少推理时间，同时降低边际性能。在我们提出的方法中，我们将滤波器修剪过程作为优化问题，并提出一种新的过滤器选择标准，通过条件熵测量。基于神经元表示应均匀分布的假设，我们还开发了一种可以减少过拟合的最大熵滤波器冻结技术。比较了两种过滤器修剪策略 - 全局策略和分层策略。我们的实验结果表明，在相同的精度下降阈值下，结合这两种策略可以实现比仅应用其中一种策略更高的神经网络压缩比。两阶段修剪，即结合全局和分层策略，在VGG-16上实现10 X FLOP减少和46％推理时间减少，精度下降2％。

##### URL
[http://arxiv.org/abs/1809.02220](http://arxiv.org/abs/1809.02220)

##### PDF
[http://arxiv.org/pdf/1809.02220](http://arxiv.org/pdf/1809.02220)

