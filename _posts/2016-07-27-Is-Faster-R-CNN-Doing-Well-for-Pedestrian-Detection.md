---
layout: post
title: "Is Faster R-CNN Doing Well for Pedestrian Detection?"
date: 2016-07-27 03:35:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Liliang Zhang, Liang Lin, Xiaodan Liang, Kaiming He
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting pedestrian has been arguably addressed as a special topic beyond general object detection. Although recent deep learning object detectors such as Fast/Faster R-CNN [1, 2] have shown excellent performance for general object detection, they have limited success for detecting pedestrian, and previous leading pedestrian detectors were in general hybrid methods combining hand-crafted and deep convolutional features. In this paper, we investigate issues involving Faster R-CNN [2] for pedestrian detection. We discover that the Region Proposal Network (RPN) in Faster R-CNN indeed performs well as a stand-alone pedestrian detector, but surprisingly, the downstream classifier degrades the results. We argue that two reasons account for the unsatisfactory accuracy: (i) insufficient resolution of feature maps for handling small instances, and (ii) lack of any bootstrapping strategy for mining hard negative examples. Driven by these observations, we propose a very simple but effective baseline for pedestrian detection, using an RPN followed by boosted forests on shared, high-resolution convolutional feature maps. We comprehensively evaluate this method on several benchmarks (Caltech, INRIA, ETH, and KITTI), presenting competitive accuracy and good speed. Code will be made publicly available.

##### Abstract (translated by Google)
探测行人被认为是超越一般物体检测的特殊话题。尽管最近的快速/快速R-CNN [1,2]等深度学习目标探测器在通用目标检测方面表现出色，但它们在行人检测方面的成功有限，而以前的主流行人检测器则采用混合手工方式和深卷积特征。在本文中，我们调查涉及更快R-CNN [2]行人检测的问题。我们发现快速R-CNN中的区域提议网络（RPN）确实表现出很好的独立行人检测器的性能，但令人惊讶的是，下游分类器降低了结果。我们认为有两个原因说明准确性不理想：（1）处理小实例的特征映射解决不足;（2）没有任何引导策略来挖掘硬性反例。在这些观察的驱动下，我们提出了一个非常简单而有效的行人检测基线，使用RPN，然后在共享的高分辨率卷积特征地图上增强森林。我们在几个基准（加州理工学院，INRIA，ETH和KITTI）上综合评估这个方法，表现出有竞争力的准确性和良好的速度。代码将被公开。

##### URL
[https://arxiv.org/abs/1607.07032](https://arxiv.org/abs/1607.07032)

##### PDF
[https://arxiv.org/pdf/1607.07032](https://arxiv.org/pdf/1607.07032)

