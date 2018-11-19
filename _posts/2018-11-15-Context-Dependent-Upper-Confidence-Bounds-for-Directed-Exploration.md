---
layout: post
title: "Context-Dependent Upper-Confidence Bounds for Directed Exploration"
date: 2018-11-15 23:43:56
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Raksha Kumaraswamy, Matthew Schlegel, Adam White, Martha White
mathjax: true
---

* content
{:toc}

##### Abstract
Directed exploration strategies for reinforcement learning are critical for learning an optimal policy in a minimal number of interactions with the environment. Many algorithms use optimism to direct exploration, either through visitation estimates or upper confidence bounds, as opposed to data-inefficient strategies like \epsilon-greedy that use random, undirected exploration. Most data-efficient exploration methods require significant computation, typically relying on a learned model to guide exploration. Least-squares methods have the potential to provide some of the data-efficiency benefits of model-based approaches -- because they summarize past interactions -- with the computation closer to that of model-free approaches. In this work, we provide a novel, computationally efficient, incremental exploration strategy, leveraging this property of least-squares temporal difference learning (LSTD). We derive upper confidence bounds on the action-values learned by LSTD, with context-dependent (or state-dependent) noise variance. Such context-dependent noise focuses exploration on a subset of variable states, and allows for reduced exploration in other states. We empirically demonstrate that our algorithm can converge more quickly than other incremental exploration strategies using confidence estimates on action-values.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06629](http://arxiv.org/abs/1811.06629)

##### PDF
[http://arxiv.org/pdf/1811.06629](http://arxiv.org/pdf/1811.06629)

