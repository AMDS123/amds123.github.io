---
layout: post
title: "Agent Embeddings: A Latent Representation for Pole-Balancing Networks"
date: 2018-11-12 00:31:59
categories: arXiv_AI
tags: arXiv_AI Face Embedding
author: Oscar Chang, Robert Kwiatkowski, Siyuan Chen, Hod Lipson
mathjax: true
---

* content
{:toc}

##### Abstract
We show that it is possible to reduce a high-dimensional object like a neural network agent into a low-dimensional vector representation with semantic meaning that we call agent embeddings, akin to word or face embeddings. This can be done by collecting examples of existing networks, vectorizing their weights, and then learning a generative model over the weight space in a supervised fashion. We investigate a pole-balancing task, Cart-Pole, as a case study and show that multiple new pole-balancing networks can be generated from their agent embeddings without direct access to training data from the Cart-Pole simulator. In general, the learned embedding space is helpful for mapping out the space of solutions for a given task. We observe in the case of Cart-Pole the surprising finding that good agents make different decisions despite learning similar representations, whereas bad agents make similar (bad) decisions while learning dissimilar representations. Linearly interpolating between the latent embeddings for a good agent and a bad agent yields an agent embedding that generates a network with intermediate performance, where the performance can be tuned according to the coefficient of interpolation. Linear extrapolation in the latent space also results in performance boosts, up to a point.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04516](http://arxiv.org/abs/1811.04516)

##### PDF
[http://arxiv.org/pdf/1811.04516](http://arxiv.org/pdf/1811.04516)

