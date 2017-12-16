---
layout: post
title: "Cascaded Pyramid Network for Multi-Person Pose Estimation"
date: 2017-11-20 14:36:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Detection
author: Yilun Chen, Zhicheng Wang, Yuxiang Peng, Zhiqiang Zhang, Gang Yu, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
The topic of multi-person pose estimation has been largely improved recently, especially with the development of convolutional neural network. However, there still exist a lot of challenging cases, such as occluded keypoints, invisible keypoints and complex background, which cannot be well addressed. In this paper, we present a novel network structure called Cascaded Pyramid Network (CPN) which targets to relieve the problem from these "hard" keypoints. More specifically, our algorithm includes two stages: GlobalNet and RefineNet. GlobalNet is a feature pyramid network which can successfully localize the "simple" keypoints like eyes and hands but may fail to precisely recognize the occluded or invisible keypoints. Our RefineNet tries explicitly handling the "hard" keypoints by integrating all levels of feature representations from the GlobalNet together with an online hard keypoint mining loss. In general, to address the multi-person pose estimation problem, a top-down pipeline is adopted to first generate a set of human bounding boxes based on a detector, followed by our CPN for keypoint localization in each human bounding box. Based on the proposed algorithm, we achieve state-of-art results on the COCO keypoint benchmark, with average precision at 73.0 on the COCO test-dev dataset and 72.1 on the COCO test-challenge dataset, which is a 19% relative improvement compared with 60.5 from the COCO 2016 keypoint challenge.

##### Abstract (translated by Google)
多人姿态估计的主题近年来有了很大的改进，特别是随着卷积神经网络的发展。但是，仍然存在很多具有挑战性的案例，比如闭塞的关键点，隐形的关键点和复杂的背景，这些都不能很好地解决。在本文中，我们提出了一种称为级联金字塔网络（CPN）的新型网络结构，其目标是从这些“硬”关键点解决问题。更具体地说，我们的算法包括两个阶段：GlobalNet和RefineNet。 GlobalNet是一个功能金字塔网络，可以成功定位“简单”的关键点，如眼睛和手，但可能无法精确识别被遮挡或不可见的关键点。我们的RefineNet试图通过整合来自GlobalNet的所有级别的特征表示以及在线硬关键点采矿损失来明确处理“硬”关键点。一般来说，为了解决多人姿态估计问题，采用自顶向下的流水线，首先根据检测器生成一组人体包围盒，然后在每个人体包围盒中进行关键点定位的CPN。基于所提出的算法，我们在COCO关键点基准上获得了最新的结果，COCO测试数据集的平均精确度为73.0，COCO测试挑战数据集的平均精度为72.1，相比之下，相对提高了19％ COCO2016关键挑战为60.5。

##### URL
[https://arxiv.org/abs/1711.07319](https://arxiv.org/abs/1711.07319)

##### PDF
[https://arxiv.org/pdf/1711.07319](https://arxiv.org/pdf/1711.07319)

