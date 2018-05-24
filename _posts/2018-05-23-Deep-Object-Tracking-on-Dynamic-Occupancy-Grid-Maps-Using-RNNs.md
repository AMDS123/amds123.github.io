---
layout: post
title: "Deep Object Tracking on Dynamic Occupancy Grid Maps Using RNNs"
date: 2018-05-23 07:36:48
categories: arXiv_RO
tags: arXiv_RO Object_Detection Segmentation Tracking CNN Object_Tracking RNN Detection
author: Nico Engel, Stefan Hoermann, Philipp Henzler, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
The comprehensive representation and understanding of the driving environment is crucial to improve the safety and reliability of autonomous vehicles. In this paper, we present a new approach to establish an environment model containing a segmentation between static and dynamic background and parametric modeled objects with shape, position and orientation. Multiple laser scanners are fused into a dynamic occupancy grid map resulting in a 360{\deg} perception of the environment. A single-stage deep convolutional neural network is combined with a recurrent neural network, which takes a time series of the occupancy grid map as input and tracks cell states and its corresponding object hypotheses. The labels for training are created unsupervised with an automatic label generation algorithm. 
 The proposed methods are evaluated in real-world experiments in complex inner city scenarios using the aforementioned 360{\deg} laser perception. The results show a better object detection accuracy in comparison with our old approach as well as an AUC score of 0.946 for the dynamic and static segmentation. Furthermore, we gain an improved detection for occluded objects and a more consistent size estimation due to the usage of time series as input and the memory about previous states introduced by the recurrent neural network.

##### Abstract (translated by Google)
对驾驶环境的全面表达和理解对于提高自动驾驶汽车的安全性和可靠性至关重要。在本文中，我们提出了一种新的方法来建立一个环境模型，其中包含静态和动态背景之间的分割以及具有形状，位置和方向的参数建模对象。多个激光扫描仪融合到一个动态占用网格图中，导致对环境的360度感知。将单级深度卷积神经网络与循环神经网络相结合，该网络将占用网格图的时间序列作为输入并跟踪细胞状态及其相应的对象假设。用于自动标签生成算法的训练标签不受监督。
 所提出的方法在复杂的内城情景中的实际实验中使用前述的360°激光感知进行评估。结果显示，与我们的老方法相比，更好的目标检测精度以及动态和静态分割的0.946的AUC评分。此外，由于使用时间序列作为输入以及回归神经网络引入的先前状态的记忆，我们获得了对闭塞物体的改进检测和更一致的尺寸估计。

##### URL
[http://arxiv.org/abs/1805.08986](http://arxiv.org/abs/1805.08986)

##### PDF
[http://arxiv.org/pdf/1805.08986](http://arxiv.org/pdf/1805.08986)

