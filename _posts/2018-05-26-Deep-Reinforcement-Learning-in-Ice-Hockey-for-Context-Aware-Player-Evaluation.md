---
layout: post
title: "Deep Reinforcement Learning in Ice Hockey for Context-Aware Player Evaluation"
date: 2018-05-26 19:23:51
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning RNN
author: Guiliang Liu, Oliver Schulte
mathjax: true
---

* content
{:toc}

##### Abstract
A variety of machine learning models have been proposed to assess the performance of players in professional sports. However, they have only a limited ability to model how player performance depends on the game context. This paper proposes a new approach to capturing game context: we apply Deep Reinforcement Learning (DRL) to learn an action-value Q function from 3M play-by-play events in the National Hockey League (NHL). The neural network representation integrates both continuous context signals and game history, using a possession-based LSTM. The learned Q-function is used to value players' actions under different game contexts. To assess a player's overall performance, we introduce a novel Game Impact Metric (GIM) that aggregates the values of the player's actions. Empirical Evaluation shows GIM is consistent throughout a play season, and correlates highly with standard success measures and future salary.

##### Abstract (translated by Google)
已经提出了各种机器学习模型来评估职业体育运动员的表现。但是，他们只能模拟玩家的表现如何依赖于游戏环境。本文提出了一种捕捉游戏情境的新方法：我们应用深度强化学习（DRL）从全国冰球联盟（NHL）的3M比赛事件中学习动作值Q功能。神经网络表示使用基于占有的LSTM整合了连续的上下文信号和游戏历史。学过的Q函数用于评估玩家在不同游戏环境下的行为。为了评估玩家的总体表现，我们引入了一种新颖的游戏影响度量（Game Impact Metric，GIM），它汇总了玩家行为的值。实证评估显示GIM在整个赛季都是一致的，并且与标准成功度量和未来薪水高度相关。

##### URL
[http://arxiv.org/abs/1805.11088](http://arxiv.org/abs/1805.11088)

##### PDF
[http://arxiv.org/pdf/1805.11088](http://arxiv.org/pdf/1805.11088)

