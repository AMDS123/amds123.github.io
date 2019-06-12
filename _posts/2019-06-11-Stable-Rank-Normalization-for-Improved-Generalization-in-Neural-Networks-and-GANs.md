---
layout: post
title: "Stable Rank Normalization for Improved Generalization in Neural Networks and GANs"
date: 2019-06-11 15:37:49
categories: arXiv_CV
tags: arXiv_CV GAN Classification
author: Amartya Sanyal, Philip H.S. Torr, Puneet K. Dokania
mathjax: true
---

* content
{:toc}

##### Abstract
Exciting new work on the generalization bounds for neural networks (NN) given by Neyshabur et al. , Bartlett et al. depend on two parameter-depenedent quantities: the Lipschitz constant upper-bound and the stable rank (a softer version of the rank operator). This leads to an interesting question of whether controlling these quantities might improve the generalization behaviour of NNs. To this end, we propose stable rank normalization (SRN), a novel, optimal, and computationally efficient weight-normalization scheme which minimizes the stable rank of a linear operator. Surprisingly we find that SRN, inspite of being non-convex problem, can be shown to have a unique optimal solution. Moreover, we show that SRN allows control of the data-dependent empirical Lipschitz constant, which in contrast to the Lipschitz upper-bound, reflects the true behaviour of a model on a given dataset. We provide thorough analyses to show that SRN, when applied to the linear layers of a NN for classification, provides striking improvements-11.3% on the generalization gap compared to the standard NN along with significant reduction in memorization. When applied to the discriminator of GANs (called SRN-GAN) it improves Inception, FID, and Neural divergence scores on the CIFAR 10/100 and CelebA datasets, while learning mappings with low empirical Lipschitz constants.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.04659](https://arxiv.org/abs/1906.04659)

##### PDF
[https://arxiv.org/pdf/1906.04659](https://arxiv.org/pdf/1906.04659)

