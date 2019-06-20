---
layout: post
title: "When to Trust Your Model: Model-Based Policy Optimization"
date: 2019-06-19 17:54:53
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Michael Janner, Justin Fu, Marvin Zhang, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Designing effective model-based reinforcement learning algorithms is difficult because the ease of data generation must be weighed against the bias of model-generated data. In this paper, we study the role of model usage in policy optimization both theoretically and empirically. We first formulate and analyze a model-based reinforcement learning algorithm with a guarantee of monotonic improvement at each step. In practice, this analysis is overly pessimistic and suggests that real off-policy data is always preferable to model-generated on-policy data, but we show that an empirical estimate of model generalization can be incorporated into such analysis to justify model usage. Motivated by this analysis, we then demonstrate that a simple procedure of using short model-generated rollouts branched from real data has the benefits of more complicated model-based algorithms without the usual pitfalls. In particular, this approach surpasses the sample efficiency of prior model-based methods, matches the asymptotic performance of the best model-free algorithms, and scales to horizons that cause other model-based methods to fail entirely.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08253](http://arxiv.org/abs/1906.08253)

##### PDF
[http://arxiv.org/pdf/1906.08253](http://arxiv.org/pdf/1906.08253)

