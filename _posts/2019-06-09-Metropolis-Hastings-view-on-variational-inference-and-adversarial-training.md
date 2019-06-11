---
layout: post
title: "Metropolis-Hastings view on variational inference and adversarial training"
date: 2019-06-09 14:23:34
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Inference
author: Kirill Neklyudov, Evgenii Egorov, Pavel Shvechikov, Dmitry Vetrov
mathjax: true
---

* content
{:toc}

##### Abstract
A significant part of MCMC methods can be considered as the Metropolis-Hastings (MH) algorithm with different proposal distributions. From this point of view, the problem of constructing a sampler can be reduced to the question - how to choose a proposal for the MH algorithm? To address this question, we propose to learn an independent sampler that maximizes the acceptance rate of the MH algorithm, which, as we demonstrate, is highly related to the conventional variational inference. For Bayesian inference, the proposed method compares favorably against alternatives to sample from the posterior distribution. Under the same approach, we step beyond the scope of classical MCMC methods and deduce the Generative Adversarial Networks (GANs) framework from scratch, treating the generator as the proposal and the discriminator as the acceptance test. On real-world datasets, we improve Frechet Inception Distance and Inception Score, using different GANs as a proposal distribution for the MH algorithm. In particular, we demonstrate improvements of recently proposed BigGAN model on ImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07151](http://arxiv.org/abs/1810.07151)

##### PDF
[http://arxiv.org/pdf/1810.07151](http://arxiv.org/pdf/1810.07151)

