---
layout: post
title: "Asynchronous, Photometric Feature Tracking using Events and Frames"
date: 2018-07-25 16:40:05
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Daniel Gehrig, Henri Rebecq, Guillermo Gallego, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method that leverages the complementarity of event cameras and standard cameras to track visual features with low-latency. Event cameras are novel sensors that output pixel-level brightness changes, called "events". They offer significant advantages over standard cameras, namely a very high dynamic range, no motion blur, and a latency in the order of microseconds. However, because the same scene pattern can produce different events depending on the motion direction, establishing event correspondences across time is challenging. By contrast, standard cameras provide intensity measurements (frames) that do not depend on motion direction. Our method extracts features on frames and subsequently tracks them asynchronously using events, thereby exploiting the best of both types of data: the frames provide a photometric representation that does not depend on motion direction and the events provide low-latency updates. In contrast to previous works, which are based on heuristics, this is the first principled method that uses raw intensity measurements directly, based on a generative event model within a maximum-likelihood framework. As a result, our method produces feature tracks that are both more accurate (subpixel accuracy) and longer than the state of the art, across a wide variety of scenes.

##### Abstract (translated by Google)
我们提出了一种方法，利用事件相机和标准相机的互补性来跟踪低延迟的视觉特征。事件相机是输出像素级亮度变化的新型传感器，称为“事件”。与标准相机相比，它们具有明显的优势，即非常高的动态范围，无运动模糊，以及微秒级的延迟。然而，因为相同的场景模式可以根据运动方向产生不同的事件，所以建立跨时间的事件对应是具有挑战性的。相比之下，标准相机提供不依赖于运动方向的强度测量（帧）。我们的方法提取帧上的特征，然后使用事件异步跟踪它们，从而利用两种类型数据中的最佳类型：帧提供不依赖于运动方向的光度表示，并且事件提供低延迟更新。与先前基于启发式的工作相比，这是基于最大似然框架内的生成事件模型直接使用原始强度测量的第一原理方法。因此，我们的方法可以在各种各样的场景中生成比现有技术更精确（亚像素精度）和更长的特征轨迹。

##### URL
[http://arxiv.org/abs/1807.09713](http://arxiv.org/abs/1807.09713)

##### PDF
[http://arxiv.org/pdf/1807.09713](http://arxiv.org/pdf/1807.09713)

