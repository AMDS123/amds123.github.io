---
layout: post
title: "ISTA-Net: Iterative Shrinkage-Thresholding Algorithm Inspired Deep Network for Image Compressive Sensing"
date: 2017-06-24 09:02:21
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization
author: Jian Zhang, Bernard Ghanem
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional methods for image compressive sensing (CS) reconstruction solve a well-defined inverse problem that is based on a predefined CS model, which defines the underlying structure of the problem and is generally solved by employing convergent iterative solvers. These optimization-based CS methods face the challenge of choosing optimal transforms and tuning parameters in their solvers, while also suffering from high computational complexity in most cases. Recently, some deep network based CS algorithms have been proposed to improve CS reconstruction performance, while dramatically reducing time complexity as compared to optimization-based methods. Despite their impressive results, the proposed networks (either with fully-connected or repetitive convolutional layers) lack any structural diversity and they are trained as a black box, void of any insights from the CS domain. In this paper, we combine the merits of both types of CS methods: the structure insights of optimization-based method and the performance/speed of network-based ones. We propose a novel structured deep network, dubbed ISTA-Net, which is inspired by the Iterative Shrinkage-Thresholding Algorithm (ISTA) for optimizing a general $l_1$ norm CS reconstruction model. ISTA-Net essentially implements a truncated form of ISTA, where all ISTA-Net parameters are learned end-to-end to minimize a reconstruction error in training. Borrowing more insights from the optimization realm, we propose an accelerated version of ISTA-Net, dubbed FISTA-Net, which is inspired by the fast iterative shrinkage-thresholding algorithm (FISTA). Interestingly, this acceleration naturally leads to skip connections in the underlying network design. Extensive CS experiments demonstrate that the proposed ISTA-Net and FISTA-Net outperform existing optimization-based and network-based CS methods by large margins, while maintaining a fast runtime.

##### Abstract (translated by Google)
图像压缩感知（CS）重建的传统方法解决了基于预定义的CS模型的定义明确的反问题，其定义了问题的底层结构，并且通常采用收敛迭代求解器来解决。这些基于优化的CS方法面临着在求解器中选择最优变换和调整参数的挑战，同时在大多数情况下也面临着高计算复杂性。近来，已经提出了一些基于深度网络的CS算法来改善CS重构性能，同时相比于基于优化的方法，显着降低了时间复杂度。尽管他们的结果令人印象深刻，但是所提出的网络（无论是完全连接的还是重复的卷积层）都缺乏结构多样性，并且被训练成一个黑盒子，没有来自CS域的任何见解。在本文中，我们结合两种CS方法的优点：基于优化的方法的结构洞察和基于网络的方法的性能/速度。我们提出了一个新的结构化的深度网络，被称为ISTA-Net，它受到迭代收缩阈值算法（ISTA）的启发，用于优化一个通用的$ l_1 $标准的CS重建模型。 ISTA-Net实质上实现了截断形式的ISTA，其中所有的ISTA-Net参数被端到端地学习以最小化训练中的重构错误。借鉴优化领域的更多见解，我们提出了一个被称为FISTA-Net的ISTA-Net的加速版本，它受快速迭代收缩阈值算法（FISTA）的启发。有趣的是，这种加速自然导致底层网络设计中的跳过连接。广泛的CS实验表明，所提出的ISTA-Net和FISTA-Net在性能上优于现有的基于优化的和基于网络的CS方法，同时保持快速的运行时间。

##### URL
[https://arxiv.org/abs/1706.07929](https://arxiv.org/abs/1706.07929)

##### PDF
[https://arxiv.org/pdf/1706.07929](https://arxiv.org/pdf/1706.07929)

