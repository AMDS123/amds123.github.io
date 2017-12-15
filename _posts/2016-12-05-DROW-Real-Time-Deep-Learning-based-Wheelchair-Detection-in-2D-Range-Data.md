---
layout: post
title: "DROW: Real-Time Deep Learning based Wheelchair Detection in 2D Range Data"
date: 2016-12-05 18:06:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Lucas Beyer, Alexander Hermans, Bastian Leibe
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the DROW detector, a deep learning based detector for 2D range data. Laser scanners are lighting invariant, provide accurate range data, and typically cover a large field of view, making them interesting sensors for robotics applications. So far, research on detection in laser range data has been dominated by hand-crafted features and boosted classifiers, potentially losing performance due to suboptimal design choices. We propose a Convolutional Neural Network (CNN) based detector for this task. We show how to effectively apply CNNs for detection in 2D range data, and propose a depth preprocessing step and voting scheme that significantly improve CNN performance. We demonstrate our approach on wheelchairs and walkers, obtaining state of the art detection results. Apart from the training data, none of our design choices limits the detector to these two classes, though. We provide a ROS node for our detector and release our dataset containing 464k laser scans, out of which 24k were annotated.

##### Abstract (translated by Google)
我们介绍了DROW探测器，一种2D范围数据的基于深度学习的探测器。激光扫描仪是光照不变的，提供准确的距离数据，并且通常覆盖大视野，使其成为机器人应用的有趣传感器。到目前为止，激光测距数据检测的研究一直以手工特征和增强分类器为主，由于设计选择不理想，可能会损失性能。我们提出了一个基于卷积神经网络（CNN）的检测器。我们展示了如何有效地将CNN应用于二维距离数据的检测，并提出了一个深度预处理步骤和投票方案，显着提高CNN性能。我们展示了我们在轮椅和步行者方面的方法，获得了最先进的检测结果。除了训练数据之外，我们的设计选择都没有将探测器限制到这两个类别。我们为我们的探测器提供一个ROS节点，并释放包含464k激光扫描的数据集，其中24k被注释。

##### URL
[https://arxiv.org/abs/1603.02636](https://arxiv.org/abs/1603.02636)

##### PDF
[https://arxiv.org/pdf/1603.02636](https://arxiv.org/pdf/1603.02636)

