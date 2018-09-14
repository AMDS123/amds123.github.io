---
layout: post
title: "Quantization Mimic: Towards Very Tiny CNN for Object Detection"
date: 2018-09-13 09:03:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Face Detection
author: Yi Wei, Xinyu Pan, Hongwei Qin, Wanli Ouyang, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a simple and general framework for training very tiny CNNs for object detection. Due to limited representation ability, it is challenging to train very tiny networks for complicated tasks like detection. To the best of our knowledge, our method, called Quantization Mimic, is the first one focusing on very tiny networks. We utilize two types of acceleration methods: mimic and quantization. Mimic improves the performance of a student network by transfering knowledge from a teacher network. Quantization converts a full-precision network to a quantized one without large degradation of performance. If the teacher network is quantized, the search scope of the student network will be smaller. Using this feature of the quantization, we propose Quantization Mimic. It first quantizes the large network, then mimic a quantized small network. The quantization operation can help student network to better match the feature maps from teacher network. To evaluate our approach, we carry out experiments on various popular CNNs including VGG and Resnet, as well as different detection frameworks including Faster R-CNN and R-FCN. Experiments on Pascal VOC and WIDER FACE verify that our Quantization Mimic algorithm can be applied on various settings and outperforms state-of-the-art model acceleration methods given limited computing resouces.

##### Abstract (translated by Google)
在本文中，我们提出了一个简单而通用的框架，用于训练非常小的CNN用于对象检测。由于表示能力有限，为检测等复杂任务训练非常小的网络具有挑战性。据我们所知，我们的方法称为Quantization Mimic，是第一个专注于非常小的网络的方法。我们使用两种类型的加速方法：模仿和量化。 Mimic通过从教师网络传输知识来提高学生网络的性能。量化将全精度网络转换为量化网络，而不会降低性能。如果教师网络被量化，则学生网络的搜索范围将更小。使用量化的这个特征，我们提出量化模拟。它首先量化大型网络，然后模拟量化的小型网络。量化操作可以帮助学生网络更好地匹配教师网络中的特征地图。为了评估我们的方法，我们在各种流行的CNN（包括VGG和Resnet）以及不同的检测框架（包括更快的R-CNN和R-FCN）上进行实验。 Pascal VOC和WIDER FACE上的实验验证了我们的量化模拟算法可以应用于各种设置，并且在给定有限计算资源的情况下优于最先进的模型加速方法。

##### URL
[http://arxiv.org/abs/1805.02152](http://arxiv.org/abs/1805.02152)

##### PDF
[http://arxiv.org/pdf/1805.02152](http://arxiv.org/pdf/1805.02152)

