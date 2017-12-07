---
layout: post
title: "S-OHEM: Stratified Online Hard Example Mining for Object Detection"
date: 2017-08-15 08:41:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection Recognition
author: Minne Li, Zhaoning Zhang, Hao Yu, Xinyuan Chen, Dongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
One of the major challenges in object detection is to propose detectors with highly accurate localization of objects. The online sampling of high-loss region proposals (hard examples) uses the multitask loss with equal weight settings across all loss types (e.g, classification and localization, rigid and non-rigid categories) and ignores the influence of different loss distributions throughout the training process, which we find essential to the training efficacy. In this paper, we present the Stratified Online Hard Example Mining (S-OHEM) algorithm for training higher efficiency and accuracy detectors. S-OHEM exploits OHEM with stratified sampling, a widely-adopted sampling technique, to choose the training examples according to this influence during hard example mining, and thus enhance the performance of object detectors. We show through systematic experiments that S-OHEM yields an average precision (AP) improvement of 0.5% on rigid categories of PASCAL VOC 2007 for both the IoU threshold of 0.6 and 0.7. For KITTI 2012, both results of the same metric are 1.6%. Regarding the mean average precision (mAP), a relative increase of 0.3% and 0.5% (1% and 0.5%) is observed for VOC07 (KITTI12) using the same set of IoU threshold. Also, S-OHEM is easy to integrate with existing region-based detectors and is capable of acting with post-recognition level regressors.

##### Abstract (translated by Google)
目标检测的主要挑战之一是提出具有高度精确的物体定位的检测器。高损失区域提案（硬示例）的在线采样使用跨所有损失类型（例如，分类和本地化，刚性和非刚性类别）的具有相同权重设置的多任务损失，并且忽略整个培训中不同损失分布的影响过程，我们认为这对培训效果至关重要。在本文中，我们提出了分层在线硬示例挖掘（S-OHEM）算法来训练更高效率和更精确的探测器。 S-OHEM采用了广泛采用的分层采样技术OHEM，在硬采样挖掘过程中根据这种影响选择训练样例，从而提高了物体探测器的性能。我们通过系统的实验显示，对于0.6和0.7的IoU阈值，S-OHEM在PASCAL VOC 2007的刚性类别上产生平均精确度（AP）提高0.5％。对于KITTI 2012，同一指标的结果均为1.6％。关于平均精度（mAP），使用相同的IoU阈值，对于VOC07（KITTI12）观察到相对增加0.3％和0.5％（1％和0.5％）。而且，S-OHEM很容易与现有的基于区域的检测器集成，并且能够与识别后级别的回归器一起工作。

##### URL
[https://arxiv.org/abs/1705.02233](https://arxiv.org/abs/1705.02233)

##### PDF
[https://arxiv.org/pdf/1705.02233](https://arxiv.org/pdf/1705.02233)

