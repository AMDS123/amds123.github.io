---
layout: post
title: "Online Visual Multi-Object Tracking via Labeled Random Finite Set Filtering"
date: 2017-08-04 09:01:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Object_Tracking Detection
author: Du Yong Kim, Ba-Ngu Vo, Ba-Tuong Vo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an online visual multi-object tracking algorithm using a top-down Bayesian formulation that seamlessly integrates state estimation, track management, clutter rejection, occlusion and mis-detection handling into a single recursion. This is achieved by modeling the multi-object state as labeled random finite set and using the Bayes recursion to propagate the multi-object filtering density forward in time. The proposed filter updates tracks with detections but switches to image data when mis-detection occurs, thereby exploiting the efficiency of detection data and the accuracy of image data. Furthermore the labeled random finite set framework enables the incorporation of prior knowledge that mis-detections of long tracks which occur in the middle of the scene are likely to be due to occlusions. Such prior knowledge can be exploited to improve occlusion handling, especially long occlusions that can lead to premature track termination in on-line multi-object tracking. Tracking performance are compared to state-of-the-art algorithms on well-known benchmark video datasets.

##### Abstract (translated by Google)
本文提出了一种在线可视多目标跟踪算法，采用自上而下的贝叶斯公式，将状态估计，轨迹管理，杂波抑制，遮挡和误检处理无缝集成到一个递归中。这是通过将多对象状态建模为标记的随机有限集并使用贝叶斯递归来及时向前传播多对象过滤密度来实现的。所提出的滤波器利用检测来更新轨道，但是当发生误检测时切换到图像数据，从而利用检测数据的效率和图像数据的精度。此外，标记的随机有限集合框架使得能够结合先前的知识，即在场景中间发生的长轨道的错误检测可能是由于遮挡造成的。这种先验知识可以被利用来改善遮挡处理，特别是可能导致在线多对象跟踪中的过早轨迹终止的长遮挡。将跟踪性能与众所周知的基准视频数据集上的最新算法进行比较。

##### URL
[https://arxiv.org/abs/1611.06011](https://arxiv.org/abs/1611.06011)

##### PDF
[https://arxiv.org/pdf/1611.06011](https://arxiv.org/pdf/1611.06011)

