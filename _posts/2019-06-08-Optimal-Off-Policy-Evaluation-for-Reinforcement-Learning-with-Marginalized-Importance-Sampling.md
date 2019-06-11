---
layout: post
title: "Optimal Off-Policy Evaluation for Reinforcement Learning with Marginalized Importance Sampling"
date: 2019-06-08 05:15:34
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Tengyang Xie, Yifei Ma, Yu-Xiang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the many real-world applications of reinforcement learning (RL) that require safe-policy iterations, we consider the problem of off-policy evaluation (OPE) --- the problem of evaluating a new policy using the historical data obtained by different behavior policies --- under the model of nonstationary episodic Markov Decision Processes with a long horizon and large action space. Existing importance sampling (IS) methods often suffer from large variance that depends exponentially on the RL horizon $H$. To solve this problem, we consider a marginalized importance sampling (MIS) estimator that recursively estimates the state marginal distribution for the target policy at every step. MIS achieves a mean-squared error of $O(H^2R_{\max}^2\sum_{t=1}^H\mathbb E_\mu[(w_{\pi,\mu}(s_t,a_t))^2]/n)$ for large $n$, where $w_{\pi,\mu}(s_t,a_t)$ is the ratio of the marginal distribution of $t$th step under $\pi$ and $\mu$, $H$ is the horizon, $R_{\max}$ is the maximal rewards, and $n$ is the sample size. The result nearly matches the Cramer-Rao lower bounds for DAG MDP in \citet{jiang2016doubly} for most non-trivial regimes. To the best of our knowledge, this is the first OPE estimator with provably optimal dependence in $H$ and the second moments of the importance weight. Besides theoretical optimality, we empirically demonstrate the superiority of our method in time-varying, partially observable, and long-horizon RL environments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03393](http://arxiv.org/abs/1906.03393)

##### PDF
[http://arxiv.org/pdf/1906.03393](http://arxiv.org/pdf/1906.03393)

