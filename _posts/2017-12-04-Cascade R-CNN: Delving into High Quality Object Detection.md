---
layout: post
title:  'Cascade R-CNN: Delving into High Quality Object Detection'
date:   2017-12-05 18:44:29
categories: CV
tags: CV
author: Zhaowei Cai, Nuno Vasconcelos
---

* content
{:toc}

##### Abstract
In object detection, an intersection over union (IoU) threshold is required to define positives and negatives. An object detector, trained with low IoU threshold, e.g. 0.5, usually produces noisy detections. However, detection performance tends to degrade with increasing the IoU thresholds. Two main factors are responsible for this: 1) overfitting during training, due to exponentially vanishing positive samples, and 2) inference-time mismatch between the IoUs for which the detector is optimal and those of the input hypotheses. A multi-stage object detection architecture, the Cascade R-CNN, is proposed to address these problems. It consists of a sequence of detectors trained with increasing IoU thresholds, to be sequentially more selective against close false positives. The detectors are trained stage by stage, leveraging the observation that the output of a detector is a good distribution for training the next higher quality detector. The resampling of progressively improved hypotheses guarantees that all detectors have a positive set of examples of equivalent size, reducing the overfitting problem. The same cascade procedure is applied at inference, enabling a closer match between the hypotheses and the detector quality of each stage. A simple implementation of the Cascade R-CNN is shown to surpass all single-model object detectors on the challenging COCO dataset. Experiments also show that the Cascade R-CNN is widely applicable across detector architectures, achieving consistent gains independently of the baseline detector strength. The code will be made available at https://github.com/zhaoweicai/cascade-rcnn.

##### Abstract (translated by Google)
在对象检测中，需要通过联合（IoU）阈值的交集来定义肯定和否定。用低IoU阈值进行训练的目标检测器，例如， 0.5，通常会产生嘈杂的检测结果。但是，随着IoU阈值的提高，检测性能会降低。造成这种情况的主要因素有两个：1）由于指数消失的正样本，训练过度拟合; 2）检测器最优的输入假设与输入假设的输入假设之间的推理时间不匹配。为了解决这些问题，提出了多级对象检测体系结构Cascade R-CNN。它由一系列随着IoU阈值增加而训练的检测器组成，依次对接近的假阳性有更多的选择性。探测器是逐步培训的，利用了探测器的输出是一个良好的分布，以培养下一个更高质量的探测器的观察。对不断改进的假设进行重采样可以保证所有检测器都有一组正确的等效大小的例子，减少了过度拟合的问题。在推理中应用相同的级联过程，使得各个阶段的假设与检测器质量之间更接近匹配。示出了级联R-CNN的简单实现超过具有挑战性的COCO数据集上的所有单模式对象检测器。实验还表明，级联R-CNN可广泛应用于各种检测器架构，获得与基线检测器强度无关的一致增益。代码将在https://github.com/zhaoweicai/cascade-rcnn上提供。

