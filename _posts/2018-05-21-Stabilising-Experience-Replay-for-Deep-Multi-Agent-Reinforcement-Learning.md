---
layout: post
title: "Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning"
date: 2018-05-21 08:24:02
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Deep_Learning
author: Jakob Foerster, Nantas Nardelli, Gregory Farquhar, Triantafyllos Afouras, Philip H. S. Torr, Pushmeet Kohli, Shimon Whiteson
mathjax: true
---

* content
{:toc}

##### Abstract
Many real-world problems, such as network packet routing and urban traffic control, are naturally modeled as multi-agent reinforcement learning (RL) problems. However, existing multi-agent RL methods typically scale poorly in the problem size. Therefore, a key challenge is to translate the success of deep learning on single-agent RL to the multi-agent setting. A major stumbling block is that independent Q-learning, the most popular multi-agent RL method, introduces nonstationarity that makes it incompatible with the experience replay memory on which deep Q-learning relies. This paper proposes two methods that address this problem: 1) using a multi-agent variant of importance sampling to naturally decay obsolete data and 2) conditioning each agent's value function on a fingerprint that disambiguates the age of the data sampled from the replay memory. Results on a challenging decentralised variant of StarCraft unit micromanagement confirm that these methods enable the successful combination of experience replay with multi-agent RL.

##### Abstract (translated by Google)
许多现实世界的问题，例如网络分组路由和城市交通控制，都被自然地建模为多智能体强化学习（RL）问题。然而，现有的多智能体RL方法通常在问题规模上缩小。因此，一个关键的挑战是将单一代理RL的深度学习的成功转化为多代理设置。一个主要的绊脚石是独立的Q-learning，最流行的多智能体RL方法，引入了非平稳性，这使得它与深度Q-learning所依赖的体验重放记忆不兼容。本文提出了两种解决此问题的方法：1）使用重要性抽样的多智体变体来自然衰减过时数据; 2）调整每个智能体的价值函数，以消除从重播内存采样数据的年龄。对星际争霸单位微观管理的具有挑战性的分散式变体的结果证实，这些方法能够使体验重播与多代理RL成功结合。

##### URL
[http://arxiv.org/abs/1702.08887](http://arxiv.org/abs/1702.08887)

##### PDF
[http://arxiv.org/pdf/1702.08887](http://arxiv.org/pdf/1702.08887)

