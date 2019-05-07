---
layout: post
title: "Improved Training of Wasserstein GANs"
date: 2017-12-25 23:03:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Language_Model
author: Ishaan Gulrajani, Faruk Ahmed, Martin Arjovsky, Vincent Dumoulin, Aaron Courville
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) are powerful generative models, but suffer from training instability. The recently proposed Wasserstein GAN (WGAN) makes progress toward stable training of GANs, but sometimes can still generate only low-quality samples or fail to converge. We find that these problems are often due to the use of weight clipping in WGAN to enforce a Lipschitz constraint on the critic, which can lead to undesired behavior. We propose an alternative to clipping weights: penalize the norm of gradient of the critic with respect to its input. Our proposed method performs better than standard WGAN and enables stable training of a wide variety of GAN architectures with almost no hyperparameter tuning, including 101-layer ResNets and language models over discrete data. We also achieve high quality generations on CIFAR-10 and LSUN bedrooms.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.00028](https://arxiv.org/abs/1704.00028)

##### PDF
[https://arxiv.org/pdf/1704.00028](https://arxiv.org/pdf/1704.00028)

