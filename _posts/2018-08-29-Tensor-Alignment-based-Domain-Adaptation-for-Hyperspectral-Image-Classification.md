---
layout: post
title: "Tensor Alignment based Domain Adaptation for Hyperspectral Image Classification"
date: 2018-08-29 12:51:59
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Optimization Classification
author: Yao Qin, Lorenzo Bruzzone, Biao Li, Yuanxin Ye
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a tensor alignment (TA) based domain adaptation method for hyperspectral image (HSI) classification. To be specific, HSIs in both domains are first segmented into superpixels and tensors of both domains are constructed to include neighboring samples from single superpixel. Then we consider the subspace invariance between two domains as projection matrices and original tensors are projected as core tensors with lower dimensions into the invariant tensor subspace by applying Tucker decomposition. To preserve geometric information in original tensors, we employ a manifold regularization term for core tensors into the decomposition progress. The projection matrices and core tensors are solved in an alternating optimization manner and the convergence of TA algorithm is analyzed. In addition, a post-processing strategy is defined via pure samples extraction for each superpixel to further improve classification performance. Experimental results on four real HSIs demonstrate that the proposed method can achieve better performance compared with the state-of-the-art subspace learning methods when a limited amount of source labeled samples are available.

##### Abstract (translated by Google)
本文提出了一种基于张量对齐（TA）的高光谱图像（HSI）分类域自适应方法。具体而言，两个域中的HSI首先被分割成超像素，并且两个域的张量被构造为包括来自单个超像素的相邻样本。然后我们考虑两个域之间的子空间不变性，因为投影矩阵和原始张量通过应用Tucker分解被投影为具有较低维度的核心张量到不变张量子空间中。为了保留原始张量中的几何信息，我们将核心张量的流形正则化项用于分解过程。以交替优化方式求解投影矩阵和核心张量，分析TA算法的收敛性。此外，通过对每个超像素的纯样本提取来定义后处理策略，以进一步提高分类性能。四个真实HSI的实验结果表明，当有限量的源标记样本可用时，与现有技术的子空间学习方法相比，所提出的方法可以实现更好的性能。

##### URL
[http://arxiv.org/abs/1808.09769](http://arxiv.org/abs/1808.09769)

##### PDF
[http://arxiv.org/pdf/1808.09769](http://arxiv.org/pdf/1808.09769)

