---
layout: post
title: "Predicting Future Instance Segmentations by Forecasting Convolutional Features"
date: 2018-03-30 14:55:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Detection
author: Pauline Luc, Camille Couprie, Yann LeCun, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
Anticipating future events is an important prerequisite towards intelligent behavior. Video forecasting has been studied as a proxy task towards this goal. Recent work has shown that to predict semantic segmentation of future frames, forecasting at the semantic level is more effective than forecasting RGB frames and then segmenting these. In this paper we consider the more challenging problem of future instance segmentation, which additionally segments out individual objects. To deal with a varying number of output labels per image, we develop a predictive model in the space of fixed-sized convolutional features of the Mask R-CNN instance segmentation model. We apply the "detection head" of Mask R-CNN on the predicted features to produce the instance segmentation of future frames. Experiments show that this approach significantly improves over baselines based on optical flow.

##### Abstract (translated by Google)
预测未来事件是实现智能行为的重要先决条件。视频预测已被研究作为实现这一目标的代理任务。最近的研究表明，为了预测未来帧的语义分割，预测语义级别比预测RGB帧更有效，然后对这些帧进行分段。在本文中，我们考虑未来实例分割中更具挑战性的问题，它将细分出单独的对象。为了处理每个图像的不同数量的输出标签，我们在Mask R-CNN实例分割模型的固定大小的卷积特征的空间中开发了预测模型。我们将Mask R-CNN的“检测头”应用于预测特征，以产生未来帧的实例分割。实验表明，这种方法明显改善了基于光流的基线。

##### URL
[https://arxiv.org/abs/1803.11496](https://arxiv.org/abs/1803.11496)

##### PDF
[https://arxiv.org/pdf/1803.11496](https://arxiv.org/pdf/1803.11496)

