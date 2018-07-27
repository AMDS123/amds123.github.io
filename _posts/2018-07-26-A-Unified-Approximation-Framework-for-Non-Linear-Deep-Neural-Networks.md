---
layout: post
title: "A Unified Approximation Framework for Non-Linear Deep Neural Networks"
date: 2018-07-26 13:36:19
categories: arXiv_AI
tags: arXiv_AI Sparse CNN
author: Yuzhe Ma, Ran Chen, Wei Li, Fanhua Shang, Wenjian Yu, Minsik Cho, Bei Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have achieved significant success in a variety of real world applications. However, tons of parameters in the networks restrict the efficiency of neural networks due to the large model size and the intensive computation. To address this issue, various compression and acceleration techniques have been investigated, among which low-rank filters and sparse filters are heavily studied. In this paper we propose a unified framework to compress the convolutional neural networks by combining these two strategies, while taking the nonlinear activation into consideration. The filer of a layer is approximated by the sum of a sparse component and a low-rank component, both of which are in favor of model compression. Especially, we constrain the sparse component to be structured sparse which facilitates acceleration. The performance of the network is retained by minimizing the reconstruction error of the feature maps after activation of each layer, using the alternating direction method of multipliers (ADMM). The experimental results show that our proposed approach can compress VGG-16 and AlexNet by over 4X. In addition, 2.2X and 1.1X speedup are achieved on VGG-16 and AlexNet, respectively, at a cost of less increase on error rate.

##### Abstract (translated by Google)
深度神经网络（DNN）在各种现实世界的应用中取得了巨大的成功。然而，由于模型尺寸大且计算密集，网络中的大量参数限制了神经网络的效率。为了解决这个问题，已经研究了各种压缩和加速技术，其中大量研究了低秩滤波器和稀疏滤波器。在本文中，我们提出了一个统一的框架，通过结合这两种策略来压缩卷积神经网络，同时考虑非线性激活。层的文件管理器由稀疏组件和低秩组件的总和近似，这两者都有利于模型压缩。特别是，我们将稀疏分量约束为稀疏的结构，这有利于加速。使用乘法器的交替方向方法（ADMM），通过在激活每层之后最小化特征图的重建误差来保持网络的性能。实验结果表明，我们提出的方法可以将VGG-16和AlexNet压缩4倍以上。此外，VGG-16和AlexNet分别实现了2.2倍和1.1倍的加速，但错误率的增加较少。

##### URL
[http://arxiv.org/abs/1807.10119](http://arxiv.org/abs/1807.10119)

##### PDF
[http://arxiv.org/pdf/1807.10119](http://arxiv.org/pdf/1807.10119)

