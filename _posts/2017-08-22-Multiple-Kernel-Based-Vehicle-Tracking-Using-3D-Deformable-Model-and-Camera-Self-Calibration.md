---
layout: post
title: "Multiple-Kernel Based Vehicle Tracking Using 3D Deformable Model and Camera Self-Calibration"
date: 2017-08-22 21:41:11
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Tracking Classification Detection
author: Zheng Tang, Gaoang Wang, Tao Liu, Young-Gun Lee, Adwin Jahn, Xu Liu, Xiaodong He, Jenq-Neng Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking of multiple objects is an important application in AI City geared towards solving salient problems related to safety and congestion in an urban environment. Frequent occlusion in traffic surveillance has been a major problem in this research field. In this challenge, we propose a model-based vehicle localization method, which builds a kernel at each patch of the 3D deformable vehicle model and associates them with constraints in 3D space. The proposed method utilizes shape fitness evaluation besides color information to track vehicle objects robustly and efficiently. To build 3D car models in a fully unsupervised manner, we also implement evolutionary camera self-calibration from tracking of walking humans to automatically compute camera parameters. Additionally, the segmented foreground masks which are crucial to 3D modeling and camera self-calibration are adaptively refined by multiple-kernel feedback from tracking. For object detection/classification, the state-of-the-art single shot multibox detector (SSD) is adopted to train and test on the NVIDIA AI City Dataset. To improve the accuracy on categories with only few objects, like bus, bicycle and motorcycle, we also employ the pretrained model from YOLO9000 with multi-scale testing. We combine the results from SSD and YOLO9000 based on ensemble learning. Experiments show that our proposed tracking system outperforms both state-of-the-art of tracking by segmentation and tracking by detection.

##### Abstract (translated by Google)
跟踪多个对象是AI市的一个重要应用，旨在解决城市环境中与安全和拥堵有关的突出问题。交通监控中频繁的堵塞一直是这个研究领域的主要问题。在这个挑战中，我们提出了一种基于模型的车辆定位方法，它在3D变形车辆模型的每个补丁上建立一个内核，并将它们与三维空间中的约束联系起来。所提出的方法利用形状适应性评估，除了颜色信息之外，还可以有效地跟踪车辆物体。为了以完全无监督的方式建立3D车模，我们还实施从步行人的跟踪进化摄像机自动校准以自动计算摄像机参数。另外，对三维建模和摄像机自标定至关重要的分段前景蒙板，由多核跟踪反馈进行自适应细化。对于物体检测/分类，采用最先进的单发多盒探测器（SSD）对NVIDIA AI City Dataset进行训练和测试。为了提高公交车，自行车，摩托车等少数物体的分类精度，我们还采用了YOLO9000的预训模型进行多尺度测试。我们结合SSD和YOLO9000基于集成学习的结果。实验表明，我们提出的跟踪系统胜过了最先进的跟踪分割和跟踪检测。

##### URL
[https://arxiv.org/abs/1708.06831](https://arxiv.org/abs/1708.06831)

##### PDF
[https://arxiv.org/pdf/1708.06831](https://arxiv.org/pdf/1708.06831)

