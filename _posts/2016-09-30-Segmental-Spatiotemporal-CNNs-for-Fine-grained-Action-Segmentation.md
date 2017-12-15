---
layout: post
title: "Segmental Spatiotemporal CNNs for Fine-grained Action Segmentation"
date: 2016-09-30 15:08:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Action_Recognition CNN Inference Classification Relation Recognition
author: Colin Lea, Austin Reiter, Rene Vidal, Gregory D. Hager
mathjax: true
---

* content
{:toc}

##### Abstract
Joint segmentation and classification of fine-grained actions is important for applications of human-robot interaction, video surveillance, and human skill evaluation. However, despite substantial recent progress in large-scale action classification, the performance of state-of-the-art fine-grained action recognition approaches remains low. We propose a model for action segmentation which combines low-level spatiotemporal features with a high-level segmental classifier. Our spatiotemporal CNN is comprised of a spatial component that uses convolutional filters to capture information about objects and their relationships, and a temporal component that uses large 1D convolutional filters to capture information about how object relationships change across time. These features are used in tandem with a semi-Markov model that models transitions from one action to another. We introduce an efficient constrained segmental inference algorithm for this model that is orders of magnitude faster than the current approach. We highlight the effectiveness of our Segmental Spatiotemporal CNN on cooking and surgical action datasets for which we observe substantially improved performance relative to recent baseline methods.

##### Abstract (translated by Google)
细粒度行为的联合分割和分类对于人机交互，视频监控和人才技能评估等应用具有重要意义。然而，尽管在大规模行动分类方面取得了实质性的进展，但是最先进的细粒度行动识别方法的表现仍然很低。我们提出了一个动作分割的模型，它将低层次的时空特征与高层次的分块分类器相结合。我们的时空CNN包含一个空间组件，它使用卷积过滤器来捕获关于对象及其关系的信息，以及一个使用大型一维卷积过滤器捕获关于对象关系随时间变化的信息的时间组件。这些特征与半马尔可夫模型一起使用，模型从一个动作转换到另一个动作。我们为这个模型引入一个有效的约束分段推理算法，比当前的方法快几个数量级。我们强调了我们的节段性时空CNN对于烹饪和手术动作数据集的有效性，相对于最近的基线方法，我们观察到其性能显着改善。

##### URL
[https://arxiv.org/abs/1602.02995](https://arxiv.org/abs/1602.02995)

##### PDF
[https://arxiv.org/pdf/1602.02995](https://arxiv.org/pdf/1602.02995)

