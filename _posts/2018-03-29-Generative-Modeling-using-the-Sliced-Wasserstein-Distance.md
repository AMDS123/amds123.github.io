---
layout: post
title: "Generative Modeling using the Sliced Wasserstein Distance"
date: 2018-03-29 17:58:44
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Ishan Deshpande, Ziyu Zhang, Alexander Schwing
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Nets (GANs) are very successful at modeling distributions from given samples, even in the high-dimensional case. However, their formulation is also known to be hard to optimize and often not stable. While this is particularly true for early GAN formulations, there has been significant empirically motivated and theoretically founded progress to improve stability, for instance, by using the Wasserstein distance rather than the Jenson-Shannon divergence. Here, we consider an alternative formulation for generative modeling based on random projections which, in its simplest form, results in a single objective rather than a saddle-point formulation. By augmenting this approach with a discriminator we improve its accuracy. We found our approach to be significantly more stable compared to even the improved Wasserstein GAN. Further, unlike the traditional GAN loss, the loss formulated in our method is a good measure of the actual distance between the distributions and, for the first time for GAN training, we are able to show estimates for the same.

##### Abstract (translated by Google)
生成对抗网络（GAN）在给定样本的分布建模方面非常成功，即使在高维情况下也是如此。然而，他们的公式也被称为难以优化，并且往往不稳定。虽然早期GAN公式的这种情况尤其如此，但是在改善稳定性方面取得了显着的经验主动和理论上的进展，例如，通过使用Wasserstein距离而不是简森 - 香农分歧。在这里，我们考虑一种基于随机投影的生成建模的替代公式，其最简单的形式是单一目标而不是鞍点公式。通过使用鉴别器来增强这种方法，我们可以提高其准确性。与甚至改进的Wasserstein GAN相比，我们发现我们的方法显着更稳定。此外，与传统的GAN损失不同，我们的方法中制定的损失衡量的是分布之间的实际距离，并且对于GAN培训首次能够显示相同的估计值。

##### URL
[http://arxiv.org/abs/1803.11188](http://arxiv.org/abs/1803.11188)

##### PDF
[http://arxiv.org/pdf/1803.11188](http://arxiv.org/pdf/1803.11188)

