---
layout: post
title: "A Baseline for 3D Multi-Object Tracking"
date: 2019-07-09 03:26:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Detection
author: Xinshuo Weng, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
3D multi-object tracking (MOT) is an essential component technology for many real-time applications such as autonomous driving or assistive robotics. However, recent works for 3D MOT tend to focus more on developing accurate systems giving less regard to computational cost and system complexity. In contrast, this work proposes a simple yet accurate real-time baseline 3D MOT system. We use an off-the-shelf 3D object detector to obtain oriented 3D bounding boxes from the LiDAR point cloud. Then, a combination of 3D Kalman filter and Hungarian algorithm is used for state estimation and data association. Although our baseline system is a straightforward combination of standard methods, we obtain the state-of-the-art results. To evaluate our baseline system, we propose a new 3D MOT extension to the official KITTI 2D MOT evaluation along with two new metrics. Our proposed baseline method for 3D MOT establishes new state-of-the-art performance on 3D MOT for KITTI, improving the 3D MOTA from 72.23 of prior art to 76.47. Surprisingly, by projecting our 3D tracking results to the 2D image plane and compare against published 2D MOT methods, our system places 2nd on the official KITTI leaderboard. Also, our proposed 3D MOT method runs at a rate of 214.7 FPS, 65 times faster than the state-of-the-art 2D MOT system. Our code is publicly available at https://github.com/xinshuoweng/AB3DMOT

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03961](http://arxiv.org/abs/1907.03961)

##### PDF
[http://arxiv.org/pdf/1907.03961](http://arxiv.org/pdf/1907.03961)

