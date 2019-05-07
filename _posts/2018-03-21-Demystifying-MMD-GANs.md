---
layout: post
title: "Demystifying MMD GANs"
date: 2018-03-21 17:25:27
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization
author: Mikołaj Bińkowski, Dougal J. Sutherland, Michael Arbel, Arthur Gretton
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the training and performance of generative adversarial networks using the Maximum Mean Discrepancy (MMD) as critic, termed MMD GANs. As our main theoretical contribution, we clarify the situation with bias in GAN loss functions raised by recent work: we show that gradient estimators used in the optimization process for both MMD GANs and Wasserstein GANs are unbiased, but learning a discriminator based on samples leads to biased gradients for the generator parameters. We also discuss the issue of kernel choice for the MMD critic, and characterize the kernel corresponding to the energy distance used for the Cramer GAN critic. Being an integral probability metric, the MMD benefits from training strategies recently developed for Wasserstein GANs. In experiments, the MMD GAN is able to employ a smaller critic network than the Wasserstein GAN, resulting in a simpler and faster-training algorithm with matching performance. We also propose an improved measure of GAN convergence, the Kernel Inception Distance, and show how to use it to dynamically adapt learning rates during GAN training.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.01401](https://arxiv.org/abs/1801.01401)

##### PDF
[https://arxiv.org/pdf/1801.01401](https://arxiv.org/pdf/1801.01401)

