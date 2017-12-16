---
layout: post
title: "Learning Unified Embedding for Apparel Recognition"
date: 2017-08-15 13:36:30
categories: arXiv_CV
tags: arXiv_CV Embedding Recognition
author: Yang Song, Yuan Li, Bo Wu, Chao-Yeh Chen, Xiao Zhang, Hartwig Adam
mathjax: true
---

* content
{:toc}

##### Abstract
In apparel recognition, specialized models (e.g. models trained for a particular vertical like dresses) can significantly outperform general models (i.e. models that cover a wide range of verticals). Therefore, deep neural network models are often trained separately for different verticals. However, using specialized models for different verticals is not scalable and expensive to deploy. This paper addresses the problem of learning one unified embedding model for multiple object verticals (e.g. all apparel classes) without sacrificing accuracy. The problem is tackled from two aspects: training data and training difficulty. On the training data aspect, we figure out that for a single model trained with triplet loss, there is an accuracy sweet spot in terms of how many verticals are trained together. To ease the training difficulty, a novel learning scheme is proposed by using the output from specialized models as learning targets so that L2 loss can be used instead of triplet loss. This new loss makes the training easier and make it possible for more efficient use of the feature space. The end result is a unified model which can achieve the same retrieval accuracy as a number of separate specialized models, while having the model complexity as one. The effectiveness of our approach is shown in experiments.

##### Abstract (translated by Google)
在服装识别中，专门模型（例如针对像服装这样的特定垂直所训练的模型）可以明显优于一般模型（即覆盖广泛垂直线的模型）。因此，深度神经网络模型通常分别针对不同的垂直方向进行训练。但是，针对不同的垂直行业使用专门的模型不具有可扩展性，而且部署成本高昂。本文解决了在不牺牲准确性的情况下学习多个对象垂直（例如所有服装类）的统一嵌入模型的问题。这个问题从培训数据和培训难度两个方面来处理。在训练数据方面，我们发现，对于训练有三重失误的单个模型，在有多少垂直线训练在一起时，有一个准确的最佳位置。为了减轻训练难度，提出了一种新的学习方案，以专门模型的输出作为学习目标，使用L2损失代替三重损失。这种新的损失使训练变得更容易，并使得更有效地使用特征空间成为可能。最终的结果是一个统一的模型，可以达到与一些单独的专业模型相同的检索精度，同时具有模型复杂性。我们的方法的有效性在实验中显示。

##### URL
[https://arxiv.org/abs/1707.05929](https://arxiv.org/abs/1707.05929)

##### PDF
[https://arxiv.org/pdf/1707.05929](https://arxiv.org/pdf/1707.05929)

