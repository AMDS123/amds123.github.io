---
layout: post
title: "Tiny SSD: A Tiny Single-shot Detection Deep Convolutional Neural Network for Real-time Embedded Object Detection"
date: 2018-02-19 01:57:46
categories: arXiv_AI
tags: arXiv_AI Object_Detection CNN Classification Detection
author: Alexander Wong, Mohammad Javad Shafiee, Francis Li, Brendan Chwyl
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection is a major challenge in computer vision, involving both object classification and object localization within a scene. While deep neural networks have been shown in recent years to yield very powerful techniques for tackling the challenge of object detection, one of the biggest challenges with enabling such object detection networks for widespread deployment on embedded devices is high computational and memory requirements. Recently, there has been an increasing focus in exploring small deep neural network architectures for object detection that are more suitable for embedded devices, such as Tiny YOLO and SqueezeDet. Inspired by the efficiency of the Fire microarchitecture introduced in SqueezeNet and the object detection performance of the single-shot detection macroarchitecture introduced in SSD, this paper introduces Tiny SSD, a single-shot detection deep convolutional neural network for real-time embedded object detection that is composed of a highly optimized, non-uniform Fire sub-network stack and a non-uniform sub-network stack of highly optimized SSD-based auxiliary convolutional feature layers designed specifically to minimize model size while maintaining object detection performance. The resulting Tiny SSD possess a model size of 2.3MB (~26X smaller than Tiny YOLO) while still achieving an mAP of 61.3% on VOC 2007 (~4.2% higher than Tiny YOLO). These experimental results show that very small deep neural network architectures can be designed for real-time object detection that are well-suited for embedded scenarios.

##### Abstract (translated by Google)
对象检测是计算机视觉领域的主要挑战，涉及场景中的对象分类和对象本地化。尽管近年来深度神经网络已经证明能够产生非常强大的技术来应对物体检测的挑战，但是使这种对象检测网络能够广泛部署在嵌入式设备上面临的最大挑战之一是高度计算和内存要求。最近，越来越多的人关注探索更适合嵌入式设备的小型深度神经网络体系结构，如Tiny YOLO和SqueezeDet。受SqueezeNet中引入的Fire微体系结构的效率以及SSD中引入的单发检测宏体系结构的目标检测性能的启发，本文引入了Tiny SSD--一种用于实时嵌入式目标检测的单次检测深卷积神经网络，由高度优化的非均匀火灾子网络堆栈和由高度优化的基于SSD的辅助卷积特征层构成的非统一子网络堆栈组成，专门设计用于最小化模型大小，同时保持对象检测性能。由此产生的Tiny SSD拥有2.3MB（比Tiny YOLO小约26倍）的模型尺寸，同时在VOC 2007上仍然达到61.3％的mAP（比Tiny YOLO高约4.2％）。这些实验结果表明，非常小的深度神经网络架构可以设计用于非常适合嵌入式场景的实时对象检测。

##### URL
[http://arxiv.org/abs/1802.06488](http://arxiv.org/abs/1802.06488)

##### PDF
[http://arxiv.org/pdf/1802.06488](http://arxiv.org/pdf/1802.06488)

