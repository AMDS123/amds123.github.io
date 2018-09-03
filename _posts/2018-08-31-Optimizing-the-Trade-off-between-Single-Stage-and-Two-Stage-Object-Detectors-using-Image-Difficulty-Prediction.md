---
layout: post
title: "Optimizing the Trade-off between Single-Stage and Two-Stage Object Detectors using Image Difficulty Prediction"
date: 2018-08-31 13:13:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Prediction Detection
author: Petru Soviany, Radu Tudor Ionescu
mathjax: true
---

* content
{:toc}

##### Abstract
There are mainly two types of state-of-the-art object detectors. On one hand, we have two-stage detectors, such as Faster R-CNN (Region-based Convolutional Neural Networks) or Mask R-CNN, that (i) use a Region Proposal Network to generate regions of interests in the first stage and (ii) send the region proposals down the pipeline for object classification and bounding-box regression. Such models reach the highest accuracy rates, but are typically slower. On the other hand, we have single-stage detectors, such as YOLO (You Only Look Once) and SSD (Singe Shot MultiBox Detector), that treat object detection as a simple regression problem by taking an input image and learning the class probabilities and bounding box coordinates. Such models reach lower accuracy rates, but are much faster than two-stage object detectors. In this paper, we propose to use an image difficulty predictor to achieve an optimal trade-off between accuracy and speed in object detection. The image difficulty predictor is applied on the test images to split them into easy versus hard images. Once separated, the easy images are sent to the faster single-stage detector, while the hard images are sent to the more accurate two-stage detector. Our experiments on PASCAL VOC 2007 show that using image difficulty compares favorably to a random split of the images. Our method is flexible, in that it allows to choose a desired threshold for splitting the images into easy versus hard.

##### Abstract (translated by Google)
主要有两种类型的现有技术物体探测器。一方面，我们有两级探测器，如更快的R-CNN（基于区域的卷积神经网络）或掩模R-CNN，它们（i）使用区域提议网络在第一阶段生成感兴趣的区域， （ii）将区域提案发送到管道中以进行对象分类和边界框回归。这些模型达到最高准确率，但通常较慢。另一方面，我们有单级探测器，例如YOLO（You Only Look Once）和SSD（Singe Shot MultiBox Detector），它通过获取输入图像和学习类概率来将对象检测视为一个简单的回归问题。边界框坐标。这种模型的准确率较低，但比两级物体探测器快得多。在本文中，我们建议使用图像难度预测器来实现对象检测中的准确度和速度之间的最佳权衡。将图像难度预测器应用于测试图像以将它们分成易与硬图像。分离后，将简单的图像发送到更快的单级检测器，同时将硬图像发送到更准确的两级检测器。我们对PASCAL VOC 2007的实验表明，使用图像难度与图像的随机分割相比是有利的。我们的方法是灵活的，因为它允许选择所需的阈值以将图像分成易与硬。

##### URL
[http://arxiv.org/abs/1803.08707](http://arxiv.org/abs/1803.08707)

##### PDF
[http://arxiv.org/pdf/1803.08707](http://arxiv.org/pdf/1803.08707)

