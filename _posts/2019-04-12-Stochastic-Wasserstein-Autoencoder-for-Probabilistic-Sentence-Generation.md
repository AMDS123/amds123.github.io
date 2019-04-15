---
layout: post
title: "Stochastic Wasserstein Autoencoder for Probabilistic Sentence Generation"
date: 2019-04-12 17:43:25
categories: arXiv_CL
tags: arXiv_CL
author: Hareesh Bahuleyan, Lili Mou, Hao Zhou, Olga Vechtomova
mathjax: true
---

* content
{:toc}

##### Abstract
The variational autoencoder (VAE) imposes a probabilistic distribution (typically Gaussian) on the latent space and penalizes the Kullback--Leibler (KL) divergence between the posterior and prior. In NLP, VAEs are extremely difficult to train due to the problem of KL collapsing to zero. One has to implement various heuristics such as KL weight annealing and word dropout in a carefully engineered manner to successfully train a VAE for text. In this paper, we propose to use the Wasserstein autoencoder (WAE) for probabilistic sentence generation, where the encoder could be either stochastic or deterministic. We show theoretically and empirically that, in the original WAE, the stochastically encoded Gaussian distribution tends to become a Dirac-delta function, and we propose a variant of WAE that encourages the stochasticity of the encoder. Experimental results show that the latent space learned by WAE exhibits properties of continuity and smoothness as in VAEs, while simultaneously achieving much higher BLEU scores for sentence reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.08462](http://arxiv.org/abs/1806.08462)

##### PDF
[http://arxiv.org/pdf/1806.08462](http://arxiv.org/pdf/1806.08462)

