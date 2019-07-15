---
layout: post
title: "Virtual Adversarial Lipschitz Regularization"
date: 2019-07-12 11:41:18
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN
author: D&#xe1;vid Terj&#xe9;k
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are one of the most popular approaches when it comes to training generative models, among which variants of Wasserstein GANs are considered superior to the standard GAN formulation in terms of learning stability and sample quality. However, Wasserstein GANs require the critic to be K-Lipschitz, which is often enforced implicitly by penalizing the norm of its gradient, or by globally restricting its Lipschitz constant via weight normalization techniques. Training with a regularization term penalizing the violation of the Lipschitz constraint explicitly, instead of through the norm of the gradient, was found to be practically infeasible in most situations. With a novel generalization of Virtual Adversarial Training, called Virtual Adversarial Lipschitz Regularization, we show that using an explicit Lipschitz penalty is indeed viable and leads to state-of-the-art performance in terms of Inception Score and Fr\'echet Inception Distance when applied to Wasserstein GANs trained on CIFAR-10.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05681](http://arxiv.org/abs/1907.05681)

##### PDF
[http://arxiv.org/pdf/1907.05681](http://arxiv.org/pdf/1907.05681)

