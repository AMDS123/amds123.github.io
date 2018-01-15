---
layout: post
title: "Model-Based Action Exploration"
date: 2018-01-11 19:05:38
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Prediction
author: Glen Berseth, Michiel van de Panne
mathjax: true
---

* content
{:toc}

##### Abstract
Deep reinforcement learning has great stride in solving challenging motion control tasks. 
 Recently there has been a significant amount of work on methods to exploit the data gathered during training, but less work is done on good methods for generating data to learn from. 
 For continuous actions domains, the typical method for generating exploratory actions is by sampling from a Gaussian distribution centred around the mean of a policy. 
 Although these methods can find an optimal policy, in practise, they do not scale well, and solving environments with many actions dimensions becomes impractical. 
 We consider learning a forward dynamics model to predict the result, ($s_{t+1}$), of taking a particular action, ($a$), given a specific observation of the state, ($s_{t}$). 
 With a model such as this we, can perform what comes more naturally to biological systems that have already collect experience, we perform internal predictions of outcomes and endeavour to try actions we believe have a reasonable chance of success. 
 This method greatly reduces the space of exploratory actions, increasing learning speed and enables higher quality solutions to difficult problems, such as robotic locomotion.

##### Abstract (translated by Google)
深度强化学习在解决具有挑战性的运动控制任务方面有很大的进步
 最近，在培训过程中收集数据的方法方面已经做了大量的工作，但是为了生成可以学习的数据的好方法却做了很少的工作。
 对于连续行为域，产生探索性行为的典型方法是从以策略平均值为中心的高斯分布中采样。
 虽然这些方法可以找到一个最优策略，但是在实践中，它们不能很好地扩展，解决多个行为维度的环境变得不切实际。
 我们考虑学习一个正向动力学模型来预测结果，（$ s_ {t + 1} $），采取一个特定的行动，（$ a $），给定一个特定的观察状态，（$ s_ {t} $ ）。
 有了这样一个模型，我们可以对已经收集经验的生物系统进行更自然的操作，我们对结果进行内部预测，并努力尝试我们认为有合理成功机会的行动。
 这种方法极大地减少了探索行为的空间，提高了学习速度，并为诸如机器人运动等难题提供了更高质量的解决方案。

##### URL
[http://arxiv.org/abs/1801.03954](http://arxiv.org/abs/1801.03954)

##### PDF
[http://arxiv.org/pdf/1801.03954](http://arxiv.org/pdf/1801.03954)

