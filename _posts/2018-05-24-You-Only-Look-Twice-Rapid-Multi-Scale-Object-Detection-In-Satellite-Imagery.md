---
layout: post
title: "You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery"
date: 2018-05-24 05:17:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection Deep_Learning Detection
author: Adam Van Etten
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of small objects in large swaths of imagery is one of the primary problems in satellite imagery analytics. While object detection in ground-based imagery has benefited from research into new deep learning approaches, transitioning such technology to overhead imagery is nontrivial. Among the challenges is the sheer number of pixels and geographic extent per image: a single DigitalGlobe satellite image encompasses &gt;64 km2 and over 250 million pixels. Another challenge is that objects of interest are minuscule (often only ~10 pixels in extent), which complicates traditional computer vision techniques. To address these issues, we propose a pipeline (You Only Look Twice, or YOLT) that evaluates satellite images of arbitrary size at a rate of &gt;0.5 km2/s. The proposed approach can rapidly detect objects of vastly different scales with relatively little training data over multiple sensors. We evaluate large test images at native resolution, and yield scores of F1 &gt; 0.8 for vehicle localization. We further explore resolution and object size requirements by systematically testing the pipeline at decreasing resolution, and conclude that objects only ~5 pixels in size can still be localized with high confidence. Code is available at https://github.com/CosmiQ/yolt.

##### Abstract (translated by Google)
在大量图像中检测小物体是卫星图像分析中的主要问题之一。虽然基于地面的图像中的物体检测已从研究新的深度学习方法中受益，但将这种技术转换为俯视图像并非易事。其中挑战之一是每个图像的像素数量和地理范围的巨大数量：单个DigitalGlobe卫星图像包含> 64平方公里和超过2.5亿像素。另一个挑战是感兴趣的对象是微不足道的（通常只有10个像素的范围），这使传统的计算机视觉技术变得复杂。为了解决这些问题，我们提出了以大于0.5km2 / s的速率评估任意大小的卫星图像的流水线（You Only Look Twice或YOLT）。所提出的方法可以通过多个传感器上相对较少的训练数据来快速检测极大地不同尺度的对象。我们以原始分辨率评估大型测试图像，并且产生F1> 0.8用于车辆定位。我们通过系统地测试降低分辨率的流水线来进一步探索解决方案和对象大小要求，并得出结论：只有〜5像素大小的对象仍然可以高置信度地进行本地化。代码位于https://github.com/CosmiQ/yolt。

##### URL
[http://arxiv.org/abs/1805.09512](http://arxiv.org/abs/1805.09512)

##### PDF
[http://arxiv.org/pdf/1805.09512](http://arxiv.org/pdf/1805.09512)

