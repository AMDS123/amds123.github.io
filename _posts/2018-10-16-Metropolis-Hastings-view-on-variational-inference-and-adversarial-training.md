---
layout: post
title: "Metropolis-Hastings view on variational inference and adversarial training"
date: 2018-10-16 17:26:24
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Optimization Inference
author: Kirill Neklyudov, Pavel Shvechikov, Dmitry Vetrov
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose to view the acceptance rate of the Metropolis-Hastings algorithm as a universal objective for learning to sample from target distribution -- given either as a set of samples or in the form of unnormalized density. This point of view unifies the goals of such approaches as Markov Chain Monte Carlo (MCMC), Generative Adversarial Networks (GANs), variational inference. To reveal the connection we derive the lower bound on the acceptance rate and treat it as the objective for learning explicit and implicit samplers. The form of the lower bound allows for doubly stochastic gradient optimization in case the target distribution factorizes (i.e. over data points). We empirically validate our approach on Bayesian inference for neural networks and generative models for images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07151](http://arxiv.org/abs/1810.07151)

##### PDF
[http://arxiv.org/pdf/1810.07151](http://arxiv.org/pdf/1810.07151)

