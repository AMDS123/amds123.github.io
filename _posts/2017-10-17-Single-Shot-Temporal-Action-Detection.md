---
layout: post
title: "Single Shot Temporal Action Detection"
date: 2017-10-17 12:41:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Tianwei Lin, Xu Zhao, Zheng Shou
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action detection is a very important yet challenging problem, since videos in real applications are usually long, untrimmed and contain multiple action instances. This problem requires not only recognizing action categories but also detecting start time and end time of each action instance. Many state-of-the-art methods adopt the "detection by classification" framework: first do proposal, and then classify proposals. The main drawback of this framework is that the boundaries of action instance proposals have been fixed during the classification step. To address this issue, we propose a novel Single Shot Action Detector (SSAD) network based on 1D temporal convolutional layers to skip the proposal generation step via directly detecting action instances in untrimmed video. On pursuit of designing a particular SSAD network that can work effectively for temporal action detection, we empirically search for the best network architecture of SSAD due to lacking existing models that can be directly adopted. Moreover, we investigate into input feature types and fusion strategies to further improve detection accuracy. We conduct extensive experiments on two challenging datasets: THUMOS 2014 and MEXaction2. When setting Intersection-over-Union threshold to 0.5 during evaluation, SSAD significantly outperforms other state-of-the-art systems by increasing mAP from 19.0% to 24.6% on THUMOS 2014 and from 7.4% to 11.0% on MEXaction2.

##### Abstract (translated by Google)
时间动作检测是一个非常重要但具有挑战性的问题，因为实际应用中的视频通常很长，不受限制，并且包含多个动作实例。这个问题不仅需要识别动作类别，还要检测每个动作实例的开始时间和结束时间。许多最先进的方法采用“分类检测”框架：首先提出建议，然后对提案进行分类。这个框架的主要缺点是行动实例建议的边界在分类阶段已经被修正。为了解决这个问题，我们提出了一种基于1D时间卷积层的新型单发行为检测器（SSAD），通过直接检测未修剪视频中的动作实例，跳过了建议生成步骤。由于缺乏可直接采用的现有模型，为了追求设计一个可以有效工作的时间动作检测的SSAD网络，我们实证地搜索了SSAD的最佳网络结构。此外，我们调查输入特征类型和融合策略，以进一步提高检测精度。我们对两个具有挑战性的数据集进行了广泛的实验：THUMOS 2014和MEXaction2。在评估过程中将交叉口联合阈值设置为0.5时，SSAD在THUMOS 2014中将MAP从19.0％提高到24.6％，在MEXaction2上从7.4％提高到11.0％，明显优于其他最先进的系统。

##### URL
[https://arxiv.org/abs/1710.06236](https://arxiv.org/abs/1710.06236)

##### PDF
[https://arxiv.org/pdf/1710.06236](https://arxiv.org/pdf/1710.06236)

