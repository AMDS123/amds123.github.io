---
layout: post
title: "Structural Similarity Index SSIMplified: Is there really a simpler concept at the heart of image quality measurement?"
date: 2015-05-25 01:53:07
categories: arXiv_CV
tags: arXiv_CV QA Relation
author: Kieran Gerard Larkin
mathjax: true
---

* content
{:toc}

##### Abstract
The Structural Similarity Index (SSIM) is generally considered to be a milestone in the recent history of Image Quality Assessment (IQA). Alas, SSIM's accepted development from the product of three heuristic factors continues to obscure it's real underlying simplicity. Starting instead from a symmetric-antisymmetric reformulation we first show SSIM to be a contrast or visibility function in the classic sense. Furthermore, the previously enigmatic structural covariance is revealed to be the difference of variances. The second step, eliminating the intrinsic quadratic nature of SSIM, allows a near linear correlation with human observer scores, and without invoking the usual, but arbitrary, sigmoid model fitting. We conclude that SSIM can be re-interpreted in terms of perceptual masking: it is essentially equivalent to a normalised error or noise visibility function (NVF), and, furthermore, the NVF alone explains it success in modelling perceptual image quality. We use the term Dissimilarity Quotient (DQ) for the specifically anti/symmetric SSIM derived NVF. It seems that IQA researchers may now have two choices: 1) Continue to use the complex SSIM formula, but noting that SSIM only works coincidentally since the covariance term is actually the mean square error (MSE) in disguise. 2) Use the simplest of all perceptually-masked image quality metrics, namely NVF or DQ. On this choice Occam is clear: in the absence of differences in predictive ability, the fewer assumptions that are made, the better.

##### Abstract (translated by Google)
结构相似性指数（SSIM）通常被认为是近年来图像质量评估（IQA）历史上的一个里程碑。可惜的是，SSIM从三个启发式因素的产物中被接受的发展继续掩盖了它真正的潜在的简单性。从对称反对称重新开始，我们首先将SSIM展示为经典意义上的对比度或可见度函数。此外，先前的神秘结构协方差揭示了差异的差异。第二步，消除SSIM的固有二次性，允许与人类观察者得分近似线性相关，而不需要通常的但任意的S形模型拟合。我们得出这样的结论：SSIM可以用感知掩蔽来重新解释：它本质上等同于归一化误差或噪声可见度函数（NVF），而且，NVF本身就解释了它在建模感知图像质量方面的成功。我们使用术语“差异商（DQ）”来表示特定的反/对称SSIM派生的NVF。似乎IQA的研究人员现在可能有两种选择：1）继续使用复杂的SSIM公式，但注意SSIM只能巧合地工作，因为协方差项实际上是伪装的均方误差（MSE）。 2）使用最简单的所有感知掩盖的图像质量度量，即NVF或DQ。在这个选择奥卡姆是明确的：在预测能力差异的情况下，做出的假设越少越好。

##### URL
[https://arxiv.org/abs/1503.06680](https://arxiv.org/abs/1503.06680)

##### PDF
[https://arxiv.org/pdf/1503.06680](https://arxiv.org/pdf/1503.06680)

