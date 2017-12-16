---
layout: post
title: "Continuous-Time Visual-Inertial Trajectory Estimation with Event Cameras"
date: 2017-02-23 20:56:09
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Elias Mueggler, Guillermo Gallego, Henri Rebecq, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
In contrast to traditional cameras, which output images at a fixed rate, event cameras have independent pixels that output asynchronous pixel-level brightness changes with microsecond resolution. In this paper, we leverage a continuous-time framework to perform trajectory estimation by fusing visual data from a moving event camera with inertial data from an IMU. This framework allows direct integration of the asynchronous events with micro-second accuracy and the inertial measurements at high frequency. The pose trajectory is approximated by a smooth curve in the space of rigid-body motions using cubic splines. This formulation significantly reduces the number of variables in trajectory estimation problems. We evaluate our method on real data from several scenes and compare the results against ground truth from a motion-capture system. We show superior performance of the proposed technique compared to non-batch event-based algorithms. We also show that both the map orientation and scale can be recovered accurately by fusing events and inertial data. To the best of our knowledge, this is the first work on visual-inertial fusion with event cameras using a continuous-time framework.

##### Abstract (translated by Google)
与以固定速率输出图像的传统相机相比，事件相机具有独立像素，以微秒分辨率输出异步像素级亮度变化。在本文中，我们利用连续时间框架通过将来自移动事件相机的视觉数据与来自IMU的惯性数据融合来执行轨迹估计。这个框架可以将异步事件与微秒精确度和高频惯性测量直接整合在一起。姿态轨迹用刚体运动空间中的光滑曲线近似为三次样条。该公式显着减少了轨迹估计问题中的变量数量。我们对来自多个场景的实际数据评估我们的方法，并将结果与​​来自运动捕捉系统的地面实况进行比较。与非批量事件的算法相比，我们展示了所提出的技术的优越性能。我们还表明，通过融合事件和惯性数据，可以准确地恢复地图方向和尺度。就我们所知，这是第一部使用连续时间框架的事件相机进行视觉 - 惯性融合的工作。

##### URL
[https://arxiv.org/abs/1702.07389](https://arxiv.org/abs/1702.07389)

##### PDF
[https://arxiv.org/pdf/1702.07389](https://arxiv.org/pdf/1702.07389)

