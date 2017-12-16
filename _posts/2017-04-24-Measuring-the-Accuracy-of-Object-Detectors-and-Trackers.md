---
layout: post
title: "Measuring the Accuracy of Object Detectors and Trackers"
date: 2017-04-24 15:41:35
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Object_Tracking Detection
author: Tobias Bottger, Patrick Follmann, Michael Fauser
mathjax: true
---

* content
{:toc}

##### Abstract
The accuracy of object detectors and trackers is most commonly evaluated by the Intersection over Union (IoU) criterion. To date, most approaches are restricted to axis-aligned or oriented boxes and, as a consequence, many datasets are only labeled with boxes. Nevertheless, axis-aligned or oriented boxes cannot accurately capture an object's shape. To address this, a number of densely segmented datasets has started to emerge in both the object detection and the object tracking communities. However, evaluating the accuracy of object detectors and trackers that are restricted to boxes on densely segmented data is not straightforward. To close this gap, we introduce the relative Intersection over Union (rIoU) accuracy measure. The measure normalizes the IoU with the optimal box for the segmentation to generate an accuracy measure that ranges between 0 and 1 and allows a more precise measurement of accuracies. Furthermore, it enables an efficient and easy way to understand scenes and the strengths and weaknesses of an object detection or tracking approach. We display how the new measure can be efficiently calculated and present an easy-to-use evaluation framework. The framework is tested on the DAVIS and the VOT2016 segmentations and has been made available to the community.

##### Abstract (translated by Google)
目标检测器和跟踪器的精度通常由联合交叉（IoU）标准评估。迄今为止，大多数方法仅限于轴对齐或定向的框，因此，许多数据集仅用框标记。尽管如此，轴对齐或定向框不能准确地捕捉对象的形状。为了解决这个问题，一些密集分割的数据集已经开始出现在对象检测和对象跟踪社区中。然而，评估被限制在密集分段数据上的盒子的物体检测器和跟踪器的准确性并不是直截了当的。为了弥补这个差距，我们介绍了相对交汇（rIoU）准确性测量。该测量使用用于分割的最佳框对IoU进行归一化，以生成范围在0和1之间的准确性度量，并且允许对精度进行更精确的测量。此外，它能够以高效和简单的方式了解场景以及对象检测或跟踪方法的优缺点。我们展示了如何有效地计算新的度量，并提出一个易于使用的评估框架。该框架在DAVIS和VOT2016分段上进行了测试，并已提供给社区。

##### URL
[https://arxiv.org/abs/1704.07293](https://arxiv.org/abs/1704.07293)

##### PDF
[https://arxiv.org/pdf/1704.07293](https://arxiv.org/pdf/1704.07293)

