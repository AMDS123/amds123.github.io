---
layout: post
title: "Fast and Accurate Inference with Adaptive Ensemble Prediction in Image Classification with Deep Neural Networks"
date: 2017-02-27 12:54:54
categories: arXiv_CV
tags: arXiv_CV Image_Classification Inference Classification Prediction
author: Hiroshi Inoue
mathjax: true
---

* content
{:toc}

##### Abstract
Ensembling multiple predictions is a widely used technique to improve the accuracy of various machine learning tasks. In image classification tasks, for example, averaging the predictions for multiple patches extracted from the input image significantly improves accuracy. Using multiple networks trained independently to make predictions improves accuracy further. One obvious drawback of the ensembling technique is its higher execution cost during inference. If we average 100 predictions, the execution cost will be 100 times as high as the cost without the ensemble. This higher cost limits the real-world use of ensembling, even though using it is almost the norm to win image classification competitions. In this paper, we describe a new technique called adaptive ensemble prediction, which achieves the benefits of ensembling with much smaller additional execution costs. Our observation behind this technique is that many easy-to-predict inputs do not require ensembling. Hence we calculate the confidence level of the prediction for each input on the basis of the probability of the predicted label, i.e. the outputs from the softmax, during the ensembling computation. If the prediction for an input reaches a high enough probability on the basis of the confidence level, we stop ensembling for this input to avoid wasting computation power. We evaluated the adaptive ensembling by using various datasets and showed that it reduces the computation time significantly while achieving similar accuracy to the naive ensembling.

##### Abstract (translated by Google)
合并多个预测是提高各种机器学习任务的准确性的广泛使用的技术。在图像分类任务中，例如，对从输入图像中提取的多个补丁的预测进行平均，可以显着提高准确性。使用独立训练的多个网络进行预测可进一步提高准确性。集成技术的一个明显缺点是在推理过程中执行成本较高。如果我们平均预测100个，执行成本将是没有集合的成本的100倍。这种较高的成本限制了现实世界中的使用，即使使用它几乎是赢得图像分类比赛的常态。在本文中，我们描述了一种称为自适应集合预测的新技术，它以更小的额外执行成本实现了集成的好处。我们在这项技术背后的观察是许多易于预测的输入不需要整合。因此，我们根据预测标记的概率（即，来自softmax的输出）在整合计算期间计算每个输入的预测的置信度。如果基于置信水平对输入的预测达到足够高的概率，则停止对该输入进行整合以避免浪费计算能力。我们通过使用各种数据集来评估自适应集合，并且显示它在显着减少计算时间的同时达到与天真集合类似的精度。

##### URL
[https://arxiv.org/abs/1702.08259](https://arxiv.org/abs/1702.08259)

##### PDF
[https://arxiv.org/pdf/1702.08259](https://arxiv.org/pdf/1702.08259)

