---
layout: post
title: "Inception Score, Label Smoothing, Gradient Vanishing and -log) Alternative"
date: 2017-08-05 08:15:07
categories: arXiv_CV
tags: arXiv_CV GAN
author: Zhiming Zhou, Weinan Zhang, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study several GAN related topics mathematically, including Inception score, label smoothing, gradient vanishing and the -log(D(x)) alternative. We show that Inception score is actually equivalent to Mode score, both consisting of two entropy terms, which has the drawback of ignoring the prior distribution of the labels. We thus propose AM score as an alternative that leverages cross-entropy and takes the reference distribution into account. Empirical results indicate that AM score outperforms Inception score. We study label smoothing, gradient vanishing and -log(D(x)) alternative from the perspective of class-aware gradient, with which we show the exact problems when applying label smoothing to fake samples along with the log(1-D(x)) generator loss, which is previously unclear, and more importantly show that the problem does not exist when using the -log(D(x)) generator loss.

##### Abstract (translated by Google)
在本文中，我们从数学角度研究了几个与GAN相关的主题，包括初始分数，标签平滑，梯度消失和-log（D（x））的选择。我们显示Inception分数实际上相当于Mode分数，两者都由两个熵项组成，其缺点是忽略了标签的先前分布。因此，我们提出AM分数作为利用交叉熵并考虑参考分布的替代方案。实证结果表明AM评分优于Inception评分。我们从类感知梯度的角度研究了标签平滑，渐变消失和-log（D（x））替代方法，并用log（1-D（x ））发生器损失，这是以前不清楚，更重要的是表明使用-log（D（x））发生器损失时，问题不存在。

##### URL
[https://arxiv.org/abs/1708.01729](https://arxiv.org/abs/1708.01729)

##### PDF
[https://arxiv.org/pdf/1708.01729](https://arxiv.org/pdf/1708.01729)

