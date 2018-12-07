---
layout: post
title: "Self-Net: Lifelong Learning via Continual Self-Modeling"
date: 2018-12-05 21:37:07
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Blake Camp, Jaya Krishna Mandivarapu, Rolando Estrada
mathjax: true
---

* content
{:toc}

##### Abstract
Continual learning (CL) is one of the most challenging problems in artificial intelligence. While several recent approaches achieve some degree of CL in deep neural networks, they are generally marred by unscalable storage requirements, inefficient training regimes, or model saturation. In this paper, we present a scalable approach to continual learning that offers a practical solution to these problems. Motivated by the biological mechanisms responsible for consolidating knowledge and encoding experiences for long term storage, we present Self-Net, a novel framework which auto-encodes its own networks in a continual fashion. We show that a modified contractive autoencoder can efficiently integrate entire networks into a compact latent space, and we demonstrate that the latent representations can be used to generate high-fidelity recollections of their original counterparts. The result is a single, compact model capable of generating the an entire set of task-specific networks, each individually trained on a different task during the lifetime of the system. Our technique outperforms other state-of-the-art approaches on numerous datasets, including continual versions of MNIST, CIFAR10, CIFAR100, and Atari. To the best of our knowledge, we are the first to demonstrate the efficacy of using autoencoders to sequentially encode entire sets of networks in order to facilitate continual learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10354](http://arxiv.org/abs/1805.10354)

##### PDF
[http://arxiv.org/pdf/1805.10354](http://arxiv.org/pdf/1805.10354)

