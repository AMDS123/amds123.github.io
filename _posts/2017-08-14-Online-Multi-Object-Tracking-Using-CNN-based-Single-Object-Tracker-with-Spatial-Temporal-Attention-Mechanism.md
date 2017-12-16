---
layout: post
title: "Online Multi-Object Tracking Using CNN-based Single Object Tracker with Spatial-Temporal Attention Mechanism"
date: 2017-08-14 03:30:17
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Object_Tracking
author: Qi Chu, Wanli Ouyang, Hongsheng Li, Xiaogang Wang, Bin Liu, Nenghai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a CNN-based framework for online MOT. This framework utilizes the merits of single object trackers in adapting appearance models and searching for target in the next frame. Simply applying single object tracker for MOT will encounter the problem in computational efficiency and drifted results caused by occlusion. Our framework achieves computational efficiency by sharing features and using ROI-Pooling to obtain individual features for each target. Some online learned target-specific CNN layers are used for adapting the appearance model for each target. In the framework, we introduce spatial-temporal attention mechanism (STAM) to handle the drift caused by occlusion and interaction among targets. The visibility map of the target is learned and used for inferring the spatial attention map. The spatial attention map is then applied to weight the features. Besides, the occlusion status can be estimated from the visibility map, which controls the online updating process via weighted loss on training samples with different occlusion statuses in different frames. It can be considered as temporal attention mechanism. The proposed algorithm achieves 34.3% and 46.0% in MOTA on challenging MOT15 and MOT16 benchmark dataset respectively.

##### Abstract (translated by Google)
在本文中，我们提出了一个基于CNN的在线MOT框架。该框架利用单目标跟踪器的优点来适应外观模型，并在下一帧搜索目标。简单地将单目标跟踪器应用于MOT将会遇到计算效率上的问题，并且由于遮挡而导致漂移结果。我们的框架通过共享特征和使用ROI-Pooling来获得每个目标的单个特征来实现计算效率。一些在线学习的特定于目标的CNN层被用于适应每个目标的外观模型。在此框架下，引入时空关注机制（STAM）来处理目标间的遮挡和交互引起的漂移。学习目标的可见性图并用于推断空间关注图。然后应用空间关注图来加权特征。此外，可视化图可以估计遮挡状态，通过不同帧遮挡状态不同的训练样本的加权损失来控制在线更新过程。它可以被视为时间上的关注机制。该算法分别在具有挑战性的MOT15和MOT16基准数据集上，在MOTA上达到34.3％和46.0％。

##### URL
[https://arxiv.org/abs/1708.02843](https://arxiv.org/abs/1708.02843)

##### PDF
[https://arxiv.org/pdf/1708.02843](https://arxiv.org/pdf/1708.02843)

