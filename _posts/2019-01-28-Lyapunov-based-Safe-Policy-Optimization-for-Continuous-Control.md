---
layout: post
title: "Lyapunov-based Safe Policy Optimization for Continuous Control"
date: 2019-01-28 23:14:58
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Yinlam Chow, Ofir Nachum, Aleksandra Faust, Mohammad Ghavamzadeh, Edgar Duenez-Guzman
mathjax: true
---

* content
{:toc}

##### Abstract
We study continuous action reinforcement learning problems in which it is crucial that the agent interacts with the environment only through {\em safe} policies, i.e.,~policies that do not take the agent to undesirable situations. We formulate these problems as {\em constrained} Markov decision processes (CMDPs) and present safe policy optimization algorithms that are based on a {\em Lyapunov} approach to solve them. Our algorithms can use any standard policy gradient (PG) method, such as deep deterministic policy gradient (DDPG) or proximal policy optimization (PPO), to train a neural network policy, while guaranteeing near-constraint satisfaction for every policy update by projecting either the policy parameter or the action onto the set of feasible solutions induced by the state-dependent linearized Lyapunov constraints. Compared to the existing constrained PG algorithms, ours are more data efficient as they are able to utilize both on-policy and off-policy data. Moreover, our action-projection algorithm often leads to less conservative policy updates and allows for natural integration into an end-to-end PG training pipeline. We evaluate our algorithms and compare them with the state-of-the-art baselines on several simulated (MuJoCo) tasks, as well as a real-world indoor robot navigation problem, demonstrating their effectiveness in terms of balancing performance and constraint satisfaction. Videos of the experiments can be found in the following link: https://drive.google.com/file/d/1pzuzFqWIE710bE2U6DmS59AfRzqK2Kek/view?usp=sharing .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10031](http://arxiv.org/abs/1901.10031)

##### PDF
[http://arxiv.org/pdf/1901.10031](http://arxiv.org/pdf/1901.10031)

