---
layout: post
title: "Self-Net: Lifelong Learning via Continual Self-Modeling"
date: 2019-07-12 01:05:46
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Blake Camp, Jaya Krishna Mandivarapu, Rolando Estrada
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a set of tasks over time, also known as continual learning (CL), is one of the most challenging problems in artificial intelligence. While recent approaches achieve some degree of CL in deep neural networks, they either (1) grow the network parameters linearly with the number of tasks, (2) require storing training data from previous tasks, or (3) restrict the network's ability to learn new tasks. To address these issues, we propose a novel framework, Self-Net, that uses an autoencoder to learn a set of low-dimensional representations of the weights learned for different tasks. We demonstrate that these low-dimensional vectors can then be used to generate high-fidelity recollections of the original weights. Self-Net can incorporate new tasks over time with little retraining and with minimal loss in performance for older tasks. Our system does not require storing prior training data and its parameters grow only logarithmically with the number of tasks. We show that our technique outperforms current state-of-the-art approaches on numerous datasets---including continual versions of MNIST, CIFAR10, CIFAR100, and Atari---and we demonstrate that our method can achieve over 10X storage compression in a continual fashion. To the best of our knowledge, we are the first to use autoencoders to sequentially encode sets of network weights to enable continual learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.10354](http://arxiv.org/abs/1805.10354)

##### PDF
[http://arxiv.org/pdf/1805.10354](http://arxiv.org/pdf/1805.10354)

