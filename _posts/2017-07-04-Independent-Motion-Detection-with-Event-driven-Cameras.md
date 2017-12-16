---
layout: post
title: "Independent Motion Detection with Event-driven Cameras"
date: 2017-07-04 19:48:45
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Valentina Vasco, Arren Glover, Elias Mueggler, Davide Scaramuzza, Lorenzo Natale, Chiara Bartolozzi
mathjax: true
---

* content
{:toc}

##### Abstract
Unlike standard cameras that send intensity images at a constant frame rate, event-driven cameras asynchronously report pixel-level brightness changes, offering low latency and high temporal resolution (both in the order of micro-seconds). As such, they have great potential for fast and low power vision algorithms for robots. Visual tracking, for example, is easily achieved even for very fast stimuli, as only moving objects cause brightness changes. However, cameras mounted on a moving robot are typically non-stationary and the same tracking problem becomes confounded by background clutter events due to the robot ego-motion. In this paper, we propose a method for segmenting the motion of an independently moving object for event-driven cameras. Our method detects and tracks corners in the event stream and learns the statistics of their motion as a function of the robot's joint velocities when no independently moving objects are present. During robot operation, independently moving objects are identified by discrepancies between the predicted corner velocities from ego-motion and the measured corner velocities. We validate the algorithm on data collected from the neuromorphic iCub robot. We achieve a precision of ~ 90 % and show that the method is robust to changes in speed of both the head and the target.

##### Abstract (translated by Google)
与以恒定帧速发送强度图像的标准相机不同，事件驱动相机异步报告像素级亮度变化，提供低延迟和高时间分辨率（均为微秒级）。因此，它们对于机器人的快速和低功率视觉算法具有巨大的潜力。例如，即使对于非常快速的刺激，也可以很容易地实现视觉追踪，因为只有移动的物体才会引起亮度变化。然而，安装在移动机器人上的相机通常是非平稳的，并且相同的跟踪问题由于机器人自我运动而被背景混乱事件混淆。在本文中，我们提出了一种用于事件驱动相机的独立移动物体的运动分割的方法。我们的方法检测和跟踪事件流中的角点，并且当没有独立移动的物体存在时，学习他们的运动统计作为机器人关节速度的函数。在机器人操作过程中，独立移动的物体通过预测的自身运动的角速度和测量的角速度之间的差异来识别。我们验证从神经形态iCub机器人收集的数据的算法。我们达到了约90％的精度，表明该方法对于头部和目标的速度变化都是稳健的。

##### URL
[https://arxiv.org/abs/1706.08713](https://arxiv.org/abs/1706.08713)

##### PDF
[https://arxiv.org/pdf/1706.08713](https://arxiv.org/pdf/1706.08713)

