---
layout: post
title: "Provably Efficient $Q$-learning with Function Approximation via Distribution Shift Error Checking Oracle"
date: 2019-06-14 17:55:05
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Simon S. Du, Yuping Luo, Ruosong Wang, Hanrui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
$Q$-learning with function approximation is one of the most popular methods in reinforcement learning. Though the idea of using function approximation was proposed at least $60$ years ago, even in the simplest setup, i.e, approximating $Q$-functions with linear functions, it is still an open problem how to design a provably efficient algorithm that learns a near-optimal policy. The key challenges are how to efficiently explore the state space and how to decide when to stop exploring in conjunction with the function approximation scheme. 
 The current paper presents a provably efficient algorithm for $Q$-learning with linear function approximation. Under certain regularity assumptions, our algorithm, Difference Maximization $Q$-learning (DMQ), combined with linear function approximation, returns a near optimal policy using polynomial number of trajectories. Our algorithm introduces a new notion, the Distribution Shift Error Checking (DSEC) oracle. This oracle tests whether there exists a function in the function class that predicts well on a distribution $\mathcal{D}_1$, but predicts poorly on another distribution $\mathcal{D}_2$, where $\mathcal{D}_1$ and $\mathcal{D}_2$ are distributions over states induced by two different exploration policies. For the linear function class, this oracle is equivalent to solving a top eigenvalue problem. We believe our algorithmic insights, especially the DSEC oracle, are also useful in designing and analyzing reinforcement learning algorithms with general function approximation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06321](http://arxiv.org/abs/1906.06321)

##### PDF
[http://arxiv.org/pdf/1906.06321](http://arxiv.org/pdf/1906.06321)

