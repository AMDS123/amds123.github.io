---
layout: post
title: "PIPPS: Flexible Model-Based Policy Search Robust to the Curse of Chaos"
date: 2019-02-04 15:12:55
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Inference Deep_Learning
author: Paavo Parmas, Carl Edward Rasmussen, Jan Peters, Kenji Doya
mathjax: true
---

* content
{:toc}

##### Abstract
Previously, the exploding gradient problem has been explained to be central in deep learning and model-based reinforcement learning, because it causes numerical issues and instability in optimization. Our experiments in model-based reinforcement learning imply that the problem is not just a numerical issue, but it may be caused by a fundamental chaos-like nature of long chains of nonlinear computations. Not only do the magnitudes of the gradients become large, the direction of the gradients becomes essentially random. We show that reparameterization gradients suffer from the problem, while likelihood ratio gradients are robust. Using our insights, we develop a model-based policy search framework, Probabilistic Inference for Particle-Based Policy Search (PIPPS), which is easily extensible, and allows for almost arbitrary models and policies, while simultaneously matching the performance of previous data-efficient learning algorithms. Finally, we invent the total propagation algorithm, which efficiently computes a union over all pathwise derivative depths during a single backwards pass, automatically giving greater weight to estimators with lower variance, sometimes improving over reparameterization gradients by $10^6$ times.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.01240](http://arxiv.org/abs/1902.01240)

##### PDF
[http://arxiv.org/pdf/1902.01240](http://arxiv.org/pdf/1902.01240)

