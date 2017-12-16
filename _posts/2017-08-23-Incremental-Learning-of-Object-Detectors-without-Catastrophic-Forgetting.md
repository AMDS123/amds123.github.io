---
layout: post
title: "Incremental Learning of Object Detectors without Catastrophic Forgetting"
date: 2017-08-23 12:33:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Prediction Detection
author: Konstantin Shmelkov, Cordelia Schmid, Karteek Alahari
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their success for object detection, convolutional neural networks are ill-equipped for incremental learning, i.e., adapting the original model trained on a set of classes to additionally detect objects of new classes, in the absence of the initial training data. They suffer from "catastrophic forgetting" - an abrupt degradation of performance on the original set of classes, when the training objective is adapted to the new classes. We present a method to address this issue, and learn object detectors incrementally, when neither the original training data nor annotations for the original classes in the new training set are available. The core of our proposed solution is a loss function to balance the interplay between predictions on the new classes and a new distillation loss which minimizes the discrepancy between responses for old classes from the original and the updated networks. This incremental learning can be performed multiple times, for a new set of classes in each step, with a moderate drop in performance compared to the baseline network trained on the ensemble of data. We present object detection results on the PASCAL VOC 2007 and COCO datasets, along with a detailed empirical analysis of the approach.

##### Abstract (translated by Google)
尽管卷积神经网络在物体检测方面取得了成功，但是对于增量学习来说，卷积神经网络是不适合的，即，在没有初始训练数据的情况下，使在一组类上训练的原始模型适应新的类别对象。他们遭受了“灾难性的遗忘” - 当训练目标适应新的阶级时，原始阶级的表现突然退化。我们提出了一种解决这个问题的方法，并且在原始训练数据和新训练集中的原始类别的注释都不可用的情况下递增地学习对象检测器。我们提出的解决方案的核心是平衡新类别预测与新蒸馏损失之间相互作用的损失函数，从而使旧类别对原始网络和更新网络的响应之间的差异最小化。这种增量学习可以多次执行，对于每个步骤中的一组新的类别，与在数据集合上训练的基线网络相比，性能有中等下降。我们在PASCAL VOC 2007和COCO数据集上提供了对象检测结果，并对方法进行了详细的实证分析。

##### URL
[https://arxiv.org/abs/1708.06977](https://arxiv.org/abs/1708.06977)

##### PDF
[https://arxiv.org/pdf/1708.06977](https://arxiv.org/pdf/1708.06977)

