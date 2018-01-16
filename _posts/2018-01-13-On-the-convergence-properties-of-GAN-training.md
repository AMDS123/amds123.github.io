---
layout: post
title: "On the convergence properties of GAN training"
date: 2018-01-13 09:42:26
categories: arXiv_AI
tags: arXiv_AI Regularization GAN
author: Lars Mescheder
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has shown local convergence of GAN training for absolutely continuous data and generator distributions. In this note we show that the requirement of absolute continuity is necessary: we describe a simple yet prototypical counterexample showing that in the more realistic case of distributions that are not absolutely continuous, unregularized GAN training is generally not convergent. Furthermore, we discuss recent regularization strategies that were proposed to stabilize GAN training. Our analysis shows that while GAN training with instance noise or gradient penalties converges, Wasserstein-GANs and Wasserstein-GANs-GP with a finite number of discriminator updates per generator update do in general not converge to the equilibrium point. We explain these results and show that both instance noise and gradient penalties constitute solutions to the problem of purely imaginary eigenvalues of the Jacobian of the gradient vector field. Based on our analysis, we also propose a simplified gradient penalty with the same effects on local convergence as more complicated penalties.

##### Abstract (translated by Google)
最近的研究表明，GAN训练对绝对连续的数据和发生器分布的局部收敛。在这个笔记中，我们表明绝对连续性的要求是必要的：我们描述一个简单而原型的反例，表明在不是绝对连续的更现实的分布情况下，非规范化的GAN训练通常不会收敛。此外，我们讨论了最近提出的稳定GAN训练的正则化策略。我们的分析表明，尽管实例噪声或梯度损失的GAN训练收敛，但每个发生器更新有限个鉴别器更新的Wasserstein-GANs和Wasserstein-GANs-GP一般不会收敛到平衡点。我们解释这些结果，并显示实例噪声和梯度罚款构成解决方案的纯粹的虚构梯度矢量场雅可比特征值的问题。基于我们的分析，我们还提出了一个简化的梯度惩罚，对局部收敛的影响与更复杂的惩罚相同。

##### URL
[https://arxiv.org/abs/1801.04406](https://arxiv.org/abs/1801.04406)

##### PDF
[https://arxiv.org/pdf/1801.04406](https://arxiv.org/pdf/1801.04406)

