---
layout: post
title: "Detection, localisation and tracking of pallets using machine learning techniques and 2D range data"
date: 2018-03-29 21:00:56
categories: arXiv_RO
tags: arXiv_RO Object_Detection Tracking CNN Detection
author: Ihab S. Mohamed, Alessio Capitanelli, Fulvio Mastrogiovanni, Stefano Rovetta, Renato Zaccaria
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of autonomous transportation in industrial scenarios is receiving a renewed interest due to the way it can revolutionise internal logistics, especially in unstructured environments. This paper presents a novel architecture allowing a robot to detect, localise, and track multiple pallets using machine learning techniques based on an on-board 2D laser rangefinder. The architecture is composed of two main components: the first stage is a pallet detector employing a Faster Region-based Convolutional Neural Network (Faster R-CNN) detector cascaded with a CNN-based classifier; the second stage is a Kalman filter for localising and tracking detected pallets, which we also use to defer commitment to a pallet detected in the first step until sufficient confidence has been acquired via a sequential data acquisition process. For fine-tuning the CNNs, the architecture has been systematically evaluated using a real-world dataset containing 340 labeled 2D scans, which have been made freely available in an online repository. Detection performance has been assessed on the basis of the average accuracy over k-fold cross-validation, and it scored 99.58% in our tests. Concerning pallet localisation and tracking, experiments have been performed in a scenario where the robot is approaching the pallet to fork. Although data have been originally acquired by considering only one pallet, artificial data have been generated as well to mimic the presence of multiple targets in the robot workspace. Our experimental results confirm that the system is capable of identifying, localising and tracking pallets with a high success rate while being robust to false positives.

##### Abstract (translated by Google)
工业情景中的自动运输问题正在引起人们的兴趣，因为它可能会改革内部物流，特别是在非结构化环境中。本文介绍了一种新型架构，允许机器人使用基于机载2D激光测距仪的机器学习技术来检测，定位和跟踪多个托盘。该体系结构由两个主要部分组成：第一阶段是采用与基于CNN的分类器级联的基于快速区域的卷积神经网络（Faster R-CNN）检测器的托盘检测器;第二阶段是用于定位和跟踪检测到的托盘的卡尔曼滤波器，我们还用它来推迟对第一步中检测到的托盘的承诺，直到通过顺序数据采集过程获得足够的置信度。为了微调CNN，已经使用包含340个标记的2D扫描的真实世界数据集系统地评估了该架构，已经在线存储库中免费提供了该扫描。基于k倍交叉验证的平均准确性对检测性能进行了评估，在我们的测试中它的得分为99.58％。关于货盘定位和跟踪，在机器人接近货盘叉的情况下进行了实验。尽管最初只通过考虑一个托盘来获取数据，但也已经生成了仿真数据以模拟机器人工作空间中多个目标的存在。我们的实验结果证实，该系统能够以高成功率识别，定位和跟踪托盘，同时对误报有强大的影响力。

##### URL
[http://arxiv.org/abs/1803.11254](http://arxiv.org/abs/1803.11254)

##### PDF
[http://arxiv.org/pdf/1803.11254](http://arxiv.org/pdf/1803.11254)

