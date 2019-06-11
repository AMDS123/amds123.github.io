---
layout: post
title: "Making Asynchronous Stochastic Gradient Descent Work for Transformers"
date: 2019-06-08 18:19:50
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Alham Fikri Aji, Kenneth Heafield
mathjax: true
---

* content
{:toc}

##### Abstract
Asynchronous stochastic gradient descent (SGD) is attractive from a speed perspective because workers do not wait for synchronization. However, the Transformer model converges poorly with asynchronous SGD, resulting in substantially lower quality compared to synchronous SGD. To investigate why this is the case, we isolate differences between asynchronous and synchronous methods to investigate batch size and staleness effects. We find that summing several asynchronous updates, rather than applying them immediately, restores convergence behavior. With this hybrid method, Transformer training for neural machine translation task reaches a near-convergence level 1.36x faster in single-node multi-GPU training with no impact on model quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03496](http://arxiv.org/abs/1906.03496)

##### PDF
[http://arxiv.org/pdf/1906.03496](http://arxiv.org/pdf/1906.03496)

