---
layout: post
title: "Bridge the Gap Between Group Sparse Coding and Rank Minimization via Adaptive Dictionary Learning"
date: 2017-11-08 06:47:50
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhiyuan Zha, Xin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Both sparse coding and rank minimization have led to great successes in various image processing tasks. Though the underlying principles of these two approaches are similar, no theory is available to demonstrate the correspondence. In this paper, starting by designing an adaptive dictionary for each group of image patches, we analyze the sparsity of image patches in each group using the rank minimization approach. Based on this, we prove that the group-based sparse coding is equivalent to the rank minimization problem under our proposed adaptive dictionary. Therefore, the sparsity of the coefficients for each group can be measured by estimating the singular values of this group. Inspired by our theoretical analysis, four nuclear norm like minimization methods including the standard nuclear norm minimization (NNM), weighted nuclear norm minimization (WNNM), Schatten $p$-norm minimization (SNM), and weighted Schatten $p$-norm minimization (WSNM), are employed to analyze the sparsity of the coefficients and WSNM is found to be the closest solution to the singular values of each group. Based on this, WSNM is then translated to a non-convex weighted $\ell_p$-norm minimization problem in group-based sparse coding, and in order to solve this problem, a new algorithm based on the alternating direction method of multipliers (ADMM) framework is developed. Experimental results on two low-level vision tasks: image inpainting and image compressive sensing recovery, demonstrate that the proposed scheme is feasible and outperforms state-of-the-art methods.

##### Abstract (translated by Google)
稀疏编码和等级最小化在各种图像处理任务中取得了巨大的成功。尽管这两种方法的基本原理是相似的，但没有理论可用来证明这种对应关系。在本文中，首先为每组图像块设计一个自适应字典，然后利用秩最小化方法分析每组图像块的稀疏性。基于此，我们证明了基于群体的稀疏编码等价于我们提出的自适应字典下的秩最小化问题。因此，可以通过估计这个组的奇异值来测量每个组的系数的稀疏性。受到我们理论分析的启发，我们采用了最小化方法，包括标准核范数最小化（NNM），加权核范数最小化（WNNM），Schatten $ p $ -norm最小化（SNM）和加权Schatten $ p $ -norm最小化（WSNM）来分析系数的稀疏性，发现WSNM是最接近每组奇异值的解决方案。在此基础上，将WSNM转化为基于群组稀疏编码的非凸加权$ \ ell_p $ -norm最小化问题，为解决这个问题，提出了一种基于乘法器交替方向法（ADMM） ）框架开发。在两个低级视觉任务上的实验结果：图像修复和图像压缩感知恢复，证明了所提出的方案是可行的，并且胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1709.03979](https://arxiv.org/abs/1709.03979)

##### PDF
[https://arxiv.org/pdf/1709.03979](https://arxiv.org/pdf/1709.03979)

