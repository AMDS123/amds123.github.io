---
layout: post
title: "RoarNet: A Robust 3D Object Detection based on RegiOn Approximation Refinement"
date: 2018-11-09 08:43:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Inference Detection
author: Kiwoo Shin, Youngwook Paul Kwon, Masayoshi Tomizuka
mathjax: true
---

* content
{:toc}

##### Abstract
We present RoarNet, a new approach for 3D object detection from a 2D image and 3D Lidar point clouds. Based on two-stage object detection framework with PointNet as our backbone network, we suggest several novel ideas to improve 3D object detection performance. The first part of our method, RoarNet_2D, estimates the 3D poses of objects from a monocular image, which approximates where to examine further, and derives multiple candidates that are geometrically feasible. This step significantly narrows down feasible 3D regions, which otherwise requires demanding processing of 3D point clouds in a huge search space. Then the second part, RoarNet_3D, takes the candidate regions and conducts in-depth inferences to conclude final poses in a recursive manner. Inspired by PointNet, RoarNet_3D processes 3D point clouds directly without any loss of data, leading to precise detection. We evaluate our method in KITTI, a 3D object detection benchmark. Our result shows that RoarNet has superior performance to state-of-the-art methods that are publicly available. Remarkably, RoarNet also outperforms state-of-the-art methods even in settings where Lidar and camera are not time synchronized, which is practically important for actual driving environments. RoarNet is implemented in Tensorflow and publicly available with pre-trained models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03818](http://arxiv.org/abs/1811.03818)

##### PDF
[http://arxiv.org/pdf/1811.03818](http://arxiv.org/pdf/1811.03818)

