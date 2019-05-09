---
layout: post
title: "Bayesian Policy Optimization for Model Uncertainty"
date: 2019-05-08 15:04:45
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Gilwoo Lee, Brian Hou, Aditya Mandalika, Jeongseok Lee, Sanjiban Choudhury, Siddhartha S. Srinivasa
mathjax: true
---

* content
{:toc}

##### Abstract
Addressing uncertainty is critical for autonomous systems to robustly adapt to the real world. We formulate the problem of model uncertainty as a continuous Bayes-Adaptive Markov Decision Process (BAMDP), where an agent maintains a posterior distribution over latent model parameters given a history of observations and maximizes its expected long-term reward with respect to this belief distribution. Our algorithm, Bayesian Policy Optimization, builds on recent policy optimization algorithms to learn a universal policy that navigates the exploration-exploitation trade-off to maximize the Bayesian value function. To address challenges from discretizing the continuous latent parameter space, we propose a new policy network architecture that encodes the belief distribution independently from the observable state. Our method significantly outperforms algorithms that address model uncertainty without explicitly reasoning about belief distributions and is competitive with state-of-the-art Partially Observable Markov Decision Process solvers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01014](http://arxiv.org/abs/1810.01014)

##### PDF
[http://arxiv.org/pdf/1810.01014](http://arxiv.org/pdf/1810.01014)

