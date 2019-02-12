---
layout: post
title: "Social Influence as Intrinsic Motivation for Multi-Agent Deep Reinforcement Learning"
date: 2019-02-08 23:52:07
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Natasha Jaques, Angeliki Lazaridou, Edward Hughes, Caglar Gulcehre, Pedro A. Ortega, DJ Strouse, Joel Z. Leibo, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a unified mechanism for achieving coordination and communication in Multi-Agent Reinforcement Learning (MARL), through rewarding agents for having causal influence over other agents' actions. Causal influence is assessed using counterfactual reasoning. At each timestep, an agent simulates alternate actions that it could have taken, and computes their effect on the behavior of other agents. Actions that lead to bigger changes in other agents' behavior are considered influential and are rewarded. We show that this is equivalent to rewarding agents for having high mutual information between their actions. Empirical results demonstrate that influence leads to enhanced coordination and communication in challenging social dilemma environments, dramatically increasing the learning curves of the deep RL agents, and leading to more meaningful learned communication protocols. The influence rewards for all agents can be computed in a decentralized way by enabling agents to learn a model of other agents using deep neural networks. In contrast, key previous works on emergent communication in the MARL setting were unable to learn diverse policies in a decentralized manner and had to resort to centralized training. Consequently, the influence reward opens up a window of new opportunities for research in this area.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08647](http://arxiv.org/abs/1810.08647)

##### PDF
[http://arxiv.org/pdf/1810.08647](http://arxiv.org/pdf/1810.08647)

