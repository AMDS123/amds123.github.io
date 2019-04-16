---
layout: post
title: "Dist-GAN: An Improved GAN using Distance Constraints"
date: 2018-12-15 08:32:35
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Ngoc-Trung Tran, Tuan-Anh Bui, Ngai-Man Cheung
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce effective training algorithms for Generative Adversarial Networks (GAN) to alleviate mode collapse and gradient vanishing. In our system, we constrain the generator by an Autoencoder (AE). We propose a formulation to consider the reconstructed samples from AE as "real" samples for the discriminator. This couples the convergence of the AE with that of the discriminator, effectively slowing down the convergence of discriminator and reducing gradient vanishing. Importantly, we propose two novel distance constraints to improve the generator. First, we propose a latent-data distance constraint to enforce compatibility between the latent sample distances and the corresponding data sample distances. We use this constraint to explicitly prevent the generator from mode collapse. Second, we propose a discriminator-score distance constraint to align the distribution of the generated samples with that of the real samples through the discriminator score. We use this constraint to guide the generator to synthesize samples that resemble the real ones. Our proposed GAN using these distance constraints, namely Dist-GAN, can achieve better results than state-of-the-art methods across benchmark datasets: synthetic, MNIST, MNIST-1K, CelebA, CIFAR-10 and STL-10 datasets. Our code is published here (this https URL) for research.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.08887](https://arxiv.org/abs/1803.08887)

##### PDF
[https://arxiv.org/pdf/1803.08887](https://arxiv.org/pdf/1803.08887)

