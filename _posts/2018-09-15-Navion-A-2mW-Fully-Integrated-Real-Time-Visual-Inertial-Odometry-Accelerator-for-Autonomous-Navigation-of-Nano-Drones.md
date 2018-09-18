---
layout: post
title: "Navion: A 2mW Fully Integrated Real-Time Visual-Inertial Odometry Accelerator for Autonomous Navigation of Nano Drones"
date: 2018-09-15 22:54:05
categories: arXiv_RO
tags: arXiv_RO Knowledge Drone Optimization
author: Amr Suleiman, Zhengdong Zhang, Luca Carlone, Sertac Karaman, Vivienne Sze
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents Navion, an energy-efficient accelerator for visual-inertial odometry (VIO) that enables autonomous navigation of miniaturized robots (e.g., nano drones), and virtual/augmented reality on portable devices. The chip uses inertial measurements and mono/stereo images to estimate the drone's trajectory and a 3D map of the environment. This estimate is obtained by running a state-of-the-art VIO algorithm based on non-linear factor graph optimization, which requires large irregularly structured memories and heterogeneous computation flow. To reduce the energy consumption and footprint, the entire VIO system is fully integrated on chip to eliminate costly off-chip processing and storage. This work uses compression and exploits both structured and unstructured sparsity to reduce on-chip memory size by 4.1$\times$. Parallelism is used under tight area constraints to increase throughput by 43%. The chip is fabricated in 65nm CMOS, and can process 752$\times$480 stereo images from EuRoC dataset in real-time at 20 frames per second (fps) consuming only an average power of 2mW. At its peak performance, Navion can process stereo images at up to 171 fps and inertial measurements at up to 52 kHz, while consuming an average of 24mW. The chip is configurable to maximize accuracy, throughput and energy-efficiency trade-offs and to adapt to different environments. To the best of our knowledge, this is the first fully integrated VIO system in an ASIC.

##### Abstract (translated by Google)
本文介绍了Navion，一种用于视觉惯性测距（VIO）的节能加速器，可实现微型机器人（例如纳米无人机）的自动导航，以及便携式设备上的虚拟/增强现实。该芯片使用惯性测量和单声道/立体声图像来估计无人机的轨迹和环境的3D地图。该估计是通过运行基于非线性因子图优化的最先进的VIO算法获得的，该算法需要大的不规则结构的存储器和异构的计算流。为了降低能耗和占用空间，整个VIO系统完全集成在芯片上，以消除昂贵的片外处理和存储。这项工作使用压缩并利用结构化和非结构化稀疏性将片上内存大小减少4.1 $ \ times $。在严格的区域约束下使用并行性可将吞吐量提高43％。该芯片采用65nm CMOS制造，可以每秒20帧（fps）实时处理来自EuRoC数据集的752美元的480美元立体图像，平均功耗仅为2mW。在其最高性能时，Navion可以处理高达171 fps的立体声图像和高达52 kHz的惯性测量，同时平均消耗24mW。该芯片可配置为最大化精度，吞吐量和能效折衷，并适应不同的环境。据我们所知，这是ASIC中第一个完全集成的VIO系统。

##### URL
[http://arxiv.org/abs/1809.05780](http://arxiv.org/abs/1809.05780)

##### PDF
[http://arxiv.org/pdf/1809.05780](http://arxiv.org/pdf/1809.05780)

