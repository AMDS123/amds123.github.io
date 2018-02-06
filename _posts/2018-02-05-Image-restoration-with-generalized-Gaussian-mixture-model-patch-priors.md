---
layout: post
title: "Image restoration with generalized Gaussian mixture model patch priors"
date: 2018-02-05 15:18:21
categories: arXiv_CV
tags: arXiv_CV Classification
author: Charles-Alban Deledalle (IMB, UCSD), Shibin Parameswaran (UCSD), Truong Q. Nguyen (UCSD)
mathjax: true
---

* content
{:toc}

##### Abstract
Patch priors have became an important component of image restoration. A powerful approach in this category of restoration algorithms is the popular Expected Patch Log-likelihood (EPLL) algorithm. EPLL uses a Gaussian mixture model (GMM) prior learned on clean image patches as a way to regularize degraded patches. In this paper, we show that a generalized Gaussian mixture model (GGMM) captures the underlying distribution of patches better than a GMM. Even though GGMM is a powerful prior to combine with EPLL, the non-Gaussianity of its components presents major challenges to be applied to a computationally intensive process of image restoration. Specifically, each patch has to undergo a patch classification step and a shrinkage step. These two steps can be efficiently solved with a GMM prior but are computationally impractical when using a GGMM prior. In this paper, we provide approximations and computational recipes for fast evaluation of these two steps, so that EPLL can embed a GGMM prior on an image with more than tens of thousands of patches. Our main contribution is to analyze the accuracy of our approximations based on thorough theoretical analysis. Our evaluations indicate that the GGMM prior is consistently a better fit for modeling image patch distribution and performs better on average in image denoising task.

##### Abstract (translated by Google)
补丁已经成为图像恢复的重要组成部分。在这类恢复算法中，强大的方法是流行的预期修补对数似然（EPLL）算法。 EPLL使用高斯混合模型（GMM）之前学习干净的图像补丁作为一种方法来规范退化的补丁。在本文中，我们展示了广义高斯混合模型（GGMM）比GMM更好地捕获了补丁的基本分布。尽管GGMM在与EPLL相结合之前是一个强大的功能，但其组件的非高斯性给应用于计算密集型图像恢复过程带来了巨大的挑战。具体而言，每个贴片必须经历贴片分类步骤和收缩步骤。这两个步骤可以先用GMM有效地解决，但在使用GGMM之前在计算上是不切实际的。在本文中，我们提供了用于快速评估这两个步骤的近似值和计算配方，以便EPLL可以在具有数万个补丁的图像之前嵌入GGMM。我们的主要贡献是基于彻底的理论分析来分析我们的近似值的准确性。我们的评估表明，GGMM之前是一贯更适合建模图像补丁分布，并在图像去噪任务平均表现更好。

##### URL
[http://arxiv.org/abs/1802.01458](http://arxiv.org/abs/1802.01458)

##### PDF
[http://arxiv.org/pdf/1802.01458](http://arxiv.org/pdf/1802.01458)

