---
layout: post
title: "Deep Reinforcement Learning for Sponsored Search Real-time Bidding"
date: 2018-03-01 09:04:37
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization
author: Jun Zhao, Guang Qiu, Ziyu Guan, Wei Zhao, Xiaofei He
mathjax: true
---

* content
{:toc}

##### Abstract
Bidding optimization is one of the most critical problems in online advertising. Sponsored search (SS) auction, due to the randomness of user query behavior and platform nature, usually adopts keyword-level bidding strategies. In contrast, the display advertising (DA), as a relatively simpler scenario for auction, has taken advantage of real-time bidding (RTB) to boost the performance for advertisers. In this paper, we consider the RTB problem in sponsored search auction, named SS-RTB. SS-RTB has a much more complex dynamic environment, due to stochastic user query behavior and more complex bidding policies based on multiple keywords of an ad. Most previous methods for DA cannot be applied. We propose a reinforcement learning (RL) solution for handling the complex dynamic environment. Although some RL methods have been proposed for online advertising, they all fail to address the "environment changing" problem: the state transition probabilities vary between two days. Motivated by the observation that auction sequences of two days share similar transition patterns at a proper aggregation level, we formulate a robust MDP model at hour-aggregation level of the auction data and propose a control-by-model framework for SS-RTB. Rather than generating bid prices directly, we decide a bidding model for impressions of each hour and perform real-time bidding accordingly. We also extend the method to handle the multi-agent problem. We deployed the SS-RTB system in the e-commerce search auction platform of Alibaba. Empirical experiments of offline evaluation and online A/B test demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
出价优化是在线广告中最关键的问题之一。赞助商搜索（SS）拍卖由于用户查询行为和平台性质的随机性，通常采用关键字级竞价策略。相比之下，展示广告（DA）作为一种相对简单的拍卖方案，利用实时出价（RTB）来提升广告商的表现。在本文中，我们考虑了赞助搜索拍卖中的RTB问题，名为SS-RTB。由于随机用户查询行为和基于多个广告关键字的更复杂的出价策略，SS-RTB具有更复杂的动态环境。 DA的大多数以前的方法不能应用。我们提出了用于处理复杂动态环境的强化学习（RL）解决方案。尽管一些RL方法已经被提出用于在线广告，但它们都未能解决“环境变化”问题：状态转换概率在两天之内变化。受观察两天的拍卖序列在适当的聚合级别共享相似的转换模式的驱动，我们在拍卖数据的小时聚合级别制定了健壮的MDP模型，并提出了SS-RTB的逐个模型框架。我们不是直接生成出价，而是决定每小时展示的出价模式，并相应地进行实时出价。我们还扩展了处理多代理问题的方法。我们在阿里巴巴的电子商务搜索拍卖平台部署了SS-RTB系统。离线评估和在线A / B测试的经验实验证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1803.00259](http://arxiv.org/abs/1803.00259)

##### PDF
[http://arxiv.org/pdf/1803.00259](http://arxiv.org/pdf/1803.00259)

