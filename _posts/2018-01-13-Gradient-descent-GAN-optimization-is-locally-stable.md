---
layout: post
title: "Gradient descent GAN optimization is locally stable"
date: 2018-01-13 18:39:22
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


##### URL
[https://arxiv.org/abs/1706.04156](https://arxiv.org/abs/1706.04156)

##### PDF
[https://arxiv.org/pdf/1706.04156](https://arxiv.org/pdf/1706.04156)

