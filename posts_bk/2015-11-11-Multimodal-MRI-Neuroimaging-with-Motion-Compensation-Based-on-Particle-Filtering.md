---
layout: post
title: "Multimodal MRI Neuroimaging with Motion Compensation Based on Particle Filtering"
date: 2015-11-11 02:52:10
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Yu-Hui Chen, Roni Mittelman, Boklye Kim, Charles Meyer, Alfred Hero
mathjax: true
---

* content
{:toc}

##### Abstract
Head movement during scanning impedes activation detection in fMRI studies. Head motion in fMRI acquired using slice-based Echo Planar Imaging (EPI) can be estimated and compensated by aligning the images onto a reference volume through image registration. However, registering EPI images volume to volume fails to consider head motion between slices, which may lead to severely biased head motion estimates. Slice-to-volume registration can be used to estimate motion parameters for each slice by more accurately representing the image acquisition sequence. However, accurate slice to volume mapping is dependent on the information content of the slices: middle slices are information rich, while edge slides are information poor and more prone to distortion. In this work, we propose a Gaussian particle filter based head motion tracking algorithm to reduce the image misregistration errors. The algorithm uses a dynamic state space model of head motion with an observation equation that models continuous slice acquisition of the scanner. Under this model the particle filter provides more accurate motion estimates and voxel position estimates. We demonstrate significant performance improvement of the proposed approach as compared to registration-only methods of head motion estimation and brain activation detection.

##### Abstract (translated by Google)
扫描期间的头部运动妨碍了fMRI研究中的激活检测。在使用基于切片的回波平面成像（EPI）获得的fMRI中的头部运动可以通过图像配准通过将图像对准到参考体积来估计和补偿。然而，将EPI图像体积注册为体积未能考虑片之间的头部运动，这可能会导致严重偏差的头部运动估计。通过更精确地表示图像采集序列，可以使用切片 - 体积配准来估计每个切片的运动参数。然而，精确的体积映射切片依赖于切片的信息内容：中间切片是信息丰富的，而边缘切片是信息差，更容易失真。在这项工作中，我们提出了一个基于高斯粒子滤波器的头部运动跟踪算法，以减少图像配准误差。该算法使用头部运动的动态状态空间模型和用于模拟扫描仪的连续切片采集的观测方程。在这个模型下，粒子滤波器提供更准确的运动估计和体素位置估计。与头部运动估计和大脑激活检测的仅登记方法相比，我们证明了所提出方法的显着性能改善。

##### URL
[https://arxiv.org/abs/1511.03369](https://arxiv.org/abs/1511.03369)

##### PDF
[https://arxiv.org/pdf/1511.03369](https://arxiv.org/pdf/1511.03369)

