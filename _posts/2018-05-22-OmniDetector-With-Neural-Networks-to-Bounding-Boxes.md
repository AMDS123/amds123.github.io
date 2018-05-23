---
layout: post
title: "OmniDetector: With Neural Networks to Bounding Boxes"
date: 2018-05-22 11:14:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Roman Seidel, André Apitzsch, Gangolf Hirtz
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a person detector on omnidirectional images, an accurate method to generate minimal enclosing rectangles of persons. The basic idea is to adapt the qualitative detection performance of a convolutional neural network based method, namely YOLOv2 to fish-eye images. The design of our approach picks up the idea of a state-of-the-art object detector and highly overlapping areas of images with their regions of interests. This overlap reduces the number of false negatives. Based on the raw bounding boxes of the detector we fine-tuned overlapping bounding boxes by three approaches. The non-maximum suppression, the soft non-maximum suppression and the soft non-maximum suppression with Gaussian smoothing. The evaluation was done on the PIROPO database, supplemented with bounding boxes on omnidirectional images. We achieve an average precision of 64.4 % with YOLOv2 for the class person. For this purpose we fine-tuned the soft non-maximum suppression with Gaussian smoothing.

##### Abstract (translated by Google)
我们提出了一个全方位图像人检测器，一种精确的方法来生成最小的包围矩形的人。其基本思想是将基于卷积神经网络的方法即YOLOv2的定性检测性能适应于鱼眼图像。我们方法的设计体现了最先进的物体探测器和高度重叠的图像区域及其感兴趣的区域。这种重叠减少了漏报的次数。基于检测器的原始边界框，我们通过三种方法对重叠的边界框进行了微调。采用高斯平滑的非最大抑制，非最大抑制和软非最大抑制。评估是在PIROPO数据库上完成的，并在全方位图像上添加了边界框。我们使用YOLOv2为班级人员实现了64.4％的平均精确度。为此，我们用高斯平滑来微调软非最大抑制。

##### URL
[https://arxiv.org/abs/1805.08503](https://arxiv.org/abs/1805.08503)

##### PDF
[https://arxiv.org/pdf/1805.08503](https://arxiv.org/pdf/1805.08503)

