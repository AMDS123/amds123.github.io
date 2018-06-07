---
layout: post
title: "Regularization by Denoising: Clarifications and New Interpretations"
date: 2018-06-06 16:49:59
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Edward T. Reehorst, Philip Schniter
mathjax: true
---

* content
{:toc}

##### Abstract
Regularization by Denoising (RED), as recently proposed by Romano, Elad, and Milanfar, is powerful new image-recovery framework that aims to construct an explicit regularization objective from a plug-in image-denoising function. Evidence suggests that the RED algorithms are, indeed, state-of-the-art. However, a closer inspection suggests that explicit regularization may not explain the workings of these algorithms. In this paper, we clarify that the expressions in Romano et al. hold only when the denoiser has a symmetric Jacobian, and we demonstrate that such symmetry does not occur with practical denoisers such as non-local means, BM3D, TNRD, and DnCNN. Going further, we prove that non-symmetric denoising functions cannot be modeled by any explicit regularizer. In light of these results, there remains the question of how to justify the good-performing RED algorithms for practical denoisers. In response, we propose a new framework called "score-matching by denoising" (SMD), which aims to match the score (i.e., the gradient of the log-prior) instead of designing the regularizer itself. We also show tight connections between SMD, kernel density estimation, and constrained minimum mean-squared error denoising. Finally, we provide new interpretations of the RED algorithms proposed by Romano et al., and we propose novel RED algorithms with faster convergence.

##### Abstract (translated by Google)
正如Romano，Elad和Milanfar最近提出的，Denoising正则化（RED）是一种强大的新图像恢复框架，旨在从插入式图像去噪函数中构建显式正则化目标。有证据表明，RED算法确实是最先进的。然而，更仔细的检查表明，显式正则化可能无法解释这些算法的工作。在本文中，我们澄清了Romano等人的表述。只有当降噪器具有对称的雅可比矩阵时，我们才能证明这种对称性不会出现在实际的分解器中，例如非局部均值BM3D，TNRD和DnCNN。进一步，我们证明非对称降噪函数不能用任何显式正则化函数来模拟。鉴于这些结果，仍然存在如何为实际的分子拒斥者证明性能良好的RED算法的问题。作为回应，我们提出了一个名为“通过降噪进行分数匹配”（SMD）的新框架，其旨在匹配分数（即，对数先验的梯度）而不是设计正规化器本身。我们还展示了SMD，核密度估计和约束最小均方误差去噪之间的紧密联系。最后，我们提供了对Romano等人提出的RED算法的新解释，并且我们提出了具有更快收敛性的新颖RED算法。

##### URL
[http://arxiv.org/abs/1806.02296](http://arxiv.org/abs/1806.02296)

##### PDF
[http://arxiv.org/pdf/1806.02296](http://arxiv.org/pdf/1806.02296)

