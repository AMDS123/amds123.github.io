---
layout: post
title: "A Critical Investigation of Deep Reinforcement Learning for Navigation"
date: 2018-02-07 00:44:59
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning
author: Vikas Dhiman, Shurjo Banerjee, Brent Griffin, Jeffrey M Siskind, Jason J Corso
mathjax: true
---

* content
{:toc}

##### Abstract
The navigation problem is classically approached in two steps: an exploration step, where map-information about the environment is gathered; and an exploitation step, where this information is used to navigate efficiently. Deep reinforcement learning (DRL) algorithms, alternatively, approach the problem of navigation in an end-to-end fashion. Inspired by the classical approach, we ask whether DRL algorithms are able to inherently explore, gather and exploit map-information over the course of navigation. We build upon Mirowski et al. [2017] work and introduce a systematic suite of experiments that vary three parameters: the agent's starting location, the agent's target location, and the maze structure. We choose evaluation metrics that explicitly measure the algorithm's ability to gather and exploit map-information. Our experiments show that when trained and tested on the same maps, the algorithm successfully gathers and exploits map-information. However, when trained and tested on different sets of maps, the algorithm fails to transfer the ability to gather and exploit map-information to unseen maps. Furthermore, we find that when the goal location is randomized and the map is kept static, the algorithm is able to gather and exploit map-information but the exploitation is far from optimal. We open-source our experimental suite in the hopes that it serves as a framework for the comparison of future algorithms and leads to the discovery of robust alternatives to classical navigation methods.

##### Abstract (translated by Google)
导航问题通常分两步进行：探索步骤，收集有关环境的地图信息;和一个开发步骤，这个信息被用来有效的导航。深度强化学习（DRL）算法或者以端到端的方式处理导航问题。受古典方法的启发，我们问DRL算法是否能够在导航过程中内在地探索，收集和利用地图信息。我们建立在Mirowski et al。 [2017]的工作，并介绍了一个系统的实验变化三个参数：代理的起始位置，代理的目标位置，和迷宫结构的实验。我们选择评估指标，明确衡量算法收集和利用地图信息的能力。我们的实验表明，当在相同的地图上进行训练和测试时，该算法成功收集和利用地图信息。然而，当在不同的地图上进行训练和测试时，该算法无法将收集和利用地图信息的能力转移到不可见的地图上。此外，我们发现，当目标位置是随机的，并且地图保持静态时，该算法能够收集和利用地图信息，但是开发并不是最优的。我们开放我们的实验套件，希望它可以作为未来算法的比较框架，并导致发现经典导航方法的稳健替代品。

##### URL
[https://arxiv.org/abs/1802.02274](https://arxiv.org/abs/1802.02274)

##### PDF
[https://arxiv.org/pdf/1802.02274](https://arxiv.org/pdf/1802.02274)

