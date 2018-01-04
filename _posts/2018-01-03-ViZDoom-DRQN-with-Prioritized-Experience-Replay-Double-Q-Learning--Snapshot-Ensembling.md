---
layout: post
title: "ViZDoom: DRQN with Prioritized Experience Replay, Double-Q Learning, & Snapshot Ensembling"
date: 2018-01-03 13:49:08
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Christopher Schulze, Marcus Schulze
mathjax: true
---

* content
{:toc}

##### Abstract
ViZDoom is a robust, first-person shooter reinforcement learning environment, characterized by a significant degree of latent state information. In this paper, double-Q learning and prioritized experience replay methods are tested under a certain ViZDoom combat scenario using a competitive deep recurrent Q-network (DRQN) architecture. In addition, an ensembling technique known as snapshot ensembling is employed using a specific annealed learning rate to observe differences in ensembling efficacy under these two methods. Annealed learning rates are important in general to the training of deep neural network models, as they shake up the status-quo and counter a model's tending towards local optima. While both variants show performance exceeding those of built-in AI agents of the game, the known stabilizing effects of double-Q learning are illustrated, and priority experience replay is again validated in its usefulness by showing immediate results early on in agent development, with the caveat that value overestimation is accelerated in this case. In addition, some unique behaviors are observed to develop for priority experience replay (PER) and double-Q (DDQ) variants, and snapshot ensembling of both PER and DDQ proves a valuable method for improving performance of the ViZDoom Marine.

##### Abstract (translated by Google)
ViZDoom是一个强大的第一人称射击强化学习环境，其特点是具有相当程度的潜在状态信息。在本文中，双Q学习和优先体验重放方法在一定的ViZDoom作战场景下使用竞争性深循环Q网络（DRQN）架构进行测试。另外，采用称为快照集合的集合技术，使用特定的退火学习速率来观察这两种方法下的集合效果的差异。退火的学习率对于深度神经网络模型的训练是非常重要的，因为它们改变了现状，并且抵消了模型对局部最优的趋势。虽然这两个变种的性能均超过游戏内置AI代理的性能，但是已经说明了双Q学习的已知稳定效果，并且通过在代理开发早期立即显示结果，再次验证优先级体验的实用性，在这种情况下，值得高估的警告被加速。另外，为了优先体验重播（PER）和双Q（DDQ）变体，还观察到了一些独特的行为，PER和DDQ的快照集成证明了提高ViZDoom Marine性能的有效方法。

##### URL
[http://arxiv.org/abs/1801.01000](http://arxiv.org/abs/1801.01000)

##### PDF
[http://arxiv.org/pdf/1801.01000](http://arxiv.org/pdf/1801.01000)

