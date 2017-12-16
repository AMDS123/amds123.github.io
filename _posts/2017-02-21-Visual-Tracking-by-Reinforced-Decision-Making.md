---
layout: post
title: "Visual Tracking by Reinforced Decision Making"
date: 2017-02-21 08:15:51
categories: arXiv_CV
tags: arXiv_CV Tracking Reinforcement_Learning
author: Janghoon Choi, Junseok Kwon, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major challenges of model-free visual tracking problem has been the difficulty originating from the unpredictable and drastic changes in the appearance of objects we target to track. Existing methods tackle this problem by updating the appearance model on-line in order to adapt to the changes in the appearance. Despite the success of these methods however, inaccurate and erroneous updates of the appearance model result in a tracker drift. In this paper, we introduce a novel visual tracking algorithm based on a template selection strategy constructed by deep reinforcement learning methods. The tracking algorithm utilizes this strategy to choose the best template for tracking a given frame. The template selection strategy is self-learned by utilizing a simple policy gradient method on numerous training episodes randomly generated from a tracking benchmark dataset. Our proposed reinforcement learning framework is generally applicable to other confidence map based tracking algorithms. The experiment shows that our tracking algorithm effectively decides the best template for visual tracking.

##### Abstract (translated by Google)
无模型视觉跟踪问题的一个主要挑战是来自我们追踪的物体的外观的不可预测和剧烈变化的困难。现有的方法通过在线更新外观模型来解决这个问题，以适应外观的变化。尽管这些方法取得了成功，但外观模型的不准确和错误的更新导致跟踪器漂移。本文介绍了一种基于深度强化学习方法构建的模板选择策略的新型视觉跟踪算法。跟踪算法利用该策略来选择用于跟踪给定帧的最佳模板。模板选择策略是通过在从跟踪基准数据集中随机生成的众多训练集中利用简单的策略梯度方法来自学习的。我们提出的强化学习框架通常适用于其他基于信心图的跟踪算法。实验表明，我们的跟踪算法有效地决定了最佳的视觉跟踪模板。

##### URL
[https://arxiv.org/abs/1702.06291](https://arxiv.org/abs/1702.06291)

##### PDF
[https://arxiv.org/pdf/1702.06291](https://arxiv.org/pdf/1702.06291)

