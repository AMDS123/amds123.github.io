---
layout: post
title: "GumBolt: Extending Gumbel trick to Boltzmann priors"
date: 2019-03-01 17:30:53
categories: arXiv_AI
tags: arXiv_AI
author: Amir H. Khoshaman, Mohammad H. Amin
mathjax: true
---

* content
{:toc}

##### Abstract
Boltzmann machines (BMs) are appealing candidates for powerful priors in variational autoencoders (VAEs), as they are capable of capturing nontrivial and multi-modal distributions over discrete variables. However, non-differentiability of the discrete units prohibits using the reparameterization trick, essential for low-noise back propagation. The Gumbel trick resolves this problem in a consistent way by relaxing the variables and distributions, but it is incompatible with BM priors. Here, we propose the GumBolt, a model that extends the Gumbel trick to BM priors in VAEs. GumBolt is significantly simpler than the recently proposed methods with BM prior and outperforms them by a considerable margin. It achieves state-of-the-art performance on permutation invariant MNIST and OMNIGLOT datasets in the scope of models with only discrete latent variables. Moreover, the performance can be further improved by allowing multi-sampled (importance-weighted) estimation of log-likelihood in training, which was not possible with previous models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07349](http://arxiv.org/abs/1805.07349)

##### PDF
[http://arxiv.org/pdf/1805.07349](http://arxiv.org/pdf/1805.07349)

