---
layout: post
title: "In Teacher We Trust: Learning Compressed Models for Pedestrian Detection"
date: 2016-12-01 21:37:19
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Detection
author: Jonathan Shen, Noranart Vesdapunt, Vishnu N. Boddeti, Kris M. Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks continue to advance the state-of-the-art in many domains as they grow bigger and more complex. It has been observed that many of the parameters of a large network are redundant, allowing for the possibility of learning a smaller network that mimics the outputs of the large network through a process called Knowledge Distillation. We show, however, that standard Knowledge Distillation is not effective for learning small models for the task of pedestrian detection. To improve this process, we introduce a higher-dimensional hint layer to increase information flow. We also estimate the variance in the outputs of the large network and propose a loss function to incorporate this uncertainty. Finally, we attempt to boost the complexity of the small network without increasing its size by using as input hand-designed features that have been demonstrated to be effective for pedestrian detection. We succeed in training a model that contains $400\times$ fewer parameters than the large network while outperforming AlexNet on the Caltech Pedestrian Dataset.

##### Abstract (translated by Google)
深卷积神经网络在越来越大，越来越复杂的情况下继续推进许多领域的最新技术。已经观察到，大型网络的许多参数是冗余的，从而允许通过称为知识蒸馏（Knowledge Distillation）的过程来学习模拟大型网络的输出的较小网络的可能性。然而，我们表明，标准的知识蒸馏对于学习行人检测任务的小模型是无效的。为了改善这个过程，我们引入一个更高维的提示层来增加信息流。我们也估计了大型网络输出的变化，并提出了一个包含这种不确定性的损失函数。最后，我们试图通过使用已被证明对行人检测有效的输入手动设计特征来增加小网络的复杂性而不增加其尺寸。我们成功地训练了一个模型，其中包含比大型网络少$ 400 /倍的参数，同时在加州理工学院行人数据集上胜过AlexNet。

##### URL
[https://arxiv.org/abs/1612.00478](https://arxiv.org/abs/1612.00478)

##### PDF
[https://arxiv.org/pdf/1612.00478](https://arxiv.org/pdf/1612.00478)

