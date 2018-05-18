---
layout: post
title: "Learning Strict Identity Mappings in Deep Residual Networks"
date: 2018-05-16 20:03:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Optimization Detection Recognition
author: Xin Yu, Zhiding Yu, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
A family of super deep networks, referred to as residual networks or ResNet, achieved record-beating performance in various visual tasks such as image recognition, object detection, and semantic segmentation. The ability to train very deep networks naturally pushed the researchers to use enormous resources to achieve the best performance. Consequently, in many applications super deep residual networks were employed for just a marginal improvement in performance. In this paper, we propose epsilon-ResNet that allows us to automatically discard redundant layers, which produces responses that are smaller than a threshold epsilon, with a marginal or no loss in performance. The epsilon-ResNet architecture can be achieved using a few additional rectified linear units in the original ResNet. Our method does not use any additional variables nor numerous trials like other hyper-parameter optimization techniques. The layer selection is achieved using a single training process and the evaluation is performed on CIFAR-10, CIFAR-100, SVHN, and ImageNet datasets. In some instances, we achieve about 80% reduction in the number of parameters.

##### Abstract (translated by Google)
称为残余网络或ResNet的超深网络系列在诸如图像识别，对象检测和语义分割等各种视觉任务中取得了创纪录的表现。培养非常深的网络的能力自然推动研究人员使用巨大的资源来实现最佳性能。因此，在许多应用中，超深度残余网络仅用于性能的边际改进。在本文中，我们提出了epsilon-ResNet，它允许我们自动丢弃冗余层，这会产生小于阈值ε的响应，并且性能边际或无损。在ResNet中使用一些额外的整流线性单元可以实现epsilon-ResNet架构。我们的方法不像其他超参数优化技术那样使用任何附加变量或许多试验。使用单一训练过程实现图层选择，并在CIFAR-10，CIFAR-100，SVHN和ImageNet数据集上执行评估。在某些情况下，我们实现了大约80％的参数减少。

##### URL
[http://arxiv.org/abs/1804.01661](http://arxiv.org/abs/1804.01661)

##### PDF
[http://arxiv.org/pdf/1804.01661](http://arxiv.org/pdf/1804.01661)

