---
layout: post
title: "CPlaNet: Enhancing Image Geolocalization by Combinatorial Partitioning of Maps"
date: 2018-08-06 21:47:11
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Paul Hongsuck Seo, Tobias Weyand, Jack Sim, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
Image geolocalization is the task of identifying the location depicted in a photo based only on its visual information. This task is inherently challenging since many photos have only few, possibly ambiguous cues to their geolocation. Recent work has cast this task as a classification problem by partitioning the earth into a set of discrete cells that correspond to geographic regions. The granularity of this partitioning presents a critical trade-off; using fewer but larger cells results in lower location accuracy while using more but smaller cells reduces the number of training examples per class and increases model size, making the model prone to overfitting. To tackle this issue, we propose a simple but effective algorithm, combinatorial partitioning, which generates a large number of fine-grained output classes by intersecting multiple coarse-grained partitionings of the earth. Each classifier votes for the fine-grained classes that overlap with their respective coarse-grained ones. This technique allows us to predict locations at a fine scale while maintaining sufficient training examples per class. Our algorithm achieves the state-of-the-art performance in location recognition on multiple benchmark datasets.

##### Abstract (translated by Google)
图像地理定位是仅基于其视觉信息识别照片中描绘的位置的任务。这项任务本质上具有挑战性，因为许多照片只有很少，可能含糊不清的地理定位。最近的工作通过将地球划分为一组与地理区域相对应的离散单元，将此任务作为分类问题。这种分区的粒度是一个关键的权衡;使用更少但更大的单元导致更低的定位精度，而使用更多但更小的单元减少了每个类的训练示例的数量并增加了模型尺寸，使得模型易于过度拟合。为了解决这个问题，我们提出了一种简单但有效的算法 - 组合分区，它通过交叉地球的多个粗粒度分区来生成大量细粒度输出类。每个分类器都会对与其粗粒度分级重叠的细粒度类进行投票。这种技术允许我们以精细的比例预测位置，同时保持每个级别足够的训练样例。我们的算法在多个基准数据集上实现了位置识别方面的最先进性能。

##### URL
[http://arxiv.org/abs/1808.02130](http://arxiv.org/abs/1808.02130)

##### PDF
[http://arxiv.org/pdf/1808.02130](http://arxiv.org/pdf/1808.02130)

