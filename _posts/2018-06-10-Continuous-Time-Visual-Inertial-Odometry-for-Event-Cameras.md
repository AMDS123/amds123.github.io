---
layout: post
title: "Continuous-Time Visual-Inertial Odometry for Event Cameras"
date: 2018-06-10 17:42:56
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Elias Mueggler, Guillermo Gallego, Henri Rebecq, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Event cameras are bio-inspired vision sensors that output pixel-level brightness changes instead of standard intensity frames. They offer significant advantages over standard cameras, namely a very high dynamic range, no motion blur, and a latency in the order of microseconds. However, due to the fundamentally different structure of the sensor's output, new algorithms that exploit the high temporal resolution and the asynchronous nature of the sensor are required. Recent work has shown that a continuous-time representation of the event camera pose can deal with the high temporal resolution and asynchronous nature of this sensor in a principled way. In this paper, we leverage such a continuous-time representation to perform visual-inertial odometry with an event camera. This representation allows direct integration of the asynchronous events with micro-second accuracy and the inertial measurements at high frequency. The event camera trajectory is approximated by a smooth curve in the space of rigid-body motions using cubic splines. This formulation significantly reduces the number of variables in trajectory estimation problems. We evaluate our method on real data from several scenes and compare the results against ground truth from a motion-capture system. We show that our method provides improved accuracy over the result of a state-of-the-art visual odometry method for event cameras. We also show that both the map orientation and scale can be recovered accurately by fusing events and inertial data. To the best of our knowledge, this is the first work on visual-inertial fusion with event cameras using a continuous-time framework.

##### Abstract (translated by Google)
事件相机是生物启发的视觉传感器，可输出像素级亮度变化，而不是标准强度帧。它们与标准相机相比具有显着的优势，即非常高的动态范围，无运动模糊，以及微秒级别的延迟。但是，由于传感器输出的结构基本不同，因此需要采用高时间分辨率和传感器异步特性的新算法。最近的工作表明，事件相机姿态的连续时间表示可以原则上处理该传感器的高时间分辨率和异步性质。在本文中，我们利用这种连续时间表示法，用事件相机执行视觉惯性测距。这种表示方式可以将异步事件与微秒级精度和惯性测量结果直接整合在一起。事件相机轨迹通过使用三次样条的刚体运动空间中的平滑曲线来近似。该公式显着减少了轨迹估计问题中的变量数量。我们对来自多个场景的实际数据评估我们的方法，并将结果与​​动作捕捉系统的地面实况进行比较。我们表明，我们的方法比事件相机的最先进的视觉测距方法的结果提供了更高的精度。我们还表明，通过融合事件和惯性数据，可以准确地恢复地图方向和比例尺。据我们所知，这是第一部使用连续时间框架的事件相机进行视觉 - 惯性融合的工作。

##### URL
[http://arxiv.org/abs/1702.07389](http://arxiv.org/abs/1702.07389)

##### PDF
[http://arxiv.org/pdf/1702.07389](http://arxiv.org/pdf/1702.07389)

