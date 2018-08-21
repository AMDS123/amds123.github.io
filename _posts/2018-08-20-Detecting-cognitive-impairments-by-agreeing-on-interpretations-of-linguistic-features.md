---
layout: post
title: "Detecting cognitive impairments by agreeing on interpretations of linguistic features"
date: 2018-08-20 17:05:46
categories: arXiv_AI
tags: arXiv_AI Detection
author: Zining Zhu, Jekaterina Novikova, Frank Rudzicz
mathjax: true
---

* content
{:toc}

##### Abstract
Linguistic features have shown promising applications for detecting various cognitive impairments. To improve detection accuracies, increasing the amount of data or linguistic features have been two applicable approaches. However, acquiring additional clinical data could be expensive, and hand-carving features are burdensome. In this paper, we take a third approach, putting forward Consensus Networks (CN), a framework to diagnose after reaching agreements between modalities. We divide the linguistic features into non-overlapping subsets according to their natural categories, let neural networks ("ePhysicians") learn low-dimensional representations ("interpretation vectors") that agree with each other. These representations are passed into a neural network classifier, resulting in a framework for assessing cognitive impairments. In this paper, we also present methods that empirically improve the performance of CN. Namely, the addition of a noise modality and allowing gradients to propagate to interpreters while optimizing the classifier. We then present two ablation studies to illustrate the effectiveness of CN: dividing subsets in the natural modalities is more beneficial than doing so randomly, and that models built with consensus settings outperform those without given the same modalities of features. To understand further what happens in consensus networks, we visualize the interpretation vectors during training procedures. They demonstrate symmetry in an aggregate manner. Overall, using all of the 413 linguistic features, our models significantly outperform traditional classifiers, which are used by the state-of-the-art papers.

##### Abstract (translated by Google)
语言特征已经显示出用于检测各种认知障碍的有希望的应用。为了提高检测精度，增加数据量或语言特征是两种适用的方法。然而，获取额外的临床数据可能是昂贵的，并且手工雕刻特征是繁重的。在本文中，我们采取第三种方法，提出共识网络（CN），这是一种在达成模式之间的协议后进行诊断的框架。我们根据它们的自然类别将语言特征划分为非重叠子集，让神经网络（“ePhysicians”）学习彼此一致的低维表示（“解释向量”）。这些表示被传递到神经网络分类器中，从而形成用于评估认知障碍的框架。在本文中，我们还提出了经验上改善CN性能的方法。即，添加噪声模态并允许渐变在优化分类器的同时传播到解释器。然后，我们提出两个消融研究来说明CN的有效性：在自然模态中划分子集比随机执行更有利，并且使用共识设置建立的模型优于那些没有给出相同模态特征的模型。为了进一步了解共识网络中发生的情况，我们在训练过程中可视化解释向量。它们以聚合方式表现出对称性。总的来说，使用所有413种语言特征，我们的模型明显优于传统分类器，这些分类器被最先进的论文所使用。

##### URL
[http://arxiv.org/abs/1808.06570](http://arxiv.org/abs/1808.06570)

##### PDF
[http://arxiv.org/pdf/1808.06570](http://arxiv.org/pdf/1808.06570)

