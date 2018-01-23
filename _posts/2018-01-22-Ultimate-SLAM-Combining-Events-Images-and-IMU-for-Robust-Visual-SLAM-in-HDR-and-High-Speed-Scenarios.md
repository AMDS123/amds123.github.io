---
layout: post
title: "Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High Speed Scenarios"
date: 2018-01-22 15:31:17
categories: arXiv_RO
tags: arXiv_RO Knowledge SLAM
author: Antoni Rosinol Vidal, Henri Rebecq, Timo Horstschaefer, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Event cameras are bio-inspired vision sensors that output pixel-level brightness changes instead of standard intensity frames. These cameras do not suffer from motion blur and have a very high dynamic range, which enables them to provide reliable visual information during high speed motions or in scenes characterized by high dynamic range. However, event cameras output only little information when the amount of motion is limited, such as in the case of almost still motion. Conversely, standard cameras provide instant and rich information about the environment most of the time (in low-speed and good lighting scenarios), but they fail severely in case of fast motions, or difficult lighting such as high dynamic range or low light scenes. In this paper, we present the first state estimation pipeline that leverages the complementary advantages of these two sensors by fusing in a tightly-coupled manner events, standard frames, and inertial measurements. We show on the publicly available Event Camera Dataset that our hybrid pipeline leads to an accuracy improvement of 130% over event-only pipelines, and 85% over standard-frames-only visual-inertial systems, while still being computationally tractable. Furthermore, we use our pipeline to demonstrate - to the best of our knowledge - the first autonomous quadrotor flight using an event camera for state estimation, unlocking flight scenarios that were not reachable with traditional visual-inertial odometry, such as low-light environments and high-dynamic range scenes.

##### Abstract (translated by Google)
事件相机是生物启发视觉传感器，输出像素级亮度变化，而不是标准强度帧。这些相机不会受到运动模糊的影响，并具有非常高的动态范围，这使得它们能够在高速运动或高动态范围的场景中提供可靠的视觉信息。然而，事件相机在运动量有限时（例如在几乎静止的情况下）仅输出很少的信息。相反，标准摄像机在大多数时间（在低速和良好的照明场景下）提供即时和丰富的环境信息，但在高速运动或高动态范围或低光照场景等困难的情况下会严重损坏。在本文中，我们提出了第一个状态估计流水线，它利用这两个传感器的互补优势，以紧耦合的方式融合事件，标准帧和惯性测量。我们在公开的“事件相机数据集”上展示了：我们的混合流水线比单纯事件流水线的准确度提高了130％，而标准框架的视觉惯性系统的准确度提高了85％，同时仍然在计算上易于处理。此外，我们使用我们的管道来展示 - 我们所知道的 - 使用事件相机进行状态估计的第一个自主四旋翼飞行，解开传统视觉惯性测距法无法达到的飞行场景，如低光环境和高动态范围场景。

##### URL
[http://arxiv.org/abs/1709.06310](http://arxiv.org/abs/1709.06310)

##### PDF
[http://arxiv.org/pdf/1709.06310](http://arxiv.org/pdf/1709.06310)

