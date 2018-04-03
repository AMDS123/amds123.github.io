---
layout: post
title: "Exploring to learn visual saliency: The RL-IAC approach"
date: 2018-04-02 09:39:22
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Reinforcement_Learning Detection Recognition
author: Celine Craye, Timothee Lesort, David Filliat, Jean-Francois Goudou
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of object localization and recognition on autonomous mobile robots is still an active topic. In this context, we tackle the problem of learning a model of visual saliency directly on a robot. This model, learned and improved on-the-fly during the robot's exploration provides an efficient tool for localizing relevant objects within their environment. The proposed approach includes two intertwined components. On the one hand, we describe a method for learning and incrementally updating a model of visual saliency from a depth-based object detector. This model of saliency can also be exploited to produce bounding box proposals around objects of interest. On the other hand, we investigate an autonomous exploration technique to efficiently learn such a saliency model. The proposed exploration, called Reinforcement Learning-Intelligent Adaptive Curiosity (RL-IAC) is able to drive the robot's exploration so that samples selected by the robot are likely to improve the current model of saliency. We then demonstrate that such a saliency model learned directly on a robot outperforms several state-of-the-art saliency techniques, and that RL-IAC can drastically decrease the required time for learning a reliable saliency model.

##### Abstract (translated by Google)
自主移动机器人的物体定位和识别问题仍然是一个活跃的话题。在这种情况下，我们直接在机器人上解决学习视觉显着模型的问题。这种在机器人探索过程中实时学习和改进的模型为在其环境中定位相关对象提供了一种高效的工具。所提出的方法包括两个相互交织的组件。一方面，我们描述了一种用于从基于深度的对象检测器学习和逐步更新视觉显着性模型的方法。这种显着性模型也可以用来围绕感兴趣的对象产生边界框建议。另一方面，我们调查自主探索技术，以有效地学习这种显着性模型。所提出的探索称为增强学习 - 智能自适应好奇（RL-IAC）能够驱动机器人的探索，使得机器人选择的样本可能改善当前的显着性模型。然后我们证明，直接在机器人上学习的这种显着性模型胜过了几种最先进的显着性技术，并且RL-IAC可以大大减少学习可靠显着性模型所需的时间。

##### URL
[http://arxiv.org/abs/1804.00435](http://arxiv.org/abs/1804.00435)

##### PDF
[http://arxiv.org/pdf/1804.00435](http://arxiv.org/pdf/1804.00435)

