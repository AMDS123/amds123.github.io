---
layout: post
title: "Change Detection under Global Viewpoint Uncertainty"
date: 2017-03-01 23:51:03
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Murase Tomoya, Tanaka Kanji
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of change detection from a novel perspective of long-term map learning. We are particularly interested in designing an approach that can scale to large maps and that can function under global uncertainty in the viewpoint (i.e., GPS-denied situations). Our approach, which utilizes a compact bag-of-words (BoW) scene model, makes several contributions to the problem: 1) Two kinds of prior information are extracted from the view sequence map and used for change detection. Further, we propose a novel type of prior, called motion prior, to predict the relative motions of stationary objects and anomaly ego-motion detection. The proposed prior is also useful for distinguishing stationary from non-stationary objects. 2) A small set of good reference images (e.g., 10) are efficiently retrieved from the view sequence map by employing the recently developed Bag-of-Local-Convolutional-Features (BoLCF) scene model. 3) Change detection is reformulated as a scene retrieval over these reference images to find changed objects using a novel spatial Bag-of-Words (SBoW) scene model. Evaluations conducted of individual techniques and also their combinations on a challenging dataset of highly dynamic scenes in the publicly available Malaga dataset verify their efficacy.

##### Abstract (translated by Google)
本文从长期地图学习的新视角，探讨了变化检测问题。我们特别感兴趣的是设计一种可以扩展到大型地图的方法，并且可以在全球不确定性（即GPS拒绝情况）下运行。我们的方法利用了一个紧凑的文字袋（BoW）场景模型，对这个问题做出了一些贡献：1）从视图序列图中提取两种先验信息用于变化检测。此外，我们提出了一种新型的先前称为运动优先的预测静止物体的相对运动和异常自我运动检测。所提出的先验对于区分静止物体和非静止物体也是有用的。 2）通过采用最近开发的本地卷积特征（BoLCF）场景模型从视图序列图中有效地检索一小组好的参考图像（例如，10）。 3）变化检测被重新形成为这些参考图像上的场景检索，以使用新颖的空间Bag-of-Words（SBoW）场景模型来找到变化的对象。在公开发布的马拉加数据集中，对具有挑战性的高度动态场景的数据集进行单独技术的评估以及它们的组合，以验证其效力。

##### URL
[https://arxiv.org/abs/1703.00552](https://arxiv.org/abs/1703.00552)

##### PDF
[https://arxiv.org/pdf/1703.00552](https://arxiv.org/pdf/1703.00552)

