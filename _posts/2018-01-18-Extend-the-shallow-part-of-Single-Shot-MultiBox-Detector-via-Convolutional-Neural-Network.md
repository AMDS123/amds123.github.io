---
layout: post
title: "Extend the shallow part of Single Shot MultiBox Detector via Convolutional Neural Network"
date: 2018-01-18 03:03:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Liwen Zheng, Canmiao Fu, Yong Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Single Shot MultiBox Detector (SSD) is one of the fastest algorithms in the current object detection field, which uses fully convolutional neural network to detect all scaled objects in an image. Deconvolutional Single Shot Detector (DSSD) is an approach which introduces more context information by adding the deconvolution module to SSD. And the mean Average Precision (mAP) of DSSD on PASCAL VOC2007 is improved from SSD's 77.5% to 78.6%. Although DSSD obtains higher mAP than SSD by 1.1%, the frames per second (FPS) decreases from 46 to 11.8. In this paper, we propose a single stage end-to-end image detection model called ESSD to overcome this dilemma. Our solution to this problem is to cleverly extend better context information for the shallow layers of the best single stage (e.g. SSD) detectors. Experimental results show that our model can reach 79.4% mAP, which is higher than DSSD and SSD by 0.8 and 1.9 points respectively. Meanwhile, our testing speed is 25 FPS in Titan X GPU which is more than double the original DSSD.

##### Abstract (translated by Google)
单镜头MultiBox检测器（SSD）是当前目标检测领域中最快的算法之一，它使用完全卷积神经网络来检测图像中的所有缩放对象。解卷积单探测器（DSSD）是一种通过将解卷积模块添加到SSD来引入更多上下文信息的方法。 DASD在PASCAL VOC2007上的平均精度（mAP）由SSD的77.5％提高到78.6％。虽然DSSD获得的SSD比SSD高1.1％，但每秒帧数（FPS）从46降低到11.8。在本文中，我们提出一种称为ESSD的单阶段端到端图像检测模型来克服这个困境。我们对这个问题的解决方案是巧妙地为最好的单级（如SSD）探测器的浅层提供更好的背景信息。实验结果表明，我们的模型可以达到79.4％的mAP，比DSSD和SSD分别高出0.8和1.9分。同时，我们的Titan X GPU的测试速度是25 FPS，比原来的DSSD高出一倍以上。

##### URL
[http://arxiv.org/abs/1801.05918](http://arxiv.org/abs/1801.05918)

##### PDF
[http://arxiv.org/pdf/1801.05918](http://arxiv.org/pdf/1801.05918)

