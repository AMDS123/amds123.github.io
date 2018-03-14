---
layout: post
title: "Bayesian Optimization with Automatic Prior Selection for Data-Efficient Direct Policy Search"
date: 2018-03-13 16:45:49
categories: arXiv_AI
tags: arXiv_AI Transfer_Learning Optimization
author: R&#xe9;mi Pautrat, Konstantinos Chatzilygeroudis, Jean-Baptiste Mouret
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most interesting features of Bayesian optimization for direct policy search is that it can leverage priors (e.g., from simulation or from previous tasks) to accelerate learning on a robot. In this paper, we are interested in situations for which several priors exist but we do not know in advance which one fits best the current situation. We tackle this problem by introducing a novel acquisition function, called Most Likely Expected Improvement (MLEI), that combines the likelihood of the priors and the expected improvement. We evaluate this new acquisition function on a transfer learning task for a 5-DOF planar arm and on a possibly damaged, 6-legged robot that has to learn to walk on flat ground and on stairs, with priors corresponding to different stairs and different kinds of damages. Our results show that MLEI effectively identifies and exploits the priors, even when there is no obvious match between the current situations and the priors.

##### Abstract (translated by Google)
用于直接策略搜索的贝叶斯优化的最有趣的特征之一是它可以利用先验（例如，来自仿真或来自先前的任务）来加速机器人的学习。在本文中，我们感兴趣的是存在几个先验的情况，但我们事先不知道哪一个最适合当前情况。我们通过引入一种称为最可能预期改进（MLEI）的新型采集功能来解决这个问题，该功能结合了先验可能性和预期改进。我们评估了这种新的采集功能，用于5-DOF平面手臂和可能受损的6腿机器人的转移学习任务，该机器人必须学会在平坦的地面和楼梯上行走，并且对应于不同的楼梯和不同的类型的损失。我们的研究结果表明，MLEI有效地识别和利用先验，即使当前情况和先验之间没有明显的匹配。

##### URL
[http://arxiv.org/abs/1709.06919](http://arxiv.org/abs/1709.06919)

##### PDF
[http://arxiv.org/pdf/1709.06919](http://arxiv.org/pdf/1709.06919)

