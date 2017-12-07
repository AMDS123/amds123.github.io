---
layout: post
title: "UnitBox: An Advanced Object Detection Network"
date: 2016-08-04 09:06:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face_Detection CNN Detection
author: Jiahui Yu, Yuning Jiang, Zhangyang Wang, Zhimin Cao, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In present object detection systems, the deep convolutional neural networks (CNNs) are utilized to predict bounding boxes of object candidates, and have gained performance advantages over the traditional region proposal methods. However, existing deep CNN methods assume the object bounds to be four independent variables, which could be regressed by the $\ell_2$ loss separately. Such an oversimplified assumption is contrary to the well-received observation, that those variables are correlated, resulting to less accurate localization. To address the issue, we firstly introduce a novel Intersection over Union ($IoU$) loss function for bounding box prediction, which regresses the four bounds of a predicted box as a whole unit. By taking the advantages of $IoU$ loss and deep fully convolutional networks, the UnitBox is introduced, which performs accurate and efficient localization, shows robust to objects of varied shapes and scales, and converges fast. We apply UnitBox on face detection task and achieve the best performance among all published methods on the FDDB benchmark.

##### Abstract (translated by Google)
在目前的对象检测系统中，利用深度卷积神经网络（CNNs）来预测候选对象的边界框，并且与传统的区域提议方法相比具有性能优势。然而，现有的深度CNN方法假定对象边界是四个独立变量，可以分别用$ \ ell_2 $损失进行回归。这种过于简单的假设与广为接受的观察相反，即这些变量是相关的，导致定位不准确。为了解决这个问题，我们首先引入了一种新的交叉口联合（$ IoU $）损失函数来实现边界框预测，这个函数将预测框的四个边界作为一个整体进行回归。通过利用$ IoU $ loss和深度完全卷积网络的优势，UnitBox被引入，它执行准确和高效的定位，对各种形状和尺度的物体显示出鲁棒性，并且快速收敛。我们将UnitBox应用于人脸检测任务，并在FDDB基准测试的所有已发布方法中实现最佳性能。

##### URL
[https://arxiv.org/abs/1608.01471](https://arxiv.org/abs/1608.01471)

##### PDF
[https://arxiv.org/pdf/1608.01471](https://arxiv.org/pdf/1608.01471)

