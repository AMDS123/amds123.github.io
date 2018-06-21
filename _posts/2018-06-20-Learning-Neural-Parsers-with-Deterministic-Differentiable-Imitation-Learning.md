---
layout: post
title: "Learning Neural Parsers with Deterministic Differentiable Imitation Learning"
date: 2018-06-20 16:15:54
categories: arXiv_AI
tags: arXiv_AI Segmentation Reinforcement_Learning Optimization
author: Tanmay Shankar, Nicholas Rhinehart, Katharina Muelling, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of spatial segmentation of a 2D object in the context of a robotic system for painting, where an optimal segmentation depends on both the appearance of the object and the size of each segment. Since each segment must take into account appearance features at several scales, we take a hierarchical grammar-based parsing approach to decompose the object into 2D segments for painting. Since there are many ways to segment an object the solution space is extremely large and it is very challenging to utilize an exploration based optimization approach like reinforcement learning. Instead, we pose the segmentation problem as an imitation learning problem by using a segmentation algorithm in the place of an expert, that has access to a small dataset with known foreground-background segmentations. During the imitation learning process, we learn to imitate the oracle (segmentation algorithm) using only the image of the object, without the use of the known foreground-background segmentations. We introduce a novel deterministic policy gradient update, DRAG, in the form of a deterministic actor-critic variant of AggreVaTeD, to train our neural network based object parser. We will also show that our approach can be seen as extending DDPG to the Imitation Learning scenario. Training our neural parser to imitate the oracle via DRAG allow our neural parser to outperform several existing imitation learning approaches.

##### Abstract (translated by Google)
我们解决了机器人绘画系统中2D对象的空间分割问题，其中最佳分割取决于对象的外观和每个分段的大小。由于每个片段都必须考虑多个尺度的外观特征，因此我们采用基于分层语法的解析方法将对象分解为2D片段进行绘制。由于分割对象的方法很多，因此解决方案空间非常大，利用基于探索的优化方法（如强化学习）非常具有挑战性。相反，我们通过使用分割算法代替专家，将分割问题作为模仿学习问题提出，可以访问具有已知前景 - 背景分割的小数据集。在模仿学习过程中，我们学习仅使用对象的图像模仿oracle（分割算法），而不使用已知的前景背景分割。我们引入了一种新颖的确定性策略梯度更新DRAG，以AggreVaTeD的确定性演员 - 评论者变体形式来训练基于神经网络的对象解析器。我们还会表明，我们的方法可以被看作是将DDPG扩展到模仿学习场景。训练我们的神经解析器通过DRAG模仿oracle，使我们的神经解析器能够胜过几种现有的模拟学习方法。

##### URL
[http://arxiv.org/abs/1806.07822](http://arxiv.org/abs/1806.07822)

##### PDF
[http://arxiv.org/pdf/1806.07822](http://arxiv.org/pdf/1806.07822)

