---
layout: post
title: "Fast Multi-frame Stereo Scene Flow with Motion Segmentation"
date: 2017-07-05 10:42:34
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Tatsunori Taniai, Sudipta N. Sinha, Yoichi Sato
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new multi-frame method for efficiently computing scene flow (dense depth and optical flow) and camera ego-motion for a dynamic scene observed from a moving stereo camera rig. Our technique also segments out moving objects from the rigid scene. In our method, we first estimate the disparity map and the 6-DOF camera motion using stereo matching and visual odometry. We then identify regions inconsistent with the estimated camera motion and compute per-pixel optical flow only at these regions. This flow proposal is fused with the camera motion-based flow proposal using fusion moves to obtain the final optical flow and motion segmentation. This unified framework benefits all four tasks - stereo, optical flow, visual odometry and motion segmentation leading to overall higher accuracy and efficiency. Our method is currently ranked third on the KITTI 2015 scene flow benchmark. Furthermore, our CPU implementation runs in 2-3 seconds per frame which is 1-3 orders of magnitude faster than the top six methods. We also report a thorough evaluation on challenging Sintel sequences with fast camera and object motion, where our method consistently outperforms OSF [Menze and Geiger, 2015], which is currently ranked second on the KITTI benchmark.

##### Abstract (translated by Google)
我们提出了一种新的多帧方法，用于高效地计算场景流（密集深度和光流）以及从移动立体相机平台观察到的动态场景的相机自我运动。我们的技术也从僵硬的场景中分割出移动的物体。在我们的方法中，我们首先使用立体匹配和视觉测距来估计视差图和六自由度摄像机运动。然后，我们识别与估计的相机运动不一致的区域，并仅在这些区域处计算每像素光流。该流程建议与基于相机运动的流程建议融合使用融合移动来获得最终的光流和运动分割。这个统一的框架有利于所有四个任务 - 立体声，光流，视觉测距和运动分割，从而导致整体更高的准确性和效率。我们的方法目前在KITTI 2015现场流量基准中排名第三。此外，我们的CPU实现每帧运行2-3秒，比前六个方法快1-3个数量级。我们还通过快速摄像机和物体运动报告了对具有挑战性的Sintel序列的全面评估，其中我们的方法始终优于OSIT [Menze和Geiger，2015]，目前在KITTI基准测试中排名第二。

##### URL
[https://arxiv.org/abs/1707.01307](https://arxiv.org/abs/1707.01307)

##### PDF
[https://arxiv.org/pdf/1707.01307](https://arxiv.org/pdf/1707.01307)

