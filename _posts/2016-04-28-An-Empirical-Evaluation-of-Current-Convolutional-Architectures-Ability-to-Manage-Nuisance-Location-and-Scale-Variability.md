---
layout: post
title: "An Empirical Evaluation of Current Convolutional Architectures' Ability to Manage Nuisance Location and Scale Variability"
date: 2016-04-28 05:20:40
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Nikolaos Karianakis, Jingming Dong, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We conduct an empirical study to test the ability of Convolutional Neural Networks (CNNs) to reduce the effects of nuisance transformations of the input data, such as location, scale and aspect ratio. We isolate factors by adopting a common convolutional architecture either deployed globally on the image to compute class posterior distributions, or restricted locally to compute class conditional distributions given location, scale and aspect ratios of bounding boxes determined by proposal heuristics. In theory, averaging the latter should yield inferior performance compared to proper marginalization. Yet empirical evidence suggests the converse, leading us to conclude that - at the current level of complexity of convolutional architectures and scale of the data sets used to train them - CNNs are not very effective at marginalizing nuisance variability. We also quantify the effects of context on the overall classification task and its impact on the performance of CNNs, and propose improved sampling techniques for heuristic proposal schemes that improve end-to-end performance to state-of-the-art levels. We test our hypothesis on a classification task using the ImageNet Challenge benchmark and on a wide-baseline matching task using the Oxford and Fischer's datasets.

##### Abstract (translated by Google)
我们进行实证研究，以测试卷积神经网络（CNN）的能力，以减少输入数据，如位置，规模和纵横比滋扰变换的影响。我们通过采用全局部署在图像上的共同卷积体系结构来分离因子，以计算类别后验分布，或者在本地限制计算类别条件分布，给定由提议启发法确定的边界框的位置，比例和纵横比。从理论上讲，对后者的平均处理应该比适当的边缘化效果逊色。然而，经验证据表明，相反，导致我们得出这样的结论 - 在目前的卷积架构的复杂性和用于训练它们的数据集的规模上，CNN在边缘化有害变异性方面并不是非常有效。我们还量化了上下文对整体分类任务的影响及其对CNN性能的影响，并提出了改进的启发式提案方案抽样技术，可以将端到端性能提高到最先进的水平。我们使用ImageNet挑战基准和基于牛津和费歇尔数据集的宽基线匹配任务来测试我们的假设。

##### URL
[https://arxiv.org/abs/1505.06795](https://arxiv.org/abs/1505.06795)

##### PDF
[https://arxiv.org/pdf/1505.06795](https://arxiv.org/pdf/1505.06795)

