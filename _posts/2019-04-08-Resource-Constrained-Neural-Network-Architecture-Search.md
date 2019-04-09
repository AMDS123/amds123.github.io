---
layout: post
title: "Resource Constrained Neural Network Architecture Search"
date: 2019-04-08 00:39:27
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning Optimization
author: Yunyang Xiong, Ronak Mehta, Vikas Singh
mathjax: true
---

* content
{:toc}

##### Abstract
The design of neural network architectures is frequently either based on human expertise using trial/error and empirical feedback or tackled via large scale reinforcement learning strategies run over distinct discrete architecture choices. In the latter case, the optimization task is non-differentiable and also not very amenable to derivative-free optimization methods. Most methods in use today require exorbitant computational resources. And if we want networks that additionally satisfy resource constraints, the above challenges are exacerbated because the search procedure must now balance accuracy with certain budget constraints on resources. We formulate this problem as the optimization of a set function - we find that the empirical behavior of this set function often (but not always) satisfies marginal gain and monotonicity principles - properties central to the idea of submodularity. Based on this observation, we adapt algorithms that are well-known within discrete optimization to obtain heuristic schemes for neural network architecture search, with resource constraints on the architecture. This simple scheme when applied on CIFAR-100 and ImageNet, identifies resource-constrained architectures with quantifiably better performance than current state-of-the-art models designed for mobile devices. Specifically, we find high-performing architectures with fewer parameters and computations by a search method that is much faster.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03786](http://arxiv.org/abs/1904.03786)

##### PDF
[http://arxiv.org/pdf/1904.03786](http://arxiv.org/pdf/1904.03786)

