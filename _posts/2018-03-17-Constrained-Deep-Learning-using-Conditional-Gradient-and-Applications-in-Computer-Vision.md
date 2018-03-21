---
layout: post
title: "Constrained Deep Learning using Conditional Gradient and Applications in Computer Vision"
date: 2018-03-17 03:59:34
categories: arXiv_CV
tags: arXiv_CV GAN Optimization Deep_Learning Gradient_Descent
author: Sathya N. Ravi, Tuan Dinh, Vishnu Sai Rao Lokhande, Vikas Singh
mathjax: true
---

* content
{:toc}

##### Abstract
A number of results have recently demonstrated the benefits of incorporating various constraints when training deep architectures in vision and machine learning. The advantages range from guarantees for statistical generalization to better accuracy to compression. But support for general constraints within widely used libraries remains scarce and their broader deployment within many applications that can benefit from them remains under-explored. Part of the reason is that Stochastic gradient descent (SGD), the workhorse for training deep neural networks, does not natively deal with constraints with global scope very well. In this paper, we revisit a classical first order scheme from numerical optimization, Conditional Gradients (CG), that has, thus far had limited applicability in training deep models. We show via rigorous analysis how various constraints can be naturally handled by modifications of this algorithm. We provide convergence guarantees and show a suite of immediate benefits that are possible -- from training ResNets with fewer layers but better accuracy simply by substituting in our version of CG to faster training of GANs with 50% fewer epochs in image inpainting applications to provably better generalization guarantees using efficiently implementable forms of recently proposed regularizers.

##### Abstract (translated by Google)
最近，许多结果证明了在视觉和机器学习中训练深层架构时，纳入各种约束的好处。从统计泛化的保证到更好的精确性到压缩的优点。但是，对广泛使用的库中的常规约束的支持仍然很少，而且可以从中受益的许多应用程序中的更广泛的部署仍然没有得到充分研究。部分原因是，随机梯度下降（SGD）是训练深度神经网络的主力，它本身不会很好地处理全球范围内的约束。在本文中，我们从数值优化重新审视经典的一阶方案，条件梯度（CG），迄今为止在训练深度模型方面的适用性有限。我们通过严格的分析来展示如何通过修改这个算法自然地处理各种约束。我们提供了融合保证，并展示了一系列可能的直接收益 - 从更少层次但更精确的培训ResNets，只需将我们的CG版本替换为GAN更快的培训，图像修复应用程序的时代减少50％，从而更好地实现更好一般化保证使用有效实施的最近提出的正规化者的形式。

##### URL
[https://arxiv.org/abs/1803.06453](https://arxiv.org/abs/1803.06453)

##### PDF
[https://arxiv.org/pdf/1803.06453](https://arxiv.org/pdf/1803.06453)

