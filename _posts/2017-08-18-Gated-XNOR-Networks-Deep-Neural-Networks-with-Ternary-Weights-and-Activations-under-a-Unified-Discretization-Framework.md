---
layout: post
title: "Gated XNOR Networks: Deep Neural Networks with Ternary Weights and Activations under a Unified Discretization Framework"
date: 2017-08-18 07:43:44
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Lei Deng, Peng Jiao, Jing Pei, Zhenzhi Wu, Guoqi Li
mathjax: true
---

* content
{:toc}

##### Abstract
There is a pressing need to build an architecture that could subsume these networks undera unified framework that achieves both higher performance and less overhead. To this end, two fundamental issues are yet to be addressed. The first one is how to implement the back propagation when neuronal activations are discrete. The second one is how to remove the full-precision hidden weights in the training phase to break the bottlenecks of memory/computation consumption. To address the first issue, we present a multistep neuronal activation discretization method and a derivative approximation technique that enable the implementing the back propagation algorithm on discrete DNNs. While for the second issue, we propose a discrete state transition (DST) methodology to constrain the weights in a discrete space without saving the hidden weights. In this way, we build a unified framework that subsumes the binary or ternary networks as its special cases.More particularly, we find that when both the weights and activations become ternary values, the DNNs can be reduced to gated XNOR networks (or sparse binary networks) since only the event of non-zero weight and non-zero activation enables the control gate to start the XNOR logic operations in the original binary networks. This promises the event-driven hardware design for efficient mobile intelligence. We achieve advanced performance compared with state-of-the-art algorithms. Furthermore,the computational sparsity and the number of states in the discrete space can be flexibly modified to make it suitable for various hardware platforms.

##### Abstract (translated by Google)
现在迫切需要构建一个体系结构，将这些网络包含在低于统一的框架中，从而实现更高的性能和更低的开销。为此，两个基本问题尚待解决。第一个是如何实现神经元激活离散时的反向传播。二是如何去除训练阶段的全精度隐藏权重，打破内存/计算消耗的瓶颈。为了解决第一个问题，我们提出了一个多步神经元激活离散化方法和一个衍生逼近技术，使得能够实现在离散DNN上的反向传播算法。而对于第二个问题，我们提出了一个离散状态转移（DST）方法来约束离散空间中的权重而不保存隐藏的权重。通过这种方式，我们构建了一个包含二元或三元网络的统一框架作为其特殊情况。更具体地说，我们发现，当权值和激活都成为三值时，DNN可以归结为门控XNOR网络（或稀疏二​​进制网络），因为只有非零权重和非零激活事件才能使控制门在原始二进制网络中启动XNOR逻辑运算。这保证了高效的移动智能的事件驱动的硬件设计。与最先进的算法相比，我们实现了先进的性能。此外，离散空间中的计算稀疏性和状态数可以灵活地修改，以适应各种硬件平台。

##### URL
[https://arxiv.org/abs/1705.09283](https://arxiv.org/abs/1705.09283)

##### PDF
[https://arxiv.org/pdf/1705.09283](https://arxiv.org/pdf/1705.09283)

