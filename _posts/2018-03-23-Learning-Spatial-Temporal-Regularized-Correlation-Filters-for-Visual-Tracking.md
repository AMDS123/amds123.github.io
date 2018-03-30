---
layout: post
title: "Learning Spatial-Temporal Regularized Correlation Filters for Visual Tracking"
date: 2018-03-23 07:55:24
categories: arXiv_CV
tags: arXiv_CV Regularization Tracking Relation
author: Feng Li, Cheng Tian, Wangmeng Zuo, Lei Zhang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative Correlation Filters (DCF) are efficient in visual tracking but suffer from unwanted boundary effects. Spatially Regularized DCF (SRDCF) has been suggested to resolve this issue by enforcing spatial penalty on DCF coefficients, which, inevitably, improves the tracking performance at the price of increasing complexity. To tackle online updating, SRDCF formulates its model on multiple training images, further adding difficulties in improving efficiency. In this work, by introducing temporal regularization to SRDCF with single sample, we present our spatial-temporal regularized correlation filters (STRCF). Motivated by online Passive-Agressive (PA) algorithm, we introduce the temporal regularization to SRDCF with single sample, thus resulting in our spatial-temporal regularized correlation filters (STRCF). The STRCF formulation can not only serve as a reasonable approximation to SRDCF with multiple training samples, but also provide a more robust appearance model than SRDCF in the case of large appearance variations. Besides, it can be efficiently solved via the alternating direction method of multipliers (ADMM). By incorporating both temporal and spatial regularization, our STRCF can handle boundary effects without much loss in efficiency and achieve superior performance over SRDCF in terms of accuracy and speed. Experiments are conducted on three benchmark datasets: OTB-2015, Temple-Color, and VOT-2016. Compared with SRDCF, STRCF with hand-crafted features provides a 5 times speedup and achieves a gain of 5.4% and 3.6% AUC score on OTB-2015 and Temple-Color, respectively. Moreover, STRCF combined with CNN features also performs favorably against state-of-the-art CNN-based trackers and achieves an AUC score of 68.3% on OTB-2015.

##### Abstract (translated by Google)
鉴别相关滤波器（DCF）在视觉追踪中是有效的，但遭受不需要的边界效应。已经提出空间正则化DCF（SRDCF）来通过对DCF系数执行空间惩罚来解决该问题，这不可避免地以复杂性增加的价格提高了跟踪性能。为了处理在线更新，SRDCF在多个训练图像上制定了模型，进一步增加了提高效率的难度。在这项工作中，通过将单个样本的时间正则化引入SRDCF，我们提出了我们的空间 - 时间正则化相关滤波器（STRCF）。受到在线被动 - 积极（PA）算法的启发，我们将时间正则化引入单样本SRDCF，从而产生我们的时空正则化相关滤波器（STRCF）。 STRCF公式不仅可以作为SRDCF与多个训练样本的合理近似，而且在外观变化大的情况下也可以提供比SRDCF更强大的外观模型。此外，它可以通过乘法器的交替方向法（ADMM）有效解决。通过结合时间和空间正则化，我们的STRCF可以处理边界效应，而不会产生太多的效率损失，并且在精确度和速度方面比SRDCF实现更好的性能。实验在三个基准数据集上进行：OTB-2015，Temple-Color和VOT-2016。与SRDCF相比，具有手工特征的STRCF提供了5倍的加速，分别在OTB-2015和Temple-Color上获得了5.4％和3.6％的AUC分数。此外，STRCF与CNN功能相结合，对于最先进的基于CNN的跟踪器也表现出色，并且在OTB-2015上获得了68.3％的AUC评分。

##### URL
[https://arxiv.org/abs/1803.08679](https://arxiv.org/abs/1803.08679)

##### PDF
[https://arxiv.org/pdf/1803.08679](https://arxiv.org/pdf/1803.08679)

