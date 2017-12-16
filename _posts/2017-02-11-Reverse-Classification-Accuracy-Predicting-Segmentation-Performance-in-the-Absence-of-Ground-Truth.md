---
layout: post
title: "Reverse Classification Accuracy: Predicting Segmentation Performance in the Absence of Ground Truth"
date: 2017-02-11 10:16:34
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Classification
author: Vanya V. Valindria, Ioannis Lavdas, Wenjia Bai, Konstantinos Kamnitsas, Eric O. Aboagye, Andrea G. Rockall, Daniel Rueckert, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
When integrating computational tools such as automatic segmentation into clinical practice, it is of utmost importance to be able to assess the level of accuracy on new data, and in particular, to detect when an automatic method fails. However, this is difficult to achieve due to absence of ground truth. Segmentation accuracy on clinical data might be different from what is found through cross-validation because validation data is often used during incremental method development, which can lead to overfitting and unrealistic performance expectations. Before deployment, performance is quantified using different metrics, for which the predicted segmentation is compared to a reference segmentation, often obtained manually by an expert. But little is known about the real performance after deployment when a reference is unavailable. In this paper, we introduce the concept of reverse classification accuracy (RCA) as a framework for predicting the performance of a segmentation method on new data. In RCA we take the predicted segmentation from a new image to train a reverse classifier which is evaluated on a set of reference images with available ground truth. The hypothesis is that if the predicted segmentation is of good quality, then the reverse classifier will perform well on at least some of the reference images. We validate our approach on multi-organ segmentation with different classifiers and segmentation methods. Our results indicate that it is indeed possible to predict the quality of individual segmentations, in the absence of ground truth. Thus, RCA is ideal for integration into automatic processing pipelines in clinical routine and as part of large-scale image analysis studies.

##### Abstract (translated by Google)
在将诸如自动分割等计算工具整合到临床实践中时，能够评估新数据的准确性水平，特别是检测自动方法何时失败，是至关重要的。但由于缺乏事实根据，难以实现。临床数据的分割准确性可能与通过交叉验证发现的不同，因为验证数据通常用于增量方法开发，这可能导致过度拟合和不现实的性能预期。在部署之前，使用不同的度量来量化性能，为此将预测的分割与参考分割进行比较，通常由专家手动获得。但是当参考不可用时，对部署后的真实性能知之甚少。在本文中，我们引入反分类准确性（RCA）的概念作为预测新数据分割方法性能的框架。在RCA中，我们从新图像中预测分割，以训练一个反向分类器，该分类器在一组具有可用的基本事实的参考图像上进行评估。该假设是，如果预测的分割具有良好的质量，则反向分类器将在至少一些参考图像上表现良好。我们用不同的分类器和分割方法来验证我们的多器官分割方法。我们的结果表明，在没有基础事实的情况下，确实可以预测单个分割的质量。因此，RCA是临床常规自动处理流水线的理想选择，也是大规模图像分析研究的一部分。

##### URL
[https://arxiv.org/abs/1702.03407](https://arxiv.org/abs/1702.03407)

##### PDF
[https://arxiv.org/pdf/1702.03407](https://arxiv.org/pdf/1702.03407)

