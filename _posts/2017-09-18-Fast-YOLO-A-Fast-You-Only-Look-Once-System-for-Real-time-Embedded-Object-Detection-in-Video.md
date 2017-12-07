---
layout: post
title: "Fast YOLO: A Fast You Only Look Once System for Real-time Embedded Object Detection in Video"
date: 2017-09-18 13:57:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Classification Detection
author: Mohammad Javad Shafiee, Brendan Chywl, Francis Li, Alexander Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is considered one of the most challenging problems in this field of computer vision, as it involves the combination of object classification and object localization within a scene. Recently, deep neural networks (DNNs) have been demonstrated to achieve superior object detection performance compared to other approaches, with YOLOv2 (an improved You Only Look Once model) being one of the state-of-the-art in DNN-based object detection methods in terms of both speed and accuracy. Although YOLOv2 can achieve real-time performance on a powerful GPU, it still remains very challenging for leveraging this approach for real-time object detection in video on embedded computing devices with limited computational power and limited memory. In this paper, we propose a new framework called Fast YOLO, a fast You Only Look Once framework which accelerates YOLOv2 to be able to perform object detection in video on embedded devices in a real-time manner. First, we leverage the evolutionary deep intelligence framework to evolve the YOLOv2 network architecture and produce an optimized architecture (referred to as O-YOLOv2 here) that has 2.8X fewer parameters with just a ~2% IOU drop. To further reduce power consumption on embedded devices while maintaining performance, a motion-adaptive inference method is introduced into the proposed Fast YOLO framework to reduce the frequency of deep inference with O-YOLOv2 based on temporal motion characteristics. Experimental results show that the proposed Fast YOLO framework can reduce the number of deep inferences by an average of 38.13%, and an average speedup of ~3.3X for objection detection in video compared to the original YOLOv2, leading Fast YOLO to run an average of ~18FPS on a Nvidia Jetson TX1 embedded system.

##### Abstract (translated by Google)
目标检测被认为是计算机视觉领域中最具挑战性的问题之一，因为它涉及场景中的目标分类和目标定位的组合。最近，与其他方法相比，深度神经网络（DNN）已经被证明可以实现优越的目标检测性能，其中YOLOv2（一种改进的只看一次的模型）是基于DNN的目标检测中的最新技术之一方法的速度和准确性。虽然YOLOv2能够在强大的GPU上实现实时性能，但是利用这种方法在嵌入式计算设备上的视频实时对象检测方面仍然非常具有挑战性，而这些设备的计算能力有限且内存有限。在本文中，我们提出了一个名为Fast YOLO的新框架，它是一个快速的You Only Look Once框架，可以加快YOLOv2在嵌入式设备上的视频对象的实时检测。首先，我们利用演化深度智能框架来演化YOLOv2网络架构，并产生一个优化的架构（这里称为O-YOLOv2），其参数减少了2.8倍，仅有2％的IOU下降。为了在保持性能的同时进一步降低嵌入式设备的功耗，在所提出的快速YOLO框架中引入运动自适应推理方法，以减少基于时间运动特征的O-YOLOv2的深度推理频率。实验结果表明，与原YOLOv2相比，所提出的快速YOLO框架能够平均减少38.13％的深层推理的数量，对于视频中的对象检测平均加速〜3.3X，使Fast YOLO运行平均在Nvidia Jetson TX1嵌入式系统上〜18FPS。

##### URL
[https://arxiv.org/abs/1709.05943](https://arxiv.org/abs/1709.05943)

##### PDF
[https://arxiv.org/pdf/1709.05943](https://arxiv.org/pdf/1709.05943)

