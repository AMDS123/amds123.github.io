---
layout: post
title: "Development of a N-type GM-PHD Filter for Multiple Target, Multiple Type Visual Tracking"
date: 2017-11-27 15:08:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Nathanael L. Baisa, Andrew Wallace
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new framework that extends the standard Probability Hypothesis Density (PHD) filter for multiple targets having $N$ different types where $N\geq2$ based on Random Finite Set (RFS) theory, taking into account not only background false positives (clutter), but also confusions among detections of different target types, which are in general different in character from background clutter. Under the assumptions of Gaussianity and linearity, our framework extends the existing Gaussian mixture (GM) implementation of the standard PHD filter to create a N-type GM-PHD filter. The methodology is applied to real video sequences by integrating object detectors' information into this filter for two scenarios. In the first scenario, a tri-GM-PHD filter ($N=3$) is applied to real video sequences containing three types of multiple targets in the same scene, two football teams and a referee, using separate but confused detections. In the second scenario, we use a dual GM-PHD filter ($N=2$) for tracking pedestrians and vehicles in the same scene handling their detectors' confusions. For both cases, Munkres's variant of the Hungarian assignment algorithm is used to associate tracked target identities between frames. This approach is evaluated and compared to both raw detection and independent GM-PHD filters using the Optimal Sub-pattern Assignment (OSPA) metric and the discrimination rate. This shows the improved performance of our strategy on real video sequences.

##### Abstract (translated by Google)
我们提出了一个新的框架，扩展标准概率假设密度（PHD）过滤器的多个目标有$ N $不同类型，其中$ N \ geq2 $基于随机有限集合（RFS）理论，不仅考虑到背景误报杂波），而且在不同目标类型的检测中混淆，这些目标类型与背景混乱性质通常不同。在高斯性和线性假设下，我们的框架扩展了标准PHD滤波器的现有高斯混合（GM）实现，以创建N型GM-PHD滤波器。该方法适用于真实的视频序列，通过将两个场景中的物体探测器的信息整合到这个滤波器中。在第一种情况下，三个GM-PHD过滤器（$ N = 3 $）被应用于在同一场景中包含三种类型的多个目标的实际视频序列，两个足球队和裁判员，使用单独但是混淆的检测。在第二种情况下，我们使用双GM-PHD滤波器（$ N = 2 $）来跟踪同一场景中的行人和车辆，以处理其检测器的混淆。对于这两种情况，Munkres的匈牙利分配算法的变体被用于在帧之间关联跟踪的目标身份。使用最佳子模式分配（OSPA）度量和鉴别率评估这种方法，并与原始检测和独立的GM-PHD滤波器进行比较。这显示了我们的策略在实际视频序列上的改进的性能。

##### URL
[https://arxiv.org/abs/1706.00672](https://arxiv.org/abs/1706.00672)

##### PDF
[https://arxiv.org/pdf/1706.00672](https://arxiv.org/pdf/1706.00672)

