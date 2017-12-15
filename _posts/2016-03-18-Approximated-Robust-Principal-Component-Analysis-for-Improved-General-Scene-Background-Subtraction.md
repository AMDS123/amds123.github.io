---
layout: post
title: "Approximated Robust Principal Component Analysis for Improved General Scene Background Subtraction"
date: 2016-03-18 13:53:26
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding
author: Salehe Erfanian Ebadi, Valia Guerra Ones, Ebroul Izquierdo
mathjax: true
---

* content
{:toc}

##### Abstract
The research reported in this paper addresses the fundamental task of separation of locally moving or deforming image areas from a static or globally moving background. It builds on the latest developments in the field of robust principal component analysis, specifically, the recently reported practical solutions for the long-standing problem of recovering the low-rank and sparse parts of a large matrix made up of the sum of these two components. This article addresses a few critical issues including: embedding global motion parameters in the matrix decomposition model, i.e., estimation of global motion parameters simultaneously with the foreground/background separation task, considering matrix block-sparsity rather than generic matrix sparsity as natural feature in video processing applications, attenuating background ghosting effects when foreground is subtracted, and more critically providing an extremely efficient algorithm to solve the low-rank/sparse matrix decomposition task. The first aspect is important for background/foreground separation in generic video sequences where the background usually obeys global displacements originated by the camera motion in the capturing process. The second aspect exploits the fact that in video processing applications the sparse matrix has a very particular structure, where the non-zero matrix entries are not randomly distributed but they build small blocks within the sparse matrix. The next feature of the proposed approach addresses removal of ghosting effects originated from foreground silhouettes and the lack of information in the occluded background regions of the image. Finally, the proposed model also tackles algorithmic complexity by introducing an extremely efficient "SVD-free" technique that can be applied in most background/foreground separation tasks for conventional video processing.

##### Abstract (translated by Google)
本文报道的研究论述了将局部移动或变形图像区域从静态或全局移动背景中分离出来的基本任务。它建立在鲁棒主成分分析领域的最新发展，特别是最近报道的用于长期恢复由这两个成分的总和构成的大矩阵的低阶和稀疏部分的实际解决方案。本文针对以下几个关键问题：将全局运动参数嵌入到矩阵分解模型中，即将全局运动参数与前景/背景分离任务同时进行估计，考虑矩阵块 - 稀疏性而不是通用矩阵稀疏性作为视频中的自然特征处理应用程序，减少前景消除时的背景重影效应，更为批判性地提供了一种解决低秩/稀疏矩阵分解任务的极其有效的算法。第一方面对于通用视频序列中的背景/前景分离是重要的，其中背景通常服从由捕捉过程中的相机运动产生的全球位移。第二个方面利用了这样一个事实，即在视频处理应用中，稀疏矩阵具有非常特殊的结构，其中非零矩阵条目不是随机分布的，而是在稀疏矩阵内构建小块。所提出的方法的下一个特征涉及消除源于前景轮廓的重影效应以及图像的遮挡的背景区域中缺少信息。最后，所提出的模型还通过引入非常有效的“无SVD”技术来处理算法的复杂性，该技术可应用于传统视频处理的大多数背景/前景分离任务。

##### URL
[https://arxiv.org/abs/1603.05875](https://arxiv.org/abs/1603.05875)

##### PDF
[https://arxiv.org/pdf/1603.05875](https://arxiv.org/pdf/1603.05875)

