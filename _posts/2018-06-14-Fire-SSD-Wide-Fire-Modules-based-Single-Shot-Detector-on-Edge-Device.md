---
layout: post
title: "Fire SSD: Wide Fire Modules based Single Shot Detector on Edge Device"
date: 2018-06-14 04:56:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Hengfui Liau, Nimmagadda Yamini, YengLiong Wong
mathjax: true
---

* content
{:toc}

##### Abstract
With the emergence of edge computing, there is an increasing need for running convolutional neural network based object detection on small form factor edge computing devices with limited compute and thermal budget for applications such as video surveillance. To address this problem, efficient object detection frameworks such as YOLO and SSD were proposed. However, SSD based object detection that uses VGG16 as backend network is insufficient to achieve real time speed on edge devices. To further improve the detection speed, the backend network is replaced by more efficient networks such as SqueezeNet and MobileNet. Although the speed is greatly improved, it comes with a price of lower accuracy. In this paper, we propose an efficient SSD named Fire SSD. Fire SSD achieves 70.7mAP on Pascal VOC 2007 test set. Fire SSD achieves the speed of 30.6FPS on low power mainstream CPU and is about 6 times faster than SSD300 and has about 4 times smaller model size. Fire SSD also achieves 22.2FPS on integrated GPU.

##### Abstract (translated by Google)
随着边缘计算的出现，越来越需要运行基于卷积神经网络的小型边缘计算设备上的物体检测，而计算和热预算有限，适用于视频监控等应用。为了解决这个问题，提出了有效的对象检测框架，如YOLO和SSD。但是，使用VGG16作为后端网络的基于SSD的对象检测不足以在边缘设备上实现实时速度。为了进一步提高检测速度，后端网络被更高效的网络取代，如SqueezeNet和MobileNet。虽然速度大大提高，但它的准确性较低。在本文中，我们提出了一种名为Fire SSD的高效SSD。 Fire SSD在Pascal VOC 2007测试装置上达到70.7mAP。 Fire SSD在低功耗主流CPU上的速度达到30.6FPS，比SSD300快6倍，并且尺寸缩小了约4倍。集成GPU上的Fire SSD也达到了22.2FPS。

##### URL
[http://arxiv.org/abs/1806.05363](http://arxiv.org/abs/1806.05363)

##### PDF
[http://arxiv.org/pdf/1806.05363](http://arxiv.org/pdf/1806.05363)

