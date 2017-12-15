---
layout: post
title: "Graph Laplacian Regularization for Image Denoising: Analysis in the Continuous Domain"
date: 2017-08-30 12:11:26
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Jiahao Pang, Gene Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
Inverse imaging problems are inherently under-determined, and hence it is important to employ appropriate image priors for regularization. One recent popular prior---the graph Laplacian regularizer---assumes that the target pixel patch is smooth with respect to an appropriately chosen graph. However, the mechanisms and implications of imposing the graph Laplacian regularizer on the original inverse problem are not well understood. To address this problem, in this paper we interpret neighborhood graphs of pixel patches as discrete counterparts of Riemannian manifolds and perform analysis in the continuous domain, providing insights into several fundamental aspects of graph Laplacian regularization for image denoising. Specifically, we first show the convergence of the graph Laplacian regularizer to a continuous-domain functional, integrating a norm measured in a locally adaptive metric space. Focusing on image denoising, we derive an optimal metric space assuming non-local self-similarity of pixel patches, leading to an optimal graph Laplacian regularizer for denoising in the discrete domain. We then interpret graph Laplacian regularization as an anisotropic diffusion scheme to explain its behavior during iterations, e.g., its tendency to promote piecewise smooth signals under certain settings. To verify our analysis, an iterative image denoising algorithm is developed. Experimental results show that our algorithm performs competitively with state-of-the-art denoising methods such as BM3D for natural images, and outperforms them significantly for piecewise smooth images.

##### Abstract (translated by Google)
逆成像问题本质上是欠定的，因此采用适当的图像先验来进行正则化是非常重要的。一个最近流行的先验图 - 拉普拉斯正则化 - 假定目标像素块相对于适当选择的图是平滑的。然而，图拉普拉斯正则化器对原始逆问题的作用机制和含义尚不完全清楚。为了解决这个问题，本文将像素块的邻域图解释为黎曼流形的离散对应图，并在连续域进行分析，从而为图像去噪的图拉普拉斯正则化的几个基本方面提供了深刻的见解。具体来说，我们首先显示拉普拉斯正则化图的收敛到连续域函数，整合在局部自适应度量空间中测量的范数。针对图像去噪，我们推导出一个假设像素块的非局部自相似性的最优度量空间，从而导出离散域去噪的最优图拉普拉斯正则化器。然后，我们将图拉普拉斯正则化解释为各向异性扩散方案，以解释其在迭代期间的行为，例如其在某些设置下促进分段平滑信号的趋势。为了验证我们的分析，开发了一种迭代图像去噪算法。实验结果表明，我们的算法与自然图像的BM3D等最先进的去噪方法竞争，并为分段平滑的图像显着优于它们。

##### URL
[https://arxiv.org/abs/1604.07948](https://arxiv.org/abs/1604.07948)

##### PDF
[https://arxiv.org/pdf/1604.07948](https://arxiv.org/pdf/1604.07948)

