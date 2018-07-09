---
layout: post
title: "Optimal Sensor Data Fusion Architecture for Object Detection in Adverse Weather Conditions"
date: 2018-07-06 09:21:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Andreas Pfeuffer, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
A good and robust sensor data fusion in diverse weather conditions is a quite challenging task. There are several fusion architectures in the literature, e.g. the sensor data can be fused right at the beginning (Early Fusion), or they can be first processed separately and then concatenated later (Late Fusion). In this work, different fusion architectures are compared and evaluated by means of object detection tasks, in which the goal is to recognize and localize predefined objects in a stream of data. Usually, state-of-the-art object detectors based on neural networks are highly optimized for good weather conditions, since the well-known benchmarks only consist of sensor data recorded in optimal weather conditions. Therefore, the performance of these approaches decreases enormously or even fails in adverse weather conditions. In this work, different sensor fusion architectures are compared for good and adverse weather conditions for finding the optimal fusion architecture for diverse weather situations. A new training strategy is also introduced such that the performance of the object detector is greatly enhanced in adverse weather scenarios or if a sensor fails. Furthermore, the paper responds to the question if the detection accuracy can be increased further by providing the neural network with a-priori knowledge such as the spatial calibration of the sensors.

##### Abstract (translated by Google)
在各种天气条件下，良好而强大的传感器数据融合是一项非常具有挑战性的任文献中有几种融合架构，例如传感器数据可以在开始时融合（早期融合），也可以先分别处理，然后再连接（延迟融合）。在这项工作中，通过对象检测任务比较和评估不同的融合架构，其中目标是识别和定位数据流中的预定义对象。通常，基于神经网络的最先进的物体检测器针对良好的天气条件进行了高度优化，因为众所周知的基准仅包括在最佳天气条件下记录的传感器数据。因此，这些方法的性能在恶劣天气条件下极大地降低甚至失败。在这项工作中，针对良好和恶劣天气条件比较了不同的传感器融合架构，以便为不同的天气情况找到最佳融合架构。还引入了新的训练策略，使得在恶劣天气情况下或者如果传感器发生故障时，物体检测器的性能大大提高。此外，本文通过为神经网络提供诸如传感器的空间校准之类的先验知识，来回答是否可以进一步提高检测精度的问题。

##### URL
[http://arxiv.org/abs/1807.02323](http://arxiv.org/abs/1807.02323)

##### PDF
[http://arxiv.org/pdf/1807.02323](http://arxiv.org/pdf/1807.02323)

