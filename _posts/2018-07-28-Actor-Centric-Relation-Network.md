---
layout: post
title: "Actor-Centric Relation Network"
date: 2018-07-28 22:48:27
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Classification Detection Relation
author: Chen Sun, Abhinav Shrivastava, Carl Vondrick, Kevin Murphy, Rahul Sukthankar, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art approaches for spatio-temporal action localization rely on detections at the frame level and model temporal context with 3D ConvNets. Here, we go one step further and model spatio-temporal relations to capture the interactions between human actors, relevant objects and scene elements essential to differentiate similar human actions. Our approach is weakly supervised and mines the relevant elements automatically with an actor-centric relational network (ACRN). ACRN computes and accumulates pair-wise relation information from actor and global scene features, and generates relation features for action classification. It is implemented as neural networks and can be trained jointly with an existing action detection system. We show that ACRN outperforms alternative approaches which capture relation information, and that the proposed framework improves upon the state-of-the-art performance on JHMDB and AVA. A visualization of the learned relation features confirms that our approach is able to attend to the relevant relations for each action.

##### Abstract (translated by Google)
用于时空动作定位的当前最先进的方法依赖于帧级别的检测和具有3D ConvNets的模型时间上下文。在这里，我们更进一步，模拟时空关系，以捕捉人类演员，相关对象和场景元素之间的相互作用，这对于区分类似的人类行为至关重要。我们的方法是弱监督的，并且以演员为中心的关系网络（ACRN）自动挖掘相关元素。 ACRN计算并累积来自演员和全局场景特征的成对关系信息，并生成用于动作分类的关系特征。它作为神经网络实现，并且可以与现有的动作检测系统联合训练。我们表明ACRN优于捕获关系信息的替代方法，并且所提出的框架改进了JHMDB和AVA的最新性能。学习关系特征的可视化证实了我们的方法能够处理每个动作的相关关系。

##### URL
[http://arxiv.org/abs/1807.10982](http://arxiv.org/abs/1807.10982)

##### PDF
[http://arxiv.org/pdf/1807.10982](http://arxiv.org/pdf/1807.10982)

