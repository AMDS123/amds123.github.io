---
layout: post
title: "A Theoretical Connection Between Statistical Physics and Reinforcement Learning"
date: 2019-06-24 20:47:42
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Inference Relation
author: Jad Rahme, Ryan P. Adams
mathjax: true
---

* content
{:toc}

##### Abstract
Sequential decision making in the presence of uncertainty and stochastic dynamics gives rise to distributions over state/action trajectories in reinforcement learning (RL) and optimal control problems. This observation has led to a variety of connections between RL and inference in probabilistic graphical models (PGMs). Here we explore a different dimension to this relationship, examining reinforcement learning using the tools and abstractions of statistical physics. The central object in the statistical physics abstraction is the idea of a partition function $\mathcal{Z}$, and here we construct a partition function from the ensemble of possible trajectories that an agent might take in a Markov decision process. Although value functions and $Q$-functions can be derived from this partition function and interpreted via average energies, the $\mathcal{Z}$-function provides an object with its own Bellman equation that can form the basis of alternative dynamic programming approaches. Moreover, when the MDP dynamics are deterministic, the Bellman equation for $\mathcal{Z}$ is linear, allowing direct solutions that are unavailable for the nonlinear equations associated with traditional value functions. The policies learned via these $\mathcal{Z}$-based Bellman updates are tightly linked to Boltzmann-like policy parameterizations. In addition to sampling actions proportionally to the exponential of the expected cumulative reward as Boltzmann policies would, these policies take entropy into account favoring states from which many outcomes are possible.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.10228](http://arxiv.org/abs/1906.10228)

##### PDF
[http://arxiv.org/pdf/1906.10228](http://arxiv.org/pdf/1906.10228)

