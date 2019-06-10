---
layout: post
title: "Improving Exploration in Soft-Actor-Critic with Normalizing Flows Policies"
date: 2019-06-06 18:43:19
categories: arXiv_AI
tags: arXiv_AI Sparse Reinforcement_Learning
author: Patrick Nadeem Ward, Ariella Smofsky, Avishek Joey Bose
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Reinforcement Learning (DRL) algorithms for continuous action spaces are known to be brittle toward hyperparameters as well as \cut{being}sample inefficient. Soft Actor Critic (SAC) proposes an off-policy deep actor critic algorithm within the maximum entropy RL framework which offers greater stability and empirical gains. The choice of policy distribution, a factored Gaussian, is motivated by \cut{chosen due}its easy re-parametrization rather than its modeling power. We introduce Normalizing Flow policies within the SAC framework that learn more expressive classes of policies than simple factored Gaussians. \cut{We also present a series of stabilization tricks that enable effective training of these policies in the RL setting.}We show empirically on continuous grid world tasks that our approach increases stability and is better suited to difficult exploration in sparse reward settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02771](http://arxiv.org/abs/1906.02771)

##### PDF
[http://arxiv.org/pdf/1906.02771](http://arxiv.org/pdf/1906.02771)

