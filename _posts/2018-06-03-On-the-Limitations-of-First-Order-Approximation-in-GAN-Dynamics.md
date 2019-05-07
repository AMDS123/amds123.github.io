---
layout: post
title: "On the Limitations of First-Order Approximation in GAN Dynamics"
date: 2018-06-03 23:00:03
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Jerry Li, Aleksander Madry, John Peebles, Ludwig Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
While Generative Adversarial Networks (GANs) have demonstrated promising performance on multiple vision tasks, their learning dynamics are not yet well understood, both in theory and in practice. To address this issue, we study GAN dynamics in a simple yet rich parametric model that exhibits several of the common problematic convergence behaviors such as vanishing gradients, mode collapse, and diverging or oscillatory behavior. In spite of the non-convex nature of our model, we are able to perform a rigorous theoretical analysis of its convergence behavior. Our analysis reveals an interesting dichotomy: a GAN with an optimal discriminator provably converges, while first order approximations of the discriminator steps lead to unstable GAN dynamics and mode collapse. Our result suggests that using first order discriminator steps (the de-facto standard in most existing GAN setups) might be one of the factors that makes GAN training challenging in practice.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.09884](https://arxiv.org/abs/1706.09884)

##### PDF
[https://arxiv.org/pdf/1706.09884](https://arxiv.org/pdf/1706.09884)

