---
layout: post
title: "An Improved Convergence Analysis of Stochastic Variance-Reduced Policy Gradient"
date: 2019-05-29 17:57:23
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Pan Xu, Felicia Gao, Quanquan Gu
mathjax: true
---

* content
{:toc}

##### Abstract
We revisit the stochastic variance-reduced policy gradient (SVRPG) method proposed by Papini et al. (2018) for reinforcement learning. We provide an improved convergence analysis of SVRPG and show that it can find an $\epsilon$-approximate stationary point of the performance function within $O(1/\epsilon^{5/3})$ trajectories. This sample complexity improves upon the best known result $O(1/\epsilon^2)$ by a factor of $O(1/\epsilon^{1/3})$. At the core of our analysis is (i) a tighter upper bound for the variance of importance sampling weights, where we prove that the variance can be controlled by the parameter distance between different policies; and (ii) a fine-grained analysis of the epoch length and batch size parameters such that we can significantly reduce the number of trajectories required in each iteration of SVRPG. We also empirically demonstrate the effectiveness of our theoretical claims of batch sizes on reinforcement learning benchmark tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12615](http://arxiv.org/abs/1905.12615)

##### PDF
[http://arxiv.org/pdf/1905.12615](http://arxiv.org/pdf/1905.12615)

