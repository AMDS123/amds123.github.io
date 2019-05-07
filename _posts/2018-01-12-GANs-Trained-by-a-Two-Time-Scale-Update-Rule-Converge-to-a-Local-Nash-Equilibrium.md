---
layout: post
title: "GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium"
date: 2018-01-12 14:05:44
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Optimization Gradient_Descent
author: Martin Heusel, Hubert Ramsauer, Thomas Unterthiner, Bernhard Nessler, Sepp Hochreiter
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) excel at creating realistic images with complex models for which maximum likelihood is infeasible. However, the convergence of GAN training has still not been proved. We propose a two time-scale update rule (TTUR) for training GANs with stochastic gradient descent on arbitrary GAN loss functions. TTUR has an individual learning rate for both the discriminator and the generator. Using the theory of stochastic approximation, we prove that the TTUR converges under mild assumptions to a stationary local Nash equilibrium. The convergence carries over to the popular Adam optimization, for which we prove that it follows the dynamics of a heavy ball with friction and thus prefers flat minima in the objective landscape. For the evaluation of the performance of GANs at image generation, we introduce the "Fréchet Inception Distance" (FID) which captures the similarity of generated images to real ones better than the Inception Score. In experiments, TTUR improves learning for DCGANs and Improved Wasserstein GANs (WGAN-GP) outperforming conventional GAN training on CelebA, CIFAR-10, SVHN, LSUN Bedrooms, and the One Billion Word Benchmark.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.08500](https://arxiv.org/abs/1706.08500)

##### PDF
[https://arxiv.org/pdf/1706.08500](https://arxiv.org/pdf/1706.08500)

