---
layout: post
title: 'FSSD: Feature Fusion Single Shot Multibox Detector'
date: 2017-12-05 21:10:17
categories: arXiv_CV
[arXiv_CV,Object Detection,Detection]
author: Zuoxin Li, Fuqiang Zhou
---

* content
{:toc}

##### Abstract
SSD (Single Shot Multibox Detetor) is one of the best object detection algorithms with both high accuracy and fast speed. However, SSD's feature pyramid detection method makes it hard to fuse the features from different scales. In this paper, we proposed FSSD (Feature Fusion Single Shot Multibox Detector), an enhanced SSD with a novel and lightweight feature fusion module which can improve the performance significantly over SSD with just a little speed drop. In the feature fusion module, features from different layers with different scales are concatenated together, followed by some down-sampling blocks to generate new feature pyramid, which will be fed to multibox detectors to predict the final detection results. On the Pascal VOC 2007 test, our network can achieve 82.7 mAP (mean average precision) at the speed of 65.8 FPS (frame per second) with the input size 300$\times$300 using a single Nvidia 1080Ti GPU. In addition, our result on COCO is also better than the conventional SSD with a large margin. Our FSSD outperforms a lot of state-of-the-art object detection algorithms in both aspects of accuracy and speed. Code will be made publicly available.

##### Abstract (translated by Google)
SSD（Single Shot Multibox Detector）是高精度，高速度的最佳物体检测算法之一。然而，SSD的特征金字塔检测方法使得难以融合不同尺度的特征。在本文中，我们提出了FSSD（特征融合单发多盒检测器），这种增强型SSD具有新颖轻便的特征融合模块，只需稍微降低速度，就可以显着提高SSD的性能。在特征融合模块中，将不同尺度的不同层次的特征串联在一起，然后进行一些下采样块生成新的特征金字塔，将其馈送到多盒检测器，以预测最终的检测结果。在Pascal VOC 2007测试中，我们的网络可以以65.8 FPS（帧/秒）的速度达到82.7 mAP（平均精确度），使用单个Nvidia 1080Ti GPU，输入尺寸为300 $ \ times $ 300。另外，我们在COCO上的成绩也比传统的SSD有了很大的提升。我们的FSSD在准确性和速度方面胜过了许多最新的对象检测算法。代码将被公开。

##### URL
[http://arxiv.org/abs/1712.00960](http://arxiv.org/abs/1712.00960)

