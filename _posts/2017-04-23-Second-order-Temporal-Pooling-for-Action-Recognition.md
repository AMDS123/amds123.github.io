---
layout: post
title: "Second-order Temporal Pooling for Action Recognition"
date: 2017-04-23 14:10:55
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Embedding Deep_Learning Prediction Relation Recognition
author: Anoop Cherian, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Most successful deep learning models for action recognition generate predictions for short video clips, which are later aggregated into a longer time-frame action descriptor by computing a statistic over these predictions. Zeroth (max) or first order (average) statistic are commonly used. In this paper, we explore the benefits of using second-order statistics. Specifically, we propose a novel end-to-end learnable action pooling scheme, temporal correlation pooling, that generates an action descriptor for a video sequence by capturing the similarities between the temporal evolution of per-frame CNN features across the video. Such a descriptor, while being computationally cheap, also naturally encodes the co-activations of multiple CNN features, thereby providing a richer characterization of actions than their first-order counterparts. We also propose higher-order extensions of this scheme by computing correlations after embedding the CNN features in a reproducing kernel Hilbert space. We provide experiments on four standard and fine-grained action recognition datasets. Our results clearly demonstrate the advantages of higher-order pooling schemes, achieving state-of-the-art performance.

##### Abstract (translated by Google)
大多数成功的动作识别深度学习模型可以对短视频剪辑进行预测，然后通过计算这些预测的统计数据，将其聚合为更长的时间帧动作描述符。通常使用第零（最大）或一阶（平均）统计量。在本文中，我们探讨使用二阶统计量的好处。具体而言，我们提出了一种新颖的端到端可学习行动池方案，即时间相关性池，通过捕获视频中每帧CNN特征的时间演进之间的相似性来生成视频序列的行动描述符。这种描述符尽管在计算上便宜，但也自然地编码了多个CNN特征的共同激活，从而提供比其一阶对应物更丰富的动作表征。在CNN特征嵌入再生核希尔伯特空间之后，我们也通过计算相关性来提出这个方案的高阶扩展。我们提供了四个标准和细粒度动作识别数据集的实验。我们的研究结果清楚地表明了高阶汇集方案的优点，实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1704.06925](https://arxiv.org/abs/1704.06925)

##### PDF
[https://arxiv.org/pdf/1704.06925](https://arxiv.org/pdf/1704.06925)

