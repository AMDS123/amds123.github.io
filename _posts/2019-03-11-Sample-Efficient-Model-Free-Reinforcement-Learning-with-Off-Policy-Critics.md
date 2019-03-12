---
layout: post
title: "Sample-Efficient Model-Free Reinforcement Learning with Off-Policy Critics"
date: 2019-03-11 09:59:58
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Denis Steckelmacher, H&#xe9;l&#xe8;ne Plisnier, Diederik M. Roijers, Ann Now&#xe9;
mathjax: true
---

* content
{:toc}

##### Abstract
Value-based reinforcement-learning algorithms are currently state-of-the-art in model-free discrete-action settings, and tend to outperform actor-critic algorithms. We argue that actor-critic algorithms are currently limited by their need for an on-policy critic, which severely constraints how the critic is learned. We propose Bootstrapped Dual Policy Iteration (BDPI), a novel model-free actor-critic reinforcement-learning algorithm for continuous states and discrete actions, with off-policy critics. Off-policy critics are compatible with experience replay, ensuring high sample-efficiency, without the need for off-policy corrections. The actor, by slowly imitating the average greedy policy of the critics, leads to high-quality and state-specific exploration, which we show approximates Thompson sampling. Because the actor and critics are fully decoupled, BDPI is remarkably stable and, contrary to other state-of-the-art algorithms, unusually forgiving for poorly-configured hyper-parameters. BDPI is significantly more sample-efficient compared to Bootstrapped DQN, PPO, A3C and ACKTR, on a variety of tasks. Source code: https://github.com/vub-ai-lab/bdpi.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.04193](http://arxiv.org/abs/1903.04193)

##### PDF
[http://arxiv.org/pdf/1903.04193](http://arxiv.org/pdf/1903.04193)

