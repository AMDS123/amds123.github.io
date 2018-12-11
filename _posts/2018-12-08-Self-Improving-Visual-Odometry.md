---
layout: post
title: "Self-Improving Visual Odometry"
date: 2018-12-08 00:26:40
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Deep_Learning SLAM
author: Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a self-supervised learning framework that uses unlabeled monocular video sequences to generate large-scale supervision for training a Visual Odometry (VO) frontend, a network which computes pointwise data associations across images. Our self-improving method enables a VO frontend to learn over time, unlike other VO and SLAM systems which require time-consuming hand-tuning or expensive data collection to adapt to new environments. Our proposed frontend operates on monocular images and consists of a single multi-task convolutional neural network which outputs 2D keypoints locations, keypoint descriptors, and a novel point stability score. We use the output of VO to create a self-supervised dataset of point correspondences to retrain the frontend. When trained using VO at scale on 2.5 million monocular images from ScanNet, the stability classifier automatically discovers a ranking for keypoints that are not likely to help in VO, such as t-junctions across depth discontinuities, features on shadows and highlights, and dynamic objects like people. The resulting frontend outperforms both traditional methods (SIFT, ORB, AKAZE) and deep learning methods (SuperPoint and LF-Net) in a 3D-to-2D pose estimation task on ScanNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03245](http://arxiv.org/abs/1812.03245)

##### PDF
[http://arxiv.org/pdf/1812.03245](http://arxiv.org/pdf/1812.03245)

