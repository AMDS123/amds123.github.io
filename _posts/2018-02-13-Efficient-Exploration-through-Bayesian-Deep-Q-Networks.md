---
layout: post
title: "Efficient Exploration through Bayesian Deep Q-Networks"
date: 2018-02-13 00:48:17
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kamyar Azizzadenesheli, Emma Brunskill, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Bayesian Deep Q-Network (BDQN), a practical Thompson sampling based Reinforcement Learning (RL) Algorithm. Thompson sampling allows for targeted exploration in high dimensions through posterior sampling but is usually computationally expensive. We address this limitation by introducing uncertainty only at the output layer of the network through a Bayesian Linear Regression (BLR) model. This layer can be trained with fast closed-form updates and its samples can be drawn efficiently through the Gaussian distribution. We apply our method to a wide range of Atari games in Arcade Learning Environments. Since BDQN carries out more efficient exploration, it is able to reach higher rewards substantially faster than a key baseline, the double deep Q network (DDQN).

##### Abstract (translated by Google)
我们提出贝叶斯深Q网络（BDQN），一种基于实际汤普森抽样的强化学习（RL）算法。汤普森采样允许通过后采样进行高维有针对性的探测，但通常在计算上是昂贵的。我们通过贝叶斯线性回归（BLR）模型通过仅在网络的输出层引入不确定性来解决这个限制。该层可以用快速封闭形式更新进行训练，其样本可以通过高斯分布有效地绘制。我们将我们的方法应用于街机学习环境中的各种Atari游戏。由于BDQN进行更有效的探索，它能够比关键基线 - 双深度Q网络（DDQN）快得多获得更高的回报。

##### URL
[http://arxiv.org/abs/1802.04412](http://arxiv.org/abs/1802.04412)

##### PDF
[http://arxiv.org/pdf/1802.04412](http://arxiv.org/pdf/1802.04412)

