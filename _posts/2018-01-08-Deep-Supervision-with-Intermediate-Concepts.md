---
layout: post
title: "Deep Supervision with Intermediate Concepts"
date: 2018-01-08 22:00:48
categories: arXiv_CV
tags: arXiv_CV GAN CNN Image_Classification Inference Classification
author: Chi Li, M. Zeeshan Zia, Quoc-Huy Tran, Xiang Yu, Gregory D.Hager, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Recent data-driven approaches to scene interpretation predominantly pose inference as an end-to-end black-box mapping, commonly performed by a Convolutional Neural Network (CNN). However, decades of work on perceptual organization in both human and machine vision suggests that there are often intermediate representations that are intrinsic to an inference task, and which provide essential structure to improve generalization. In this work, we explore an approach for injecting prior domain structure into neural network training by supervising hidden layers of a CNN with intermediate concepts that normally are not observed in practice. We formulate a probabilistic framework which formalizes these notions and predicts improved generalization via this deep supervision method. One advantage of this approach is that we are able to train only from synthetic CAD renderings of cluttered scenes, where concept values can be extracted, but apply the results to real images. Our implementation achieves the state-of-the-art performance of 2D/3D keypoint localization and image classification on real image benchmarks, including KITTI, PASCAL VOC, PASCAL3D+, IKEA, and CIFAR100. We provide additional evidence that our approach outperforms alternative forms of supervision, such as multi-task networks.

##### Abstract (translated by Google)
最近由数据驱动的场景解释方法主要将推理视为端到端的黑盒映射，通常由卷积神经网络（CNN）执行。然而，在人类和机器视觉方面数十年的感性组织工作表明，通常存在中间表示是推理任务固有的中间表示，并且提供了改进泛化的基本结构。在这项工作中，我们探索了一种方法，将先验域结构注入到神经网络训练中，通过监督CNN的隐藏层，使用通常在实践中没有观察到的中间概念。我们制定了一个概率框架，将这些概念形式化，并通过这种深度的监督方法预测改进的泛化。这种方法的一个优点是，我们只能从混杂场景的综合CAD渲染中进行训练，其中可以提取概念值，但将结果应用于实际图像。我们的实施实现了二维/三维关键点定位和图像分类的最新性能，包括KITTI，PASCAL VOC，PASCAL3D +，IKEA和CIFAR100。我们提供了额外的证据，表明我们的方法胜过了其他形式的监督，比如多任务网络。

##### URL
[https://arxiv.org/abs/1801.03399](https://arxiv.org/abs/1801.03399)

##### PDF
[https://arxiv.org/pdf/1801.03399](https://arxiv.org/pdf/1801.03399)

