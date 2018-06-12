---
layout: post
title: "Image denoising with generalized Gaussian mixture model patch priors"
date: 2018-06-11 13:00:13
categories: arXiv_CV
tags: arXiv_CV Classification
author: Charles-Alban Deledalle (IMB, UCSD), Shibin Parameswaran (UCSD), Truong Q. Nguyen (UCSD)
mathjax: true
---

* content
{:toc}

##### Abstract
Patch priors have become an important component of image restoration. A powerful approach in this category of restoration algorithms is the popular Expected Patch Log-Likelihood (EPLL) algorithm. EPLL uses a Gaussian mixture model (GMM) prior learned on clean image patches as a way to regularize degraded patches. In this paper, we show that a generalized Gaussian mixture model (GGMM) captures the underlying distribution of patches better than a GMM. Even though GGMM is a powerful prior to combine with EPLL, the non-Gaussianity of its components presents major challenges to be applied to a computationally intensive process of image restoration. Specifically, each patch has to undergo a patch classification step and a shrinkage step. These two steps can be efficiently solved with a GMM prior but are computationally impractical when using a GGMM prior. In this paper, we provide approximations and computational recipes for fast evaluation of these two steps, so that EPLL can embed a GGMM prior on an image with more than tens of thousands of patches. Our main contribution is to analyze the accuracy of our approximations based on thorough theoretical analysis. Our evaluations indicate that the GGMM prior is consistently a better fit formodeling image patch distribution and performs better on average in image denoising task.

##### Abstract (translated by Google)
修补程序的先期已成为图像修复的重要组成部分。这种恢复算法的强大方法是流行的预期补丁对数似然（EPLL）算法。 EPLL在清洁图像补丁上学习之前使用高斯混合模型（GMM）作为调整降级补丁的方法。在本文中，我们展示了广义高斯混合模型（GGMM）比GMM更好地捕获补丁的基本分布。尽管GGMM在结合EPLL之前是一个强大的功能，但其组件的非高斯性仍然是应用于计算密集型图像恢复过程的主要挑战。具体而言，每个补丁必须经历补丁分类步骤和收缩步骤。这两个步骤可以先用GMM有效解决，但在使用GGMM之前在计算上不切实际。在本文中，我们提供了用于快速评估这两个步骤的近似值和计算配方，以便EPLL可以在具有数万个补丁的图像之前嵌入GGMM。我们的主要贡献是基于彻底的理论分析来分析我们的近似值的准确性。我们的评估表明，GGMM之前一直是一个更好的合适的形状图像补丁分布，并在图像去噪任务中平均执行得更好。

##### URL
[http://arxiv.org/abs/1802.01458](http://arxiv.org/abs/1802.01458)

##### PDF
[http://arxiv.org/pdf/1802.01458](http://arxiv.org/pdf/1802.01458)

