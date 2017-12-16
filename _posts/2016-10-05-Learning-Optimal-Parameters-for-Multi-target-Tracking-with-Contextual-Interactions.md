---
layout: post
title: "Learning Optimal Parameters for Multi-target Tracking with Contextual Interactions"
date: 2016-10-05 13:04:48
categories: arXiv_CV
tags: arXiv_CV Tracking Prediction
author: Shaofei Wang, Charless C. Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an end-to-end framework for learning parameters of min-cost flow multi-target tracking problem with quadratic trajectory interactions including suppression of overlapping tracks and contextual cues about cooccurrence of different objects. Our approach utilizes structured prediction with a tracking-specific loss function to learn the complete set of model parameters. In this learning framework, we evaluate two different approaches to finding an optimal set of tracks under a quadratic model objective, one based on an LP relaxation and the other based on novel greedy variants of dynamic programming that handle pairwise interactions. We find the greedy algorithms achieve almost equivalent accuracy to the LP relaxation while being up to 10x faster than a commercial LP solver. We evaluate trained models on three challenging benchmarks. Surprisingly, we find that with proper parameter learning, our simple data association model without explicit appearance/motion reasoning is able to achieve comparable or better accuracy than many state-of-the-art methods that use far more complex motion features or appearance affinity metric learning.

##### Abstract (translated by Google)
我们描述了一个端到端的框架，用于学习最小成本流多目标跟踪问题的参数，二次轨迹交互包括抑制重叠轨道和关于不同对象共同发生的上下文线索。我们的方法利用具有跟踪特定损失函数的结构化预测来学习整套模型参数。在这个学习框架中，我们评估了两种不同的方法来寻找一个二次模型目标下的最佳轨道集，一个基于LP松弛，另一个基于处理配对相互作用的动态规划的新型贪婪变体。我们发现贪婪算法达到几乎相当于LP松弛的精度，而比商业LP解算器快10倍。我们评估三个具有挑战性的基准训练模型。令人惊讶的是，我们发现，通过适当的参数学习，没有显式外观/运动推理的简单数据关联模型能够实现比许多使用更复杂的运动特征或外观关联性度量的现有技术方法更好的准确性学习。

##### URL
[https://arxiv.org/abs/1610.01394](https://arxiv.org/abs/1610.01394)

##### PDF
[https://arxiv.org/pdf/1610.01394](https://arxiv.org/pdf/1610.01394)

