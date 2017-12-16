---
layout: post
title: "Deep Convolutional Framelets: A General Deep Learning Framework for Inverse Problems"
date: 2017-11-30 07:12:01
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Deep_Learning
author: Jong Chul Ye, Yoseob Han, Eunju Cha
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning approaches have achieved significant performance improvement in various imaging problems. However, it is still unclear why these deep learning architectures work. Moreover, the link between the deep learning and the classical signal processing approaches such as wavelet, non-local processing, compressed sensing, etc, is still not well understood. To address these issues, here we show that the long-searched-for missing link is the convolutional framelets for representing a signal by convolving local and non-local bases. The convolutional framelets was originally developed to generalize the recent theory of low-rank Hankel matrix approaches, and this paper significantly extends the idea to derive a deep neural network using multi-layer convolutional framelets with perfect reconstruction (PR) under rectified linear unit (ReLU). Our analysis also shows that the popular deep network components such as residual block, redundant filter channels, and concatenated ReLU (CReLU) indeed help to achieve the PR, while the pooling and unpooling layers should be augmented with multi-resolution convolutional framelets to achieve PR condition. This discovery reveals the limitations of many existing deep learning architectures for inverse problems, and leads us to propose a novel deep convolutional framelets neural network. Using numerical experiments with sparse view x-ray computed tomography (CT), we demonstrated that our deep convolution framelets network shows consistent improvement. This discovery suggests that the success of deep learning is not from a magical power of a black-box, but rather comes from the power of a novel signal representation using non-local basis combined with data-driven local basis, which is indeed a natural extension of classical signal processing theory.

##### Abstract (translated by Google)
最近，深度学习方法在各种成像问题上取得了显着的性能提升。然而，为什么这些深度学习架构的工作还不清楚。而且，深度学习与经典信号处理方法如小波，非局部处理，压缩感知等之间的联系还不是很清楚。为了解决这些问题，在这里我们展示了长期搜索到的缺失链接是通过卷积当地和非本地基地来表示信号的卷积框架。卷积框架最初是为了推广最近的低秩Hankel矩阵方法理论而产生的，本文在整数线性单元（ReLU）下利用具有完美重构（PR）的多层卷积框架推导出深度神经网络的思想， ）。我们的分析还表明，流行的深度网络组件，如残余块，冗余过滤通道和级联的ReLU（CReLU）确实有助于实现PR，而池和非虚拟层应该用多分辨率卷积框架来增强以实现PR条件。这个发现揭示了许多现有的深度学习架构的逆问题的局限性，并导致我们提出了一种新的深度卷积框架神经网络。使用稀疏视图X射线计算机断层扫描（CT）的数值实验，我们证明了我们的深卷积框架网络显示了一致的改进。这一发现表明，深度学习的成功不是来自黑盒子的神奇力量，而是来自于使用非本地基础与数据驱动本地基础相结合的新颖信号表征的力量，这是一种天然的经典信号处理理论的延伸。

##### URL
[https://arxiv.org/abs/1707.00372](https://arxiv.org/abs/1707.00372)

##### PDF
[https://arxiv.org/pdf/1707.00372](https://arxiv.org/pdf/1707.00372)

