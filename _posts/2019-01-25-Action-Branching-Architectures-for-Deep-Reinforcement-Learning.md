---
layout: post
title: "Action Branching Architectures for Deep Reinforcement Learning"
date: 2019-01-25 04:01:24
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Arash Tavakoli, Fabio Pardo, Petar Kormushev
mathjax: true
---

* content
{:toc}

##### Abstract
Discrete-action algorithms have been central to numerous recent successes of deep reinforcement learning. However, applying these algorithms to high-dimensional action tasks requires tackling the combinatorial increase of the number of possible actions with the number of action dimensions. This problem is further exacerbated for continuous-action tasks that require fine control of actions via discretization. In this paper, we propose a novel neural architecture featuring a shared decision module followed by several network branches, one for each action dimension. This approach achieves a linear increase of the number of network outputs with the number of degrees of freedom by allowing a level of independence for each individual action dimension. To illustrate the approach, we present a novel agent, called Branching Dueling Q-Network (BDQ), as a branching variant of the Dueling Double Deep Q-Network (Dueling DDQN). We evaluate the performance of our agent on a set of challenging continuous control tasks. The empirical results show that the proposed agent scales gracefully to environments with increasing action dimensionality and indicate the significance of the shared decision module in coordination of the distributed action branches. Furthermore, we show that the proposed agent performs competitively against a state-of-the-art continuous control algorithm, Deep Deterministic Policy Gradient (DDPG).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.08946](http://arxiv.org/abs/1711.08946)

##### PDF
[http://arxiv.org/pdf/1711.08946](http://arxiv.org/pdf/1711.08946)

