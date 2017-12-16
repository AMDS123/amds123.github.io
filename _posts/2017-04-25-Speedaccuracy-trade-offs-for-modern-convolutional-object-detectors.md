---
layout: post
title: "Speed/accuracy trade-offs for modern convolutional object detectors"
date: 2017-04-25 03:42:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Jonathan Huang, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer, Zbigniew Wojna, Yang Song, Sergio Guadarrama, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to serve as a guide for selecting a detection architecture that achieves the right speed/memory/accuracy balance for a given application and platform. To this end, we investigate various ways to trade accuracy for speed and memory usage in modern convolutional object detection systems. A number of successful systems have been proposed in recent years, but apples-to-apples comparisons are difficult due to different base feature extractors (e.g., VGG, Residual Networks), different default image resolutions, as well as different hardware and software platforms. We present a unified implementation of the Faster R-CNN [Ren et al., 2015], R-FCN [Dai et al., 2016] and SSD [Liu et al., 2015] systems, which we view as "meta-architectures" and trace out the speed/accuracy trade-off curve created by using alternative feature extractors and varying other critical parameters such as image size within each of these meta-architectures. On one extreme end of this spectrum where speed and memory are critical, we present a detector that achieves real time speeds and can be deployed on a mobile device. On the opposite end in which accuracy is critical, we present a detector that achieves state-of-the-art performance measured on the COCO detection task.

##### Abstract (translated by Google)
本文的目标是作为选择一个检测架构的指南，为给定的应用和平台实现适当的速度/内存/精度平衡。为此，我们研究了在现代卷积目标检测系统中交换速度和内存使用的准确性的各种方法。近年来已经提出了许多成功的系统，但是由于不同的基本特征提取器（例如VGG，剩余网络），不同的默认图像分辨率以及不同的硬件和软件平台，所以苹果对苹果的比较是困难的。我们提出了R-CNN更快的R-CNN [Ren等，2015]，R-FCN [Dai等，2016]和SSD [Liu等，2015]系统的统一实现，体系结构“，并追踪使用替代特征提取器创建的速度/精度折衷曲线，并在这些元架构中改变其他关键参数（如图像大小）。在速度和内存至关重要的这个频谱的一个极端，我们提出了一个实现实时速度的检测器，可以部署在移动设备上。在精确度至关重要的另一端，我们提供了一个检测器，可以实现在COCO检测任务上测量的最先进的性能。

##### URL
[https://arxiv.org/abs/1611.10012](https://arxiv.org/abs/1611.10012)

##### PDF
[https://arxiv.org/pdf/1611.10012](https://arxiv.org/pdf/1611.10012)

