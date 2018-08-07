---
layout: post
title: "Multi-Scale Supervised Network for Human Pose Estimation"
date: 2018-08-05 14:13:10
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Inference Detection Recognition
author: Lipeng Ke, Ming-Ching Chang, Honggang Qi, Siwei Lyu
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose estimation is an important topic in computer vision with many applications including gesture and activity recognition. However, pose estimation from image is challenging due to appearance variations, occlusions, clutter background, and complex activities. To alleviate these problems, we develop a robust pose estimation method based on the recent deep conv-deconv modules with two improvements: (1) multi-scale supervision of body keypoints, and (2) a global regression to improve structural consistency of keypoints. We refine keypoint detection heatmaps using layer-wise multi-scale supervision to better capture local contexts. Pose inference via keypoint association is optimized globally using a regression network at the end. Our method can effectively disambiguate keypoint matches in close proximity including the mismatch of left-right body parts, and better infer occluded parts. Experimental results show that our method achieves competitive performance among state-of-the-art methods on the MPII and FLIC datasets.

##### Abstract (translated by Google)
人体姿势估计是计算机视觉中的重要主题，其具有许多应用，包括手势和活动识别。然而，由于外观变化，遮挡，杂乱背景和复杂活动，图像的姿势估计是具有挑战性的。为了缓解这些问题，我们基于最近的深度conv-deconv模块开发了一种鲁棒的姿态估计方法，该方法有两个改进：（1）对身体关键点的多尺度监督，以及（2）全局回归以提高关键点的结构一致性。我们使用分层多尺度监控来优化关键点检测热图，以更好地捕获局部上下文。通过关键点关联的姿势推断在最后使用回归网络进行全局优化。我们的方法可以有效地消除近距离关键点匹配的歧义，包括左右身体部位的不匹配，以及更好地推断被遮挡的部分。实验结果表明，我们的方法在MPII和FLIC数据集的最先进方法之间取得了竞争性的表现。

##### URL
[https://arxiv.org/abs/1808.01623](https://arxiv.org/abs/1808.01623)

##### PDF
[https://arxiv.org/pdf/1808.01623](https://arxiv.org/pdf/1808.01623)

