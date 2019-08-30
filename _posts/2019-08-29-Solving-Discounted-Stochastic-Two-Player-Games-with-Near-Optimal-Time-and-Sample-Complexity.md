---
layout: post
title: "Solving Discounted Stochastic Two-Player Games with Near-Optimal Time and Sample Complexity"
date: 2019-08-29 07:04:25
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Aaron Sidford, Mengdi Wang, Lin F. Yang, Yinyu Ye
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we settle the sampling complexity of solving discounted two-player turn-based zero-sum stochastic games up to polylogarithmic factors. Given a stochastic game with discount factor $\gamma\in(0,1)$ we provide an algorithm that computes an $\epsilon$-optimal strategy with high-probability given $\tilde{O}((1 - \gamma)^{-3} \epsilon^{-2})$ samples from the transition function for each state-action-pair. Our algorithm runs in time nearly linear in the number of samples and uses space nearly linear in the number of state-action pairs. As stochastic games generalize Markov decision processes (MDPs) our runtime and sample complexities are optimal due to Azar et al (2013). We achieve our results by showing how to generalize a near-optimal Q-learning based algorithms for MDP, in particular Sidford et al (2018), to two-player strategy computation algorithms. This overcomes limitations of standard Q-learning and strategy iteration or alternating minimization based approaches and we hope will pave the way for future reinforcement learning results by facilitating the extension of MDP results to multi-agent settings with little loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11071](http://arxiv.org/abs/1908.11071)

##### PDF
[http://arxiv.org/pdf/1908.11071](http://arxiv.org/pdf/1908.11071)

