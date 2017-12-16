---
layout: post
title: "Learning to Estimate Pose by Watching Videos"
date: 2017-04-13 11:54:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Action_Recognition CNN Detection Recognition
author: Prabuddha Chakraborty, Vinay P. Namboodiri
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a technique for obtaining coarse pose estimation of humans in an image that does not require any manual supervision. While a general unsupervised technique would fail to estimate human pose, we suggest that sufficient information about coarse pose can be obtained by observing human motion in multiple frames. Specifically, we consider obtaining surrogate supervision through videos as a means for obtaining motion based grouping cues. We supplement the method using a basic object detector that detects persons. With just these components we obtain a rough estimate of the human pose. With these samples for training, we train a fully convolutional neural network (FCNN)[20] to obtain accurate dense blob based pose estimation. We show that the results obtained are close to the ground-truth and to the results obtained using a fully supervised convolutional pose estimation method [31] as evaluated on a challenging dataset [15]. This is further validated by evaluating the obtained poses using a pose based action recognition method [5]. In this setting we outperform the results as obtained using the baseline method that uses a fully supervised pose estimation algorithm and is competitive with a new baseline created using convolutional pose estimation with full supervision.

##### Abstract (translated by Google)
在本文中，我们提出了一种获取图像中的粗略姿态估计的技术，不需要任何人工监督。虽然一般的无监督技术将无法估计人的姿势，但是我们建议通过观察多帧中的人体运动来获得关于粗略姿势的足够的信息。具体而言，我们考虑通过视频获取代理监督作为获得基于运动的分组提示的手段。我们使用检测人员的基本对象检测器来补充该方法。只有这些组件，我们可以对人体姿势进行粗略估计。利用这些训练样本，我们训练一个完全卷积神经网络（FCNN）[20]来获得精确的基于密度斑点的姿态估计。我们表明，所获得的结果是接近地面实况，并使用完全监督卷积姿态估计方法获得的结果[31]评估在具有挑战性的数据集[15]。这通过使用基于姿势的动作识别方法评估获得的姿势来进一步验证[5]。在这种情况下，我们优于使用基于完全监督的姿态估计算法的基线方法所获得的结果，并与全面监督下使用卷积姿态估计所创建的新基线相竞争。

##### URL
[https://arxiv.org/abs/1704.04081](https://arxiv.org/abs/1704.04081)

##### PDF
[https://arxiv.org/pdf/1704.04081](https://arxiv.org/pdf/1704.04081)

