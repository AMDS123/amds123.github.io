---
layout: post
title: "A 58.6mW Real-Time Programmable Object Detector with Multi-Scale Multi-Object Support Using Deformable Parts Model on 1920x1080 Video at 30fps"
date: 2016-07-27 19:20:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Amr Suleiman, Zhengdong Zhang, Vivienne Sze
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a programmable, energy-efficient and real-time object detection accelerator using deformable parts models (DPM), with 2x higher accuracy than traditional rigid body models. With 8 deformable parts detection, three methods are used to address the high computational complexity: classification pruning for 33x fewer parts classification, vector quantization for 15x memory size reduction, and feature basis projection for 2x reduction of the cost of each classification. The chip is implemented in 65nm CMOS technology, and can process HD (1920x1080) images at 30fps without any off-chip storage while consuming only 58.6mW (0.94nJ/pixel, 1168 GOPS/W). The chip has two classification engines to simultaneously detect two different classes of objects. With a tested high throughput of 60fps, the classification engines can be time multiplexed to detect even more than two object classes. It is energy scalable by changing the pruning factor or disabling the parts classification.

##### Abstract (translated by Google)
本文提出了一种使用可变形零件模型（DPM）的可编程，高能效和实时的物体检测加速器，其精度比传统的刚体模型高2倍。采用8个可变形零件检测，使用三种方法来解决高计算复杂性：分类修剪，减少33倍的零件分类，减少15倍的存储器尺寸的矢量量化，以及减少每个分类成本两倍的特征基准投影。该芯片采用65纳米CMOS技术，能够以30fps的速度处理HD（1920x1080）图像，而无需任何片外存储，而仅消耗58.6mW（0.94nJ /像素，1168 GOPS / W）。该芯片有两个分类引擎来同时检测两个不同类别的对象。经过测试的60fps的高吞吐量，分类引擎可以被时分复用以检测甚至两个以上的对象类别。通过改变修剪因子或禁用零件分类可以扩展能量。

##### URL
[https://arxiv.org/abs/1607.08635](https://arxiv.org/abs/1607.08635)

##### PDF
[https://arxiv.org/pdf/1607.08635](https://arxiv.org/pdf/1607.08635)

