---
layout: post
title: "MMD GAN: Towards Deeper Understanding of Moment Matching Network"
date: 2017-11-27 14:04:35
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Gradient_Descent
author: Chun-Liang Li, Wei-Cheng Chang, Yu Cheng, Yiming Yang, Barnabás Póczos
mathjax: true
---

* content
{:toc}

##### Abstract
Generative moment matching network (GMMN) is a deep generative model that differs from Generative Adversarial Network (GAN) by replacing the discriminator in GAN with a two-sample test based on kernel maximum mean discrepancy (MMD). Although some theoretical guarantees of MMD have been studied, the empirical performance of GMMN is still not as competitive as that of GAN on challenging and large benchmark datasets. The computational efficiency of GMMN is also less desirable in comparison with GAN, partially due to its requirement for a rather large batch size during the training. In this paper, we propose to improve both the model expressiveness of GMMN and its computational efficiency by introducing adversarial kernel learning techniques, as the replacement of a fixed Gaussian kernel in the original GMMN. The new approach combines the key ideas in both GMMN and GAN, hence we name it MMD GAN. The new distance measure in MMD GAN is a meaningful loss that enjoys the advantage of weak topology and can be optimized via gradient descent with relatively small batch sizes. In our evaluation on multiple benchmark datasets, including MNIST, CIFAR- 10, CelebA and LSUN, the performance of MMD-GAN significantly outperforms GMMN, and is competitive with other representative GAN works.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.08584](https://arxiv.org/abs/1705.08584)

##### PDF
[https://arxiv.org/pdf/1705.08584](https://arxiv.org/pdf/1705.08584)

