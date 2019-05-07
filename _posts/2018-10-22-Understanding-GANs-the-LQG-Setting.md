---
layout: post
title: "Understanding GANs: the LQG Setting"
date: 2018-10-22 13:42:23
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Soheil Feizi, Farzan Farnia, Tony Ginart, David Tse
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) have become a popular method to learn a probability model from data. In this paper, we aim to provide an understanding of some of the basic issues surrounding GANs including their formulation, generalization and stability on a simple benchmark where the data has a high-dimensional Gaussian distribution. Even in this simple benchmark, the GAN problem has not been well-understood as we observe that existing state-of-the-art GAN architectures may fail to learn a proper generative distribution owing to (1) stability issues (i.e., convergence to bad local solutions or not converging at all), (2) approximation issues (i.e., having improper global GAN optimizers caused by inappropriate GAN's loss functions), and (3) generalizability issues (i.e., requiring large number of samples for training). In this setup, we propose a GAN architecture which recovers the maximum-likelihood solution and demonstrates fast generalization. Moreover, we analyze global stability of different computational approaches for the proposed GAN optimization and highlight their pros and cons. Finally, we outline an extension of our model-based approach to design GANs in more complex setups than the considered Gaussian benchmark.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1710.10793](https://arxiv.org/abs/1710.10793)

##### PDF
[https://arxiv.org/pdf/1710.10793](https://arxiv.org/pdf/1710.10793)

