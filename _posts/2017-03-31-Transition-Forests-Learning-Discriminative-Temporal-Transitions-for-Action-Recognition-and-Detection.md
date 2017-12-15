---
layout: post
title: "Transition Forests: Learning Discriminative Temporal Transitions for Action Recognition and Detection"
date: 2017-03-31 15:39:45
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Prediction Detection Relation Recognition
author: Guillermo Garcia-Hernando, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
A human action can be seen as transitions between one's body poses over time, where the transition depicts a temporal relation between two poses. Recognizing actions thus involves learning a classifier sensitive to these pose transitions as well as to static poses. In this paper, we introduce a novel method called transitions forests, an ensemble of decision trees that both learn to discriminate static poses and transitions between pairs of two independent frames. During training, node splitting is driven by alternating two criteria: the standard classification objective that maximizes the discrimination power in individual frames, and the proposed one in pairwise frame transitions. Growing the trees tends to group frames that have similar associated transitions and share same action label incorporating temporal information that was not available otherwise. Unlike conventional decision trees where the best split in a node is determined independently of other nodes, the transition forests try to find the best split of nodes jointly (within a layer) for incorporating distant node transitions. When inferring the class label of a new frame, it is passed down the trees and the prediction is made based on previous frame predictions and the current one in an efficient and online manner. We apply our method on varied skeleton action recognition and online detection datasets showing its suitability over several baselines and state-of-the-art approaches.

##### Abstract (translated by Google)
一个人的行为可以被看作是一个人的身体姿势随着时间的过渡，这个过渡描述了两个姿势之间的时间关系。因此，识别动作包括学习一个对这些姿态转换以及静态姿态敏感的分类器。在本文中，我们介绍了一种叫做转换森林的新方法，这是一个决策树的集合，它们都学习区分静态姿态和两对独立帧之间的转换。在训练过程中，节点分裂由交替的两个标准驱动：最大化各个帧中的区分能力的标准分类目标，以及在成对帧过渡中提出的标准分类目标。越来越多的树倾向于将具有相似关联转换的帧分组，并且共享包含其他情况下不可用的时间信息的相同动作标签。不同于传统的决策树，其中节点中的最佳分裂是独立于其他节点而确定的，所以过渡森林试图联合（层内）找到最佳的节点分裂，以便结合远处的节点转换。当推断新帧的类别标签时，将其传递到树上，并且基于之前的帧预测和当前帧预测以高效且在线的方式进行预测。我们将我们的方法应用于各种骨骼动作识别和在线检测数据集，以显示其在几个基线和最先进的方法中的适用性。

##### URL
[https://arxiv.org/abs/1607.02737](https://arxiv.org/abs/1607.02737)

##### PDF
[https://arxiv.org/pdf/1607.02737](https://arxiv.org/pdf/1607.02737)

