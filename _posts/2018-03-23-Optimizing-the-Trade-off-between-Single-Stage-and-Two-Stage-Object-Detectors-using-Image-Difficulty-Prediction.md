---
layout: post
title: "Optimizing the Trade-off between Single-Stage and Two-Stage Object Detectors using Image Difficulty Prediction"
date: 2018-03-23 09:35:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Prediction Detection
author: Petru Soviany, Radu Tudor Ionescu
mathjax: true
---

* content
{:toc}

##### Abstract
There are mainly two types of state-of-the-art object detectors. On one hand, we have two-stage detectors, such as Faster R-CNN (Region-based Convolutional Neural Networks) or Mask R-CNN, that (i) use a Region Proposal Network to generate regions of interests in the first stage and (ii) send the region proposals down the pipeline for object classification and bounding-box regression. Such models reach the highest accuracy rates, but are typically slower. On the other hand, we have single-stage detectors, such as YOLO (You Only Look Once) and SSD (Singe Shot MultiBox Detector), that treat object detection as a simple regression problem which takes an input image and learns the class probabilities and bounding box coordinates. Such models reach lower accuracy rates, but are much faster than two-stage object detectors. In this paper, we propose to use an image difficulty predictor to achieve an optimal trade-off between accuracy and speed in object detection. The image difficulty predictor is applied on the test images to split them into easy versus hard images. Once separated, the easy images are sent to the faster single-stage detector, while the hard images are sent to the more accurate two-stage detector. Our experiments on PASCAL VOC 2007 show that using image difficulty compares favorably to a random split of the images. Our method is flexible, in that it allows to choose a desired threshold for splitting the images into easy versus hard.

##### Abstract (translated by Google)
主要有两种类型的最先进的物体探测器。一方面，我们有两阶段探测器，比如更快的R-CNN（基于区域的卷积神经网络）或Mask R-CNN，它们（i）使用区域提议网络在第一阶段产生兴趣区域， （ii）将区域提案发送到管道中以进行对象分类和边界框回归。这样的模型达到了最高的准确率，但通常较慢。另一方面，我们有YOLO（You Only Look Once）和SSD（Singe Shot MultiBox Detector）等单级探测器，将物体探测作为一个简单的回归问题，它将输入图像作为输入图像并学习类别概率，边界框坐标。这种模型的准确率较低，但比两级物体探测器快得多。在本文中，我们建议使用图像难度预测器来实现对象检测中精度和速度之间的最佳折衷。将图像难度预测器应用于测试图像，以将其分为简易图像和硬图像。一旦分离后，简单的图像将被发送到更快的单级探测器，而硬图像被发送到更精确的两级探测器。我们在PASCAL VOC 2007上进行的实验表明，使用图像难度与图像的随机分割相比毫不逊色。我们的方法是灵活的，因为它允许选择一个期望的阈值，将图像分成简单和较难。

##### URL
[https://arxiv.org/abs/1803.08707](https://arxiv.org/abs/1803.08707)

##### PDF
[https://arxiv.org/pdf/1803.08707](https://arxiv.org/pdf/1803.08707)

