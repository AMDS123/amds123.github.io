---
layout: post
title: "Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving"
date: 2018-12-18 05:37:04
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Yan Wang, Wei-Lun Chao, Divyansh Garg, Bharath Hariharan, Mark Campbell, Kilian Weinberger
mathjax: true
---

* content
{:toc}

##### Abstract
3D object detection is an essential task in autonomous driving. Recent techniques excel with highly accurate detection rates, provided the 3D input data is obtained from precise but expensive LiDAR technology. Approaches based on cheaper monocular or stereo imagery data have, until now, resulted in drastically lower accuracies --- a gap that is commonly attributed to poor image-based depth estimation. However, in this paper we argue that data representation (rather than its quality) accounts for the majority of the difference. Taking the inner workings of convolutional neural networks into consideration, we propose to convert image-based depth maps to pseudo-LiDAR representations --- essentially mimicking LiDAR signal. With this representation we can apply different existing LiDAR-based detection algorithms. On the popular KITTI benchmark, our approach achieves impressive improvements over the existing state-of-the-art in image-based performance --- raising the detection accuracy of objects within 30m range from the previous state-of-the-art of 22\% to an unprecedented 74\%. At the time of submission our algorithm holds the highest entry on the KITTI 3D object detection leaderboard for stereo image based approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07179](http://arxiv.org/abs/1812.07179)

##### PDF
[http://arxiv.org/pdf/1812.07179](http://arxiv.org/pdf/1812.07179)

