---
layout: post
title: "Do GAN Loss Functions Really Matter?"
date: 2018-11-23 17:18:00
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN
author: Yipeng Qin, Niloy Mitra, Peter Wonka
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the recent controversy between Lipschitz regularization and the choice of loss function for the training of Generative Adversarial Networks (GANs). One side argues that the success of the GAN training should be attributed to the choice of loss function [16, 2, 5], while the other suggests that the Lipschitz regularization is the key to good results [17, 3, 18, 19]. We provide a theoretical and experimental analysis of how Lipschitz regularization interacts with the loss function to derive the following insights: (i) We show that popular GANs (NS-GAN [4], LS-GAN [16], WGAN [2]) perform equally well when the discriminator is regularized with a small Lipschitz constant, but the performance in terms of quality and diversity gets worse for larger Lipschitz constants, except for WGAN. (ii) We show that all loss functions degenerate to linear ones for small Lipschitz constants to explain why the performance of these GANs is similar. For higher Lipschitz constants, we observe that only WGAN performs well while NS-GAN and LS-GAN break down. For lower Lipschitz constants, NS-GAN and LS-GAN perform similarly to WGAN only because they degenerate to the WGAN loss. In order to further illustrate this issue, we demonstrate that even "ridiculous" loss functions such as sin and exp have similar performance to NS-GAN, LS-GAN, and WGAN, when small Lipschitz constants are used.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09567](http://arxiv.org/abs/1811.09567)

##### PDF
[http://arxiv.org/pdf/1811.09567](http://arxiv.org/pdf/1811.09567)

