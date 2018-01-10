---
layout: post
title: "Robust Stereo Visual Inertial Odometry for Fast Autonomous Flight"
date: 2018-01-09 16:44:28
categories: arXiv_RO
tags: arXiv_RO
author: Ke Sun, Kartik Mohta, Bernd Pfrommer, Michael Watterson, Sikang Liu, Yash Mulgaonkar, Camillo J. Taylor, Vijay Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, vision-aided inertial odometry for state estimation has matured significantly. However, we still encounter challenges in terms of improving the computational efficiency and robustness of the underlying algorithms for applications in autonomous flight with micro aerial vehicles in which it is difficult to use high quality sensors and pow- erful processors because of constraints on size and weight. In this paper, we present a filter-based stereo visual inertial odometry that uses the Multi-State Constraint Kalman Filter (MSCKF) [1]. Previous work on stereo visual inertial odometry has resulted in solutions that are computationally expensive. We demonstrate that our Stereo Multi-State Constraint Kalman Filter (S-MSCKF) is comparable to state-of-art monocular solutions in terms of computational cost, while providing signifi- cantly greater robustness. We evaluate our S-MSCKF algorithm and compare it with state-of-art methods including OKVIS, ROVIO, and VINS-MONO on both the EuRoC dataset, and our own experimental datasets demonstrating fast autonomous flight with maximum speed of 17.5m/s in indoor and outdoor environments. Our implementation of the S-MSCKF is available at https://github.com/KumarRobotics/msckf_vio.

##### Abstract (translated by Google)
近年来，用于状态估计的视觉辅助惯性测量法已经显着成熟。然而，由于尺寸和重量方面的限制，我们在提高微型飞行器自主飞行应用的底层算法的计算效率和鲁棒性方面仍面临挑战，其中微型飞行器难以使用高质量的传感器和强大的处理器。在本文中，我们提出了一种基于滤波器的立体视觉惯性测速法，它使用多态约束卡尔曼滤波器（MSCKF）[1]。以前关于立体视觉惯性测距法的研究已经产生了计算上昂贵的解决方案。我们证明，我们的立体多态约束卡尔曼滤波器（S-MSCKF）在计算成本方面与先进的单眼解决方案相媲美，同时提供显着更强的鲁棒性。我们评估了我们的S-MSCKF算法，并与EuRoC数据集上的OKVIS，ROVIO和VINS-MONO等最先进的方法进行了比较，我们自己的实验数据集展示了最大速度为17.5m / s的快速自主飞行室内和室外环境。我们可以在https://github.com/KumarRobotics/msckf_vio上找到S-MSCKF的实现。

##### URL
[http://arxiv.org/abs/1712.00036](http://arxiv.org/abs/1712.00036)

##### PDF
[http://arxiv.org/pdf/1712.00036](http://arxiv.org/pdf/1712.00036)

