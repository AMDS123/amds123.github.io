---
layout: post
title: "Gang of GANs: Generative Adversarial Networks with Maximum Margin Ranking"
date: 2017-04-17 04:42:56
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Felix Juefei-Xu, Vishnu Naresh Boddeti, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional generative adversarial networks (GAN) and many of its variants are trained by minimizing the KL or JS-divergence loss that measures how close the generated data distribution is from the true data distribution. A recent advance called the WGAN based on Wasserstein distance can improve on the KL and JS-divergence based GANs, and alleviate the gradient vanishing, instability, and mode collapse issues that are common in the GAN training. In this work, we aim at improving on the WGAN by first generalizing its discriminator loss to a margin-based one, which leads to a better discriminator, and in turn a better generator, and then carrying out a progressive training paradigm involving multiple GANs to contribute to the maximum margin ranking loss so that the GAN at later stages will improve upon early stages. We call this method Gang of GANs (GoGAN). We have shown theoretically that the proposed GoGAN can reduce the gap between the true data distribution and the generated data distribution by at least half in an optimally trained WGAN. We have also proposed a new way of measuring GAN quality which is based on image completion tasks. We have evaluated our method on four visual datasets: CelebA, LSUN Bedroom, CIFAR-10, and 50K-SSFF, and have seen both visual and quantitative improvement over baseline WGAN.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.04865](https://arxiv.org/abs/1704.04865)

##### PDF
[https://arxiv.org/pdf/1704.04865](https://arxiv.org/pdf/1704.04865)

