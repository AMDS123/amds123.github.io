---
layout: post
title: "Convergence of gradient based pre-training in Denoising autoencoders"
date: 2015-02-12 04:31:36
categories: arXiv_CV
tags: arXiv_CV
author: Vamsi K Ithapu, Sathya Ravi, Vikas Singh
mathjax: true
---

* content
{:toc}

##### Abstract
The success of deep architectures is at least in part attributed to the layer-by-layer unsupervised pre-training that initializes the network. Various papers have reported extensive empirical analysis focusing on the design and implementation of good pre-training procedures. However, an understanding pertaining to the consistency of parameter estimates, the convergence of learning procedures and the sample size estimates is still unavailable in the literature. In this work, we study pre-training in classical and distributed denoising autoencoders with these goals in mind. We show that the gradient converges at the rate of $\frac{1}{\sqrt{N}}$ and has a sub-linear dependence on the size of the autoencoder network. In a distributed setting where disjoint sections of the whole network are pre-trained synchronously, we show that the convergence improves by at least $\tau^{3/4}$, where $\tau$ corresponds to the size of the sections. We provide a broad set of experiments to empirically evaluate the suggested behavior.

##### Abstract (translated by Google)
深层体系结构的成功至少部分归因于初始化网络的逐层无监督预训练。不同的论文报道了大量的实证分析，重点是良好的预培训程序的设计和实施。然而，关于参数估计的一致性，学习过程的收敛性和样本量估计的理解在文献中仍然不可用。在这项工作中，我们研究了经典和分布式去噪自动编码器的预训练，并考虑到了这些目标。我们证明梯度收敛于$ \ frac {1} {\ sqrt {N}} $的速率，并且对自动编码器网络的大小具有次线性依赖性。在分布式环境中，整个网络的不相交部分是同步预训练的，我们证明收敛性至少提高了$ \ tau ^ {3/4} $，其中$ \ tau $对应于部分的大小。我们提供了一系列广泛的实验来验证所建议的行为。

##### URL
[https://arxiv.org/abs/1502.03537](https://arxiv.org/abs/1502.03537)

##### PDF
[https://arxiv.org/pdf/1502.03537](https://arxiv.org/pdf/1502.03537)

