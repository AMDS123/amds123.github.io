---
layout: post
title: "Supersizing Self-supervision: Learning to Grasp from 50K Tries and 700 Robot Hours"
date: 2015-09-23 02:08:02
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Lerrel Pinto, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Current learning-based robot grasping approaches exploit human-labeled datasets for training the models. However, there are two problems with such a methodology: (a) since each object can be grasped in multiple ways, manually labeling grasp locations is not a trivial task; (b) human labeling is biased by semantics. While there have been attempts to train robots using trial-and-error experiments, the amount of data used in such experiments remains substantially low and hence makes the learner prone to over-fitting. In this paper, we take the leap of increasing the available training data to 40 times more than prior work, leading to a dataset size of 50K data points collected over 700 hours of robot grasping attempts. This allows us to train a Convolutional Neural Network (CNN) for the task of predicting grasp locations without severe overfitting. In our formulation, we recast the regression problem to an 18-way binary classification over image patches. We also present a multi-stage learning approach where a CNN trained in one stage is used to collect hard negatives in subsequent stages. Our experiments clearly show the benefit of using large-scale datasets (and multi-stage training) for the task of grasping. We also compare to several baselines and show state-of-the-art performance on generalization to unseen objects for grasping.

##### Abstract (translated by Google)
当前基于学习的机器人抓取方法利用人标记的数据集来训练模型。然而，这样一种方法存在两个问题：（a）由于每个物体都可以通过多种方式进行抓取，所以手动标记抓取位置并不是一件容易的事; （二）人类的标签是偏向于语义。虽然已经试图用试错实验来训练机器人，但是在这样的实验中使用的数据量仍然很低，因此使得学习者容易过度拟合。在本文中，我们将可用训练数据增加到原来的40倍，从而导致在700多个小时的机器人抓取尝试中收集到的50K数据点的数据集大小。这使我们能够训练一个卷积神经网络（CNN）来预测抓取位置，而不会出现严重的过度拟合。在我们的表述中，我们将回归问题重新映射到图像补丁上的18路二进制分类。我们还提出了一个多阶段的学习方法，一个阶段的CNN训练用来收集后续阶段的负面情绪。我们的实验清楚地展示了使用大规模数据集（和多阶段训练）抓握任务的好处。我们还比较了几条基线，并且展示了对于看不见的物体进行概括的一般化的最新表现。

##### URL
[https://arxiv.org/abs/1509.06825](https://arxiv.org/abs/1509.06825)

##### PDF
[https://arxiv.org/pdf/1509.06825](https://arxiv.org/pdf/1509.06825)

