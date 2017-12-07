---
layout: post
title: "R-FCN-3000 at 30fps: Decoupling Detection and Classification"
date: 2017-12-05 18:30:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Bharat Singh, Hengduo Li, Abhishek Sharma, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
We present R-FCN-3000, a large-scale real-time object detector in which objectness detection and classification are decoupled. To obtain the detection score for an RoI, we multiply the objectness score with the fine-grained classification score. Our approach is a modification of the R-FCN architecture in which position-sensitive filters are shared across different object classes for performing localization. For fine-grained classification, these position-sensitive filters are not needed. R-FCN-3000 obtains an mAP of 34.9% on the ImageNet detection dataset and outperforms YOLO-9000 by 18% while processing 30 images per second. We also show that the objectness learned by R-FCN-3000 generalizes to novel classes and the performance increases with the number of training object classes - supporting the hypothesis that it is possible to learn a universal objectness detector. Code will be made available.

##### Abstract (translated by Google)
我们提出了R-FCN-3000，一个大规模的实时对象检测器，其中的对象检测和分类是解耦的。为了获得RoI的检测分数，我们将对象分数乘以细粒度的分类分数。我们的方法是对R-FCN体系结构的修改，其中位置敏感滤波器在不同的对象类之间共享以执行本地化。对于细粒度的分类，这些位置敏感的滤波器是不需要的。 R-FCN-3000在ImageNet检测数据集上获得34.9％的mAP，在每秒处理30幅图像的同时，胜过YOLO-900018％。我们还展示了R-FCN-3000学习的对象被推广到新的类，并且性能随着训练对象类的数量增加而增加 - 支持可以学习通用对象检测器的假设。代码将被提供。

##### URL
[https://arxiv.org/abs/1712.01802](https://arxiv.org/abs/1712.01802)

##### PDF
[https://arxiv.org/pdf/1712.01802](https://arxiv.org/pdf/1712.01802)

