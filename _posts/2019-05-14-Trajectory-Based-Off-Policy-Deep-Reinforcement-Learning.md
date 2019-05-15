---
layout: post
title: "Trajectory-Based Off-Policy Deep Reinforcement Learning"
date: 2019-05-14 16:35:00
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Gradient_Descent
author: Andreas Doerr, Michael Volpp, Marc Toussaint, Sebastian Trimpe, Christian Daniel
mathjax: true
---

* content
{:toc}

##### Abstract
Policy gradient methods are powerful reinforcement learning algorithms and have been demonstrated to solve many complex tasks. However, these methods are also data-inefficient, afflicted with high variance gradient estimates, and frequently get stuck in local optima. This work addresses these weaknesses by combining recent improvements in the reuse of off-policy data and exploration in parameter space with deterministic behavioral policies. The resulting objective is amenable to standard neural network optimization strategies like stochastic gradient descent or stochastic gradient Hamiltonian Monte Carlo. Incorporation of previous rollouts via importance sampling greatly improves data-efficiency, whilst stochastic optimization schemes facilitate the escape from local optima. We evaluate the proposed approach on a series of continuous control benchmark tasks. The results show that the proposed algorithm is able to successfully and reliably learn solutions using fewer system interactions than standard policy gradient methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05710](https://arxiv.org/abs/1905.05710)

##### PDF
[https://arxiv.org/pdf/1905.05710](https://arxiv.org/pdf/1905.05710)

