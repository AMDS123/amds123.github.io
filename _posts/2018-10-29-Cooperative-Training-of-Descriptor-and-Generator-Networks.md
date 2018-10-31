---
layout: post
title: "Cooperative Training of Descriptor and Generator Networks"
date: 2018-10-29 16:42:24
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jianwen Xie, Yang Lu, Ruiqi Gao, Song-Chun Zhu, Ying Nian Wu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the cooperative training of two generative models for image modeling and synthesis. Both models are parametrized by convolutional neural networks (ConvNets). The first model is a deep energy-based model, whose energy function is defined by a bottom-up ConvNet, which maps the observed image to the energy. We call it the descriptor network. The second model is a generator network, which is a non-linear version of factor analysis. It is defined by a top-down ConvNet, which maps the latent factors to the observed image. The maximum likelihood learning algorithms of both models involve MCMC sampling such as Langevin dynamics. We observe that the two learning algorithms can be seamlessly interwoven into a cooperative learning algorithm that can train both models simultaneously. Specifically, within each iteration of the cooperative learning algorithm, the generator model generates initial synthesized examples to initialize a finite-step MCMC that samples and trains the energy-based descriptor model. After that, the generator model learns from how the MCMC changes its synthesized examples. That is, the descriptor model teaches the generator model by MCMC, so that the generator model accumulates the MCMC transitions and reproduces them by direct ancestral sampling. We call this scheme MCMC teaching. We show that the cooperative algorithm can learn highly realistic generative models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1609.09408](http://arxiv.org/abs/1609.09408)

##### PDF
[http://arxiv.org/pdf/1609.09408](http://arxiv.org/pdf/1609.09408)

