---
layout: post
title: "The Effects of Super-Resolution on Object Detection Performance in Satellite Imagery"
date: 2019-04-09 16:58:39
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Object_Detection Detection
author: Jacob Shermeyer, Adam Van Etten
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the application of super-resolution techniques to satellite imagery, and the effects of these techniques on object detection algorithm performance. Specifically, we enhance satellite imagery beyond its native resolution, and test if we can identify various types of vehicles, planes, and boats with greater accuracy than native resolution. Using the Very Deep Super-Resolution (VDSR) framework and a custom Random Forest Super-Resolution (RFSR) framework we generate enhancement levels of 2x, 4x, and 8x over five distinct resolutions ranging from 30 cm to 4.8 meters. Using both native and super-resolved data, we then train several custom detection models using the SIMRDWN object detection framework. SIMRDWN combines a number of popular object detection algorithms (e.g. SSD, YOLO) into a unified framework that is designed to rapidly detect objects in large satellite images. This approach allows us to quantify the effects of super-resolution techniques on object detection performance across multiple classes and resolutions. We also quantify the performance of object detection as a function of native resolution and object pixel size. For our test set we note that performance degrades from mean average precision (mAP) = 0.53 at 30 cm resolution, down to mAP = 0.11 at 4.8 m resolution. Super-resolving native 30 cm imagery to 15 cm yields the greatest benefit; a 13-36% improvement in mAP. Super-resolution is less beneficial at coarser resolutions, though still provides a small improvement in performance.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.04098](https://arxiv.org/abs/1812.04098)

##### PDF
[https://arxiv.org/pdf/1812.04098](https://arxiv.org/pdf/1812.04098)

