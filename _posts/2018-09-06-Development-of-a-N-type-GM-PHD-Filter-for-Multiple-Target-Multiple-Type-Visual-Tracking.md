---
layout: post
title: "Development of a N-type GM-PHD Filter for Multiple Target, Multiple Type Visual Tracking"
date: 2018-09-06 11:36:51
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
我们提出了一个新的框架，扩展标准概率假设密度（PHD）过滤器，用于具有$ N $不同类型的多个目标，其中$ N \ geq2 $基于随机有限集（RFS）理论，不仅考虑背景误报（杂乱），但也存在不同目标类型的检测之间的混淆，这些检测通常与背景杂乱不同。在高斯性和线性度的假设下，我们的框架扩展了标准PHD滤波器的现有高斯混合（GM）实现，以创建N型GM-PHD滤波器。通过将对象检测器的信息集成到该过滤器中，该方法应用于实际视频序列，用于两种情况。在第一种情况下，三-GM-PHD滤波器（$ N = 3 $）应用于包含同一场景中的三种类型的多个目标的真实视频序列，两个足球队和一个裁判，使用单独但混乱的检测。在第二种情况下，我们使用双GM-PHD滤波器（$ N = 2 $）来跟踪处理探测器混乱的同一场景中的行人和车辆。对于这两种情况，Munkres的匈牙利分配算法的变体用于关联帧之间的跟踪目标身份。使用最佳子模式分配（OSPA）度量和辨别率来评估该方法并与原始检测和独立GM-PHD滤波器进行比较。这表明我们的策略在真实视频序列上的性能得到了改善。

##### URL
[http://arxiv.org/abs/1706.00672](http://arxiv.org/abs/1706.00672)

##### PDF
[http://arxiv.org/pdf/1706.00672](http://arxiv.org/pdf/1706.00672)

