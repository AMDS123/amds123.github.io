---
layout: post
title: "GroundNet: Segmentation-Aware Monocular Ground Plane Estimation with Geometric Consistency"
date: 2018-11-17 21:25:53
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Prediction Detection
author: Yunze Man, Xinshuo Weng, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the problem of estimating the orientation of the ground plane with respect to a mobile monocular camera platform (e.g., ground robot, wearable camera, assistive robotic platform). To address this problem, we formulate the ground plane estimation problem as an inter-mingled multi-task prediction problem by jointly optimizing for point-wise surface normal direction, 2D ground segmentation, and depth estimates. Our proposed model -- GroundNet -- estimates the ground normal in two streams separately and then a consistency loss is applied on top of the two streams to enforce geometric consistency. A semantic segmentation stream is used to isolate the ground regions and are used to selectively back-propagate parameter updates only through the ground regions in the image. Our experiments on KITTI and ApolloScape datasets verify that the GroundNet is able to predict consistent depth and normal within the ground region. It also achieves top performance on ground plane normal estimation and horizon line detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07222](http://arxiv.org/abs/1811.07222)

##### PDF
[http://arxiv.org/pdf/1811.07222](http://arxiv.org/pdf/1811.07222)

