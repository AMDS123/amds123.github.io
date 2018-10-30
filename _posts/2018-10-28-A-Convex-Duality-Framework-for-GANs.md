---
layout: post
title: "A Convex Duality Framework for GANs"
date: 2018-10-28 01:15:20
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN
author: Farzan Farnia, David Tse
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial network (GAN) is a minimax game between a generator mimicking the true model and a discriminator distinguishing the samples produced by the generator from the real training samples. Given an unconstrained discriminator able to approximate any function, this game reduces to finding the generative model minimizing a divergence measure, e.g. the Jensen-Shannon (JS) divergence, to the data distribution. However, in practice the discriminator is constrained to be in a smaller class $\mathcal{F}$ such as neural nets. Then, a natural question is how the divergence minimization interpretation changes as we constrain $\mathcal{F}$. In this work, we address this question by developing a convex duality framework for analyzing GANs. For a convex set $\mathcal{F}$, this duality framework interprets the original GAN formulation as finding the generative model with minimum JS-divergence to the distributions penalized to match the moments of the data distribution, with the moments specified by the discriminators in $\mathcal{F}$. We show that this interpretation more generally holds for f-GAN and Wasserstein GAN. As a byproduct, we apply the duality framework to a hybrid of f-divergence and Wasserstein distance. Unlike the f-divergence, we prove that the proposed hybrid divergence changes continuously with the generative model, which suggests regularizing the discriminator's Lipschitz constant in f-GAN and vanilla GAN. We numerically evaluate the power of the suggested regularization schemes for improving GAN's training performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.11740](https://arxiv.org/abs/1810.11740)

##### PDF
[https://arxiv.org/pdf/1810.11740](https://arxiv.org/pdf/1810.11740)

