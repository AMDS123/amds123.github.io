---
layout: post
title: "Event-based Dynamic Face Detection and Tracking Based on Activity"
date: 2018-03-27 14:27:26
categories: arXiv_CV
tags: arXiv_CV Face Tracking Detection Face_Detection
author: Gregor Lenz, Sio-Hoi Ieng, Ryad Benosman
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first purely event-based approach for face detection using an ATIS, a neuromorphic camera. We look for pairs of blinking eyes by comparing local activity across the input frame to a predefined range, which is defined by the number of events per second in a specific location. If within range, the signal is checked for additional constraints such as duration, synchronicity and distance between the eyes. After a valid blink is registered, we await a second blink in the same spot to initiate Gaussian trackers above the eyes. Based on their position, a bounding box around the estimated outlines of the face is drawn. The face can then be tracked until it is occluded.

##### Abstract (translated by Google)
我们用ATIS（一种神经形态相机）提出了第一种纯粹基于事件的人脸检测方法。我们通过将输入框中的本地活动与预定范围进行比较来寻找闪烁的眼睛对，该范围由特定位置的每秒事件数定义。如果在范围内，则检查信号是否存在其他约束条件，如持续时间，同步性和眼睛之间的距离。在注册有效的眨眼后，我们等待在同一个点眨眼，以启动眼睛上方的高斯跟踪器。根据它们的位置，绘制围绕估计的脸部轮廓的边界框。然后可以追踪脸部，直到它被遮挡。

##### URL
[https://arxiv.org/abs/1803.10106](https://arxiv.org/abs/1803.10106)

##### PDF
[https://arxiv.org/pdf/1803.10106](https://arxiv.org/pdf/1803.10106)

