---
layout: post
title: "Detect-and-Track: Efficient Pose Estimation in Videos"
date: 2017-12-26 05:56:39
categories: arXiv_CV
tags: arXiv_CV Video_Caption Pose_Estimation Tracking Object_Tracking Prediction Detection
author: Rohit Girdhar, Georgia Gkioxari, Lorenzo Torresani, Manohar Paluri, Du Tran
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of estimating and tracking human body keypoints in complex, multi-person video. We propose an extremely lightweight yet highly effective approach that builds upon the latest advancements in human detection and video understanding. Our method operates in two-stages: keypoint estimation in frames or short clips, followed by lightweight tracking to generate keypoint predictions linked over the entire video. For frame-level pose estimation we experiment with Mask R-CNN, as well as our own proposed 3D extension of this model, which leverages temporal information over small clips to generate more robust frame predictions. We conduct extensive ablative experiments on the newly released multi-person video pose estimation benchmark, PoseTrack, to validate various design choices of our model. Our approach achieves an accuracy of 55.2% on the validation and 51.8% on the test set using the Multi-Object Tracking Accuracy (MOTA) metric, and achieves state of the art performance on the ICCV 2017 PoseTrack keypoint tracking challenge.

##### Abstract (translated by Google)
本文讨论了在复杂的多人视频中估计和跟踪人体关键点的问题。我们提出了一个非常轻便但非常有效的方法，建立在人类检测和视频理解方面的最新进展。我们的方法分为两个阶段：帧或短片段中的关键点估计，然后是轻量级跟踪，以生成关联整个视频的关键点预测。对于帧级姿态估计，我们试验Mask R-CNN，以及我们自己提出的这个模型的3D扩展，它利用小片段上的时间信息来生成更强健的帧预测。我们在新发布的多人视频姿态估计基准PoseTrack上进行了广泛的烧蚀实验，验证了我们模型的各种设计选择。我们的方法使用多目标跟踪精度（MOTA）度量，在验证方面达到了55.2％的精确度，在测试组方面达到了51.8％，并在ICCV 2017年PoseTrack关键点跟踪挑战中实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1712.09184](http://arxiv.org/abs/1712.09184)

##### PDF
[http://arxiv.org/pdf/1712.09184](http://arxiv.org/pdf/1712.09184)

