---
layout: post
title: "Revisiting RCNN: On Awakening the Classification Power of Faster RCNN"
date: 2018-03-19 04:13:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Bowen Cheng, Yunchao Wei, Honghui Shi, Rogerio Feris, Jinjun Xiong, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent region-based object detectors are usually built with separate classification and localization branches on top of shared feature extraction networks. In this paper, we analyze failure cases of state-of-the-art detectors and observe that most hard false positives result from classification instead of localization. We conjecture that: (1) Shared feature representation is not optimal due to the mismatched goals of feature learning for classification and localization; (2) multi-task learning helps, yet optimization of the multi-task loss may result in sub-optimal for individual tasks; (3) large receptive field for different scales leads to redundant context information for small objects.We demonstrate the potential of detector classification power by a simple, effective, and widely-applicable Decoupled Classification Refinement (DCR) network. DCR samples hard false positives from the base classifier in Faster RCNN and trains a RCNN-styled strong classifier. Experiments show new state-of-the-art results on PASCAL VOC and COCO without any bells and whistles.

##### Abstract (translated by Google)
最近的基于区域的物体检测器通常是在共享特征提取网络的基础上建立独立的分类和本地化分支。在本文中，我们分析了最先进的探测器的故障情况，并观察到大多数硬性误报是由分类而不是本地化产生的。我们猜想：（1）由于分类和定位的特征学习目标不匹配，共享特征表示不是最优的; （2）多任务学习有帮助，但多任务丢失的优化可能导致个别任务的次优; （3）不同尺度下的大容量接收场导致了小物体的冗余上下文信息。通过简单，有效，广泛适用的解耦分类细化（DCR）网络，证明了探测器分类能力的潜力。 DCR从更快的RCNN中的基本分类器中采集硬误报，并训练RCNN风格的强分类器。实验表明，PASCAL VOC和COCO没有任何花里胡哨的新技术。

##### URL
[https://arxiv.org/abs/1803.06799](https://arxiv.org/abs/1803.06799)

##### PDF
[https://arxiv.org/pdf/1803.06799](https://arxiv.org/pdf/1803.06799)

