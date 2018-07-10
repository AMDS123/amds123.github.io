---
layout: post
title: "Real-time clustering and multi-target tracking using event-based sensors"
date: 2018-07-08 16:43:32
categories: arXiv_RO
tags: arXiv_RO Object_Detection Sparse Segmentation Tracking Detection
author: Francisco Barranco, Cornelia Fermuller, Eduardo Ros
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering is crucial for many computer vision applications such as robust tracking, object detection and segmentation. This work presents a real-time clustering technique that takes advantage of the unique properties of event-based vision sensors. Since event-based sensors trigger events only when the intensity changes, the data is sparse, with low redundancy. Thus, our approach redefines the well-known mean-shift clustering method using asynchronous events instead of conventional frames. The potential of our approach is demonstrated in a multi-target tracking application using Kalman filters to smooth the trajectories. We evaluated our method on an existing dataset with patterns of different shapes and speeds, and a new dataset that we collected. The sensor was attached to the Baxter robot in an eye-in-hand setup monitoring real-world objects in an action manipulation task. Clustering accuracy achieved an F-measure of 0.95, reducing the computational cost by 88% compared to the frame-based method. The average error for tracking was 2.5 pixels and the clustering achieved a consistent number of clusters along time.

##### Abstract (translated by Google)
聚类对于许多计算机视觉应用至关重要，例如强大的跟踪，对象检测和分割。这项工作提供了一种实时聚类技术，该技术利用了基于事件的视觉传感器的独特属性。由于基于事件的传感器仅在强度变化时触发事件，因此数据稀疏，冗余度较低。因此，我们的方法重新定义了使用异步事件而不是传统帧的众所周知的均值漂移聚类方法。我们的方法的潜力在使用卡尔曼滤波器来平滑轨迹的多目标跟踪应用中得到证明。我们在现有数据集上评估了我们的方法，该数据集具有不同形状和速度的模式，以及我们收集的新数据集。传感器通过手动设置连接到Baxter机器人，在动作操作任务中监控真实世界的物体。与基于帧的方法相比，聚类精度达到了0.95的F-度量，将计算成本降低了88％。跟踪的平均误差为2.5像素，并且聚类在时间上实现了一致的聚类数量。

##### URL
[http://arxiv.org/abs/1807.02851](http://arxiv.org/abs/1807.02851)

##### PDF
[http://arxiv.org/pdf/1807.02851](http://arxiv.org/pdf/1807.02851)

