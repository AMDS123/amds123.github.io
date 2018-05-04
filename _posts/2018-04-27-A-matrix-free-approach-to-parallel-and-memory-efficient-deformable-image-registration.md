---
layout: post
title: "A matrix-free approach to parallel and memory-efficient deformable image registration"
date: 2018-04-27 14:52:41
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Lars König, Jan Rühaak, Alexander Derksen, Jan Lellmann
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel computational approach to fast and memory-efficient deformable image registration. In the variational registration model, the computation of the objective function derivatives is the computationally most expensive operation, both in terms of runtime and memory requirements. In order to target this bottleneck, we analyze the matrix structure of gradient and Hessian computations for the case of the normalized gradient fields distance measure and curvature regularization. Based on this analysis, we derive equivalent matrix-free closed-form expressions for derivative computations, eliminating the need for storing intermediate results and the costs of sparse matrix arithmetic. This has further benefits: (1) matrix computations can be fully parallelized, (2) memory complexity for derivative computation is reduced from linear to constant, and (3) overall computation times are substantially reduced. In comparison with an optimized matrix-based reference implementation, the CPU implementation achieves speedup factors between 3.1 and 9.7, and we are able to handle substantially higher resolutions. Using a GPU implementation, we achieve an additional speedup factor of up to 9.2. Furthermore, we evaluated the approach on real-world medical datasets. On ten publicly available lung CT images from the DIR-Lab 4DCT dataset, we achieve the best mean landmark error of 0.93 mm compared to other submissions on the DIR-Lab website, with an average runtime of only 9.23 s. Complete non-rigid registration of full-size 3D thorax-abdomen CT volumes from oncological follow-up is achieved in 12.6 s. The experimental results show that the proposed matrix-free algorithm enables the use of variational registration models also in applications which were previously impractical due to memory or runtime restrictions.

##### Abstract (translated by Google)
我们提出了一种新的计算方法来快速和有效地记忆变形图像。在变分配准模型中，目标函数导数的计算在运算和内存要求方面都是计算上最昂贵的操作。为了解决这个瓶颈，我们分析了归一化梯度场距离测度和曲率正则化情况下梯度和Hessian计算的矩阵结构。基于这种分析，我们导出了导数计算的等效无矩阵闭式表达式，无需存储中间结果和稀疏矩阵算法的成本。这进一步的好处是：（1）矩阵计算可以完全并行化，（2）导数计算的存储器复杂度从线性降低到常数，（3）整体计算时间大大减少。与优化的基于矩阵的参考实现相比，CPU实现实现了3.1和9.7之间的加速因子，并且我们能够处理更高的分辨率。使用GPU实现，我们实现了高达9.2的额外加速因子。此外，我们评估了真实世界医学数据集的方法。在DIR-Lab 4DCT数据集的10个公开可用的肺部CT图像中，与DIR-Lab网站上的其他提交文件相比，我们获得0.93 mm的最佳平均标记误差，平均运行时间仅为9.23 s。在12.6秒内完成肿瘤随访的全尺寸3D胸腹部CT非完整定位。实验结果表明，所提出的无矩阵算法能够在由于存储器或运行时限制而在以前不实用的应用中使用变分配准模型。

##### URL
[https://arxiv.org/abs/1804.10541](https://arxiv.org/abs/1804.10541)

##### PDF
[https://arxiv.org/pdf/1804.10541](https://arxiv.org/pdf/1804.10541)

