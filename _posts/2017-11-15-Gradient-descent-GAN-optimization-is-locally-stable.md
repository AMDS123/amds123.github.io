---
layout: post
title: "Gradient descent GAN optimization is locally stable"
date: 2017-11-15 03:29:12
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Optimization Gradient_Descent
author: Vaishnavh Nagarajan, J. Zico Kolter
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the growing prominence of generative adversarial networks (GANs), optimization in GANs is still a poorly understood topic. In this paper, we analyze the "gradient descent" form of GAN optimization i.e., the natural setting where we simultaneously take small gradient steps in both generator and discriminator parameters. We show that even though GAN optimization does not correspond to a convex-concave game (even for simple parameterizations), under proper conditions, equilibrium points of this optimization procedure are still \emph{locally asymptotically stable} for the traditional GAN formulation. On the other hand, we show that the recently proposed Wasserstein GAN can have non-convergent limit cycles near equilibrium. Motivated by this stability analysis, we propose an additional regularization term for gradient descent GAN updates, which \emph{is} able to guarantee local stability for both the WGAN and the traditional GAN, and also shows practical promise in speeding up convergence and addressing mode collapse.

##### Abstract (translated by Google)
尽管生成对抗网络（GAN）日益突出，GAN中的优化仍然是一个了解不多的话题。在本文中，我们分析了GAN优化的“梯度下降”形式，即在发生器和鉴别器参数中同时采用小梯度步进的自然设置。我们证明即使GAN最优化不符合凹凸博弈（即使是简单的参数化），在适当的条件下，对于传统的GAN公式，这个优化过程的平衡点仍然是\局部渐近稳定的。另一方面，我们证明最近提出的Wasserstein GAN可以有非收敛极限循环接近平衡。在稳定性分析的推动下，我们提出了一个梯度下降GAN更新的附加正则化项，它可以保证WGAN和传统GAN的局部稳定性，并且在加速收敛和寻址模式坍方。

##### URL
[https://arxiv.org/abs/1706.04156](https://arxiv.org/abs/1706.04156)

##### PDF
[https://arxiv.org/pdf/1706.04156](https://arxiv.org/pdf/1706.04156)

