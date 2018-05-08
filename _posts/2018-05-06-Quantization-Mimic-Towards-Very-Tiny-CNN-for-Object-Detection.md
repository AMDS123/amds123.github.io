---
layout: post
title: "Quantization Mimic: Towards Very Tiny CNN for Object Detection"
date: 2018-05-06 05:36:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Detection
author: Yi Wei, Xinyu Pan, Hongwei Qin, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple and general framework for training very tiny CNNs for object detection. Due to limited representation ability, it is challenging to train very tiny networks for complicated tasks like detection. To the best of our knowledge, our method, called Quantization Mimic, is the first one focusing on very tiny networks. We utilize two types of acceleration methods: mimic and quantization. Mimic improves the performance of a student network by transfering knowledge from a teacher network. Quantization converts a full-precision network to a quantized one without large degradation of performance. If the teacher network is quantized, the search scope of the student network will be smaller. Using this property of quantization, we propose Quantization Mimic. It first quantizes the large network, then mimic a quantized small network. We suggest the operation of quantization can help student network to match the feature maps from teacher network. To evaluate the generalization of our hypothesis, we carry out experiments on various popular CNNs including VGG and Resnet, as well as different detection frameworks including Faster R-CNN and R-FCN. Experiments on Pascal VOC and WIDER FACE verify our Quantization Mimic algorithm can be applied on various settings and outperforms state-of-the-art model acceleration methods given limited computing resouces.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单而通用的框架来训练非常微小的CNN用于物体检测。由于代表能力有限，培训非常小的网络以应对复杂的任务（如检测）非常具有挑战性。就我们所知，我们称之为量化模仿的方法是第一个专注于非常小的网络的方法。我们使用两种类型的加速方法：模拟和量化。 Mimic通过从教师网络转移知识来提高学生网络的表现。量化将全精度网络转换为量化的网络，而不会导致性能的大幅降低。如果教师网络被量化，学生网络的搜索范围将会变小。使用这种量化特性，我们提出量化模拟。它首先量化大型网络，然后模仿量化的小型网络。我们建议量化操作可以帮助学生网络匹配教师网络中的特征地图。为了评估我们的假设的概括性，我们对包括VGG和Resnet在内的各种流行的CNN进行了实验，以及不同的检测框架，包括更快的R-CNN和R-FCN。对Pascal VOC和WIDER FACE的实验验证了我们的量化模拟算法可应用于各种设置，并在给定有限计算资源的情况下优于最先进的模型加速方法。

##### URL
[http://arxiv.org/abs/1805.02152](http://arxiv.org/abs/1805.02152)

##### PDF
[http://arxiv.org/pdf/1805.02152](http://arxiv.org/pdf/1805.02152)

