---
layout: post
title: "Multi-Scale Structure-Aware Network for Human Pose Estimation"
date: 2018-03-29 01:35:59
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Lipeng Ke, Ming-Ching Chang, Honggang Qi, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a robust multi-scale structure-aware neural network for human pose estimation. This method improves the recent deep conv-deconv hourglass models with four key improvements: (1) multi-scale supervision to strengthen contextual feature learning in matching body keypoints by combining feature heatmaps across scales, (2) multi-scale regression network at the end to globally optimize the structural matching of the multi-scale features, (3) structure-aware loss used in the intermediate supervision and at the regression to improve the matching of keypoints and respective neighbors to infer a higher-order matching configurations, and (4) a keypoint masking training scheme that can effectively fine-tune our network to robustly localize occluded keypoints via adjacent matches. Our method can effectively improve state-of-the-art pose estimation methods that suffer from difficulties in scale varieties, occlusions, and complex multi-person scenarios. This multi-scale supervision tightly integrates with the regression network to effectively (i) localize keypoints using the ensemble of multi-scale features, and (ii) infer global pose configuration by maximizing structural consistencies across multiple keypoints and scales. The keypoint masking training enhances these advantages to focus learning on hard occlusion samples. Our method achieves the leading position in the MPII challenge leaderboard among the state-of-the-art methods.

##### Abstract (translated by Google)
我们为人体姿态估计开发了一个稳健的多尺度结构感知神经网络。该方法改进了最近的深度卷积 - 沙漏模型，其中有四项重要改进：（1）多尺度监督，通过跨越尺度组合特征热点来加强情景特征学习以匹配身体关键点;（2）多尺度回归网络以全局优化多尺度特征的结构匹配，（3）在中间监督和回归中使用的结构感知损失，以改进关键点和相邻邻居的匹配以推断更高阶的匹配配置，以及（4 ）一个关键点掩蔽训练方案，可以有效地微调我们的网络，通过相邻匹配来稳健地定位被遮挡的关键点。我们的方法可以有效地改善在规模变化，遮挡和复杂的多人场景中遇到困难的最先进的姿态估计方法。这种多尺度监督与回归网络紧密结合以有效地（i）使用多尺度特征的集合来定位关键点，并且（ii）通过跨多个关键点和尺度最大化结构一致性来推断全局姿势配置。关键点遮蔽训练增强了这些优势，将重点放在硬阻塞样本上。我们的方法在MPII挑战排行榜中处于最先进方法的领先地位。

##### URL
[http://arxiv.org/abs/1803.09894](http://arxiv.org/abs/1803.09894)

##### PDF
[http://arxiv.org/pdf/1803.09894](http://arxiv.org/pdf/1803.09894)

