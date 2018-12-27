---
layout: post
title: "SNAS: Stochastic Neural Architecture Search"
date: 2018-12-24 14:13:16
categories: arXiv_AI
tags: arXiv_AI Attention Optimization
author: Sirui Xie, Hehui Zheng, Chunxiao Liu, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Stochastic Neural Architecture Search (SNAS), an economical end-to-end solution to Neural Architecture Search (NAS) that trains neural operation parameters and architecture distribution parameters in same round of back-propagation, while maintaining the completeness and differentiability of the NAS pipeline. In this work, NAS is reformulated as an optimization problem on parameters of a joint distribution for the search space in a cell. To leverage the gradient information in generic differentiable loss for architecture search, a novel search gradient is proposed. We prove that this search gradient optimizes the same objective as reinforcement-learning-based NAS, but assigns credits to structural decisions more efficiently. This credit assignment is further augmented with locally decomposable reward to enforce a resource-efficient constraint. In experiments on CIFAR-10, SNAS takes less epochs to find a cell architecture with state-of-the-art accuracy than non-differentiable evolution-based and reinforcement-learning-based NAS, which is also transferable to ImageNet. It is also shown that child networks of SNAS can maintain the validation accuracy in searching, with which attention-based NAS requires parameter retraining to compete, exhibiting potentials to stride towards efficient NAS on big datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09926](http://arxiv.org/abs/1812.09926)

##### PDF
[http://arxiv.org/pdf/1812.09926](http://arxiv.org/pdf/1812.09926)

