---
layout: post
title: "Compressed Dynamic Mode Decomposition for Background Modeling"
date: 2016-08-25 03:09:25
categories: arXiv_CV
tags: arXiv_CV Sparse
author: N. Benjamin Erichson, Steven L. Brunton, J. Nathan Kutz
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the method of compressed dynamic mode decomposition (cDMD) for background modeling. The dynamic mode decomposition (DMD) is a regression technique that integrates two of the leading data analysis methods in use today: Fourier transforms and singular value decomposition. Borrowing ideas from compressed sensing and matrix sketching, cDMD eases the computational workload of high resolution video processing. The key principal of cDMD is to obtain the decomposition on a (small) compressed matrix representation of the video feed. Hence, the cDMD algorithm scales with the intrinsic rank of the matrix, rather then the size of the actual video (data) matrix. Selection of the optimal modes characterizing the background is formulated as a sparsity-constrained sparse coding problem. Our results show, that the quality of the resulting background model is competitive, quantified by the F-measure, Recall and Precision. A GPU (graphics processing unit) accelerated implementation is also presented which further boosts the computational efficiency of the algorithm.

##### Abstract (translated by Google)
我们介绍了用于背景建模的压缩动态模式分解（cDMD）方法。动态模式分解（DMD）是一种回归技术，它集成了目前使用的两种主要数据分析方法：傅立叶变换和奇异值分解。借助压缩传感和矩阵绘制的思想，cDMD减轻了高分辨率视频处理的计算工作量。 cDMD的关键原则是获得视频输入的（小）压缩矩阵表示的分解。因此，cDMD算法随着矩阵的内部秩而缩放，而不是实际视频（数据）矩阵的大小。表征背景的最优模式的选择被表述为稀疏约束的稀疏编码问题。我们的研究结果表明，由此产生的背景模型的质量是有竞争力的，通过F-measure，Recall和Precision来量化。还提出了GPU（图形处理单元）加速实现，这进一步提高了算法的计算效率。

##### URL
[https://arxiv.org/abs/1512.04205](https://arxiv.org/abs/1512.04205)

##### PDF
[https://arxiv.org/pdf/1512.04205](https://arxiv.org/pdf/1512.04205)

