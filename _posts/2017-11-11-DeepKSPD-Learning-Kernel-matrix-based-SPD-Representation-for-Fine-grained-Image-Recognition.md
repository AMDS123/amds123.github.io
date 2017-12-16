---
layout: post
title: "DeepKSPD: Learning Kernel-matrix-based SPD Representation for Fine-grained Image Recognition"
date: 2017-11-11 00:41:32
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Melih Engin, Lei Wang, Luping Zhou, Xinwang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Being symmetric positive-definite (SPD), covariance matrix has traditionally been used to represent a set of local descriptors in visual recognition. Recent study shows that kernel matrix can give considerably better representation by modelling the nonlinearity in the local descriptor set. Nevertheless, neither the descriptors nor the kernel matrix is deeply learned. Worse, they are considered separately, hindering the pursuit of an optimal SPD representation. This work proposes a deep network that jointly learns local descriptors, kernel-matrix-based SPD representation, and the classifier via an end-to-end training process. We derive the derivatives for the mapping from a local descriptor set to the SPD representation to carry out backpropagation. Also, we exploit the Daleckii-Krein formula in operator theory to give a concise and unified result on differentiating SPD matrix functions, including the matrix logarithm to handle the Riemannian geometry of kernel matrix. Experiments not only show the superiority of kernel-matrix-based SPD representation with deep local descriptors, but also verify the advantage of the proposed deep network in pursuing better SPD representations for fine-grained image recognition tasks.

##### Abstract (translated by Google)
作为对称正定（SPD），协方差矩阵传统上被用来表示视觉识别中的一组局部描述符。最近的研究表明，通过对局部描述符集合中的非线性进行建模，核矩阵可以给出相当好的表示。尽管如此，描述符和核矩阵都没有深入的学习。更糟糕的是，它们被分开考虑，阻碍了追求最佳SPD表示。这项工作提出了一个深入的网络，通过端到端的培训过程共同学习本地描述符，基于内核矩阵的SPD表示和分类器。我们推导出从局部描述符集合到SPD表示的映射以执行反向传播。同时，利用算子理论中的Daleckii-Kerin公式，给出了区分SPD矩阵函数的一个简洁统一的结果，包括处理核矩阵的黎曼几何的矩阵对数。实验不仅证明了深度局部描述符的基于核矩阵的SPD表示的优越性，而且验证了所提出的深度网络在细粒度图像识别任务中寻求更好的SPD表示的优势。

##### URL
[https://arxiv.org/abs/1711.04047](https://arxiv.org/abs/1711.04047)

##### PDF
[https://arxiv.org/pdf/1711.04047](https://arxiv.org/pdf/1711.04047)

