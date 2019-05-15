---
layout: post
title: "TauRieL: Targeting Traveling Salesman Problem with a deep reinforcement learning inspired architecture"
date: 2019-05-14 12:49:32
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Embedding
author: Gorker Alp Malazgirt, Osman S. Unsal, Adrian Cristal Kestelman
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose TauRieL and target Traveling Salesman Problem (TSP) since it has broad applicability in theoretical and applied sciences. TauRieL utilizes an actor-critic inspired architecture that adopts ordinary feedforward nets to obtain a policy update vector $v$. Then, we use $v$ to improve the state transition matrix from which we generate the policy. Also, the state transition matrix allows the solver to initialize from precomputed solutions such as nearest neighbors. In an online learning setting, TauRieL unifies the training and the search where it can generate near-optimal results in seconds. The input to the neural nets in the actor-critic architecture are raw 2-D inputs, and the design idea behind this decision is to keep neural nets relatively smaller than the architectures with wide embeddings with the tradeoff of omitting any distributed representations of the embeddings. Consequently, TauRieL generates TSP solutions two orders of magnitude faster per TSP instance as compared to state-of-the-art offline techniques with a performance impact of 6.1\% in the worst case.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05567](https://arxiv.org/abs/1905.05567)

##### PDF
[https://arxiv.org/pdf/1905.05567](https://arxiv.org/pdf/1905.05567)

