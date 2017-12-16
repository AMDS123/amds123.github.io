---
layout: post
title: "Group Sparsity Residual Constraint for Image Denoising"
date: 2017-07-31 16:42:43
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhiyuan Zha, Xinggan Zhang, Qiong Wang, Lan Tang, Xin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Group-based sparse representation has shown great potential in image denoising. However, most existing methods only consider the nonlocal self-similarity (NSS) prior of noisy input image. That is, the similar patches are collected only from degraded input, which makes the quality of image denoising largely depend on the input itself. However, such methods often suffer from a common drawback that the denoising performance may degrade quickly with increasing noise levels. In this paper we propose a new prior model, called group sparsity residual constraint (GSRC). Unlike the conventional group-based sparse representation denoising methods, two kinds of prior, namely, the NSS priors of noisy and pre-filtered images, are used in GSRC. In particular, we integrate these two NSS priors through the mechanism of sparsity residual, and thus, the task of image denoising is converted to the problem of reducing the group sparsity residual. To this end, we first obtain a good estimation of the group sparse coefficients of the original image by pre-filtering, and then the group sparse coefficients of the noisy image are used to approximate this estimation. To improve the accuracy of the nonlocal similar patch selection, an adaptive patch search scheme is designed. Furthermore, to fuse these two NSS prior better, an effective iterative shrinkage algorithm is developed to solve the proposed GSRC model. Experimental results demonstrate that the proposed GSRC modeling outperforms many state-of-the-art denoising methods in terms of the objective and the perceptual metrics.

##### Abstract (translated by Google)
基于分组的稀疏表示在图像去噪方面显示出巨大的潜力。然而，大多数现有的方法只考虑噪声输入图像之前的非局部自相似性（NSS）。也就是说，类似的斑块只能从恶化的输入中收集，这使得图像去噪的质量在很大程度上取决于输入本身。然而，这种方法经常会遇到一个共同的缺点，即随着噪声水平的增加，去噪性能可能会迅速降低。在本文中，我们提出了一个新的先验模型，称为群体稀疏残差约束（GSRC）。与传统的基于群组的稀疏表示去噪方法不同，在GSRC中使用了两种先前的，即具有噪声和预滤波图像的NSS先验。特别是通过稀疏残差机制，将这两个NSS优先结合起来，从而将图像去噪任务转化为减少群体稀疏残差的问题。为此，我们首先通过预滤波对原始图像的组稀疏系数进行较好的估计，然后利用噪声图像的组稀疏系数来近似估计。为提高非局部相似斑块选择的准确性，设计了一种自适应斑块搜索方案。此外，为了更好地融合这两个NSS，提出了一种有效的迭代收缩算法来解决所提出的GSRC模型。实验结果表明，所提出的GSRC建模在目标和感知度量方面优于许多最先进的去噪方法。

##### URL
[https://arxiv.org/abs/1703.00297](https://arxiv.org/abs/1703.00297)

##### PDF
[https://arxiv.org/pdf/1703.00297](https://arxiv.org/pdf/1703.00297)

