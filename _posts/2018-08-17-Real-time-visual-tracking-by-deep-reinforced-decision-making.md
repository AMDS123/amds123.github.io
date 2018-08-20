---
layout: post
title: "Real-time visual tracking by deep reinforced decision making"
date: 2018-08-17 05:21:47
categories: arXiv_CV
tags: arXiv_CV Tracking Reinforcement_Learning
author: Janghoon Choi, Junseok Kwon, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major challenges of model-free visual tracking problem has been the difficulty originating from the unpredictable and drastic changes in the appearance of objects we target to track. Existing methods tackle this problem by updating the appearance model on-line in order to adapt to the changes in the appearance. Despite the success of these methods however, inaccurate and erroneous updates of the appearance model result in a tracker drift. In this paper, we introduce a novel real-time visual tracking algorithm based on a template selection strategy constructed by deep reinforcement learning methods. The tracking algorithm utilizes this strategy to choose the appropriate template for tracking a given frame. The template selection strategy is self-learned by utilizing a simple policy gradient method on numerous training episodes randomly generated from a tracking benchmark dataset. Our proposed reinforcement learning framework is generally applicable to other confidence map based tracking algorithms. The experiment shows that our tracking algorithm runs in real-time speed of 43 fps and the proposed policy network effectively decides the appropriate template for successful visual tracking.

##### Abstract (translated by Google)
无模型视觉跟踪问题的主要挑战之一是难以产生我们目标跟踪的物体外观的不可预测和剧烈变化。现有方法通过在线更新外观模型来解决该问题，以适应外观的变化。然而，尽管这些方法取得了成功，但外观模型的不准确和错误更新导致跟踪器漂移。在本文中，我们介绍了一种基于深度强化学习方法构建的模板选择策略的新型实时视觉跟踪算法。跟踪算法利用该策略来选择用于跟踪给定帧的适当模板。通过在跟踪基准数据集随机生成的众多训练集中使用简单的策略梯度方法来自学习模板选择策略。我们提出的强化学习框架通常适用于其他基于置信图的跟踪算法。实验表明，我们的跟踪算法以43 fps的实时速度运行，并且所提出的策略网络有效地决定了成功的视觉跟踪的适当模板。

##### URL
[http://arxiv.org/abs/1702.06291](http://arxiv.org/abs/1702.06291)

##### PDF
[http://arxiv.org/pdf/1702.06291](http://arxiv.org/pdf/1702.06291)

