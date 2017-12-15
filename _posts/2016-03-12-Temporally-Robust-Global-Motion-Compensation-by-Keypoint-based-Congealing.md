---
layout: post
title: "Temporally Robust Global Motion Compensation by Keypoint-based Congealing"
date: 2016-03-12 21:42:18
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Recognition
author: S. Morteza Safdarnejad, Yousef Atoum, Xiaoming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Global motion compensation (GMC) removes the impact of camera motion and creates a video in which the background appears static over the progression of time. Various vision problems, such as human activity recognition, background reconstruction, and multi-object tracking can benefit from GMC. Existing GMC algorithms rely on sequentially processing consecutive frames, by estimating the transformation mapping the two frames, and obtaining a composite transformation to a global motion compensated coordinate. Sequential GMC suffers from temporal drift of frames from the accurate global coordinate, due to either error accumulation or sporadic failures of motion estimation at a few frames. We propose a temporally robust global motion compensation (TRGMC) algorithm which performs accurate and stable GMC, despite complicated and long-term camera motion. TRGMC densely connects pairs of frames, by matching local keypoints of each frame. A joint alignment of these frames is formulated as a novel keypoint-based congealing problem, where the transformation of each frame is updated iteratively, such that the spatial coordinates for the start and end points of matched keypoints are identical. Experimental results demonstrate that TRGMC has superior performance in a wide range of scenarios.

##### Abstract (translated by Google)
全局运动补偿（GMC）消除了相机运动的影响，并创建了一个视频，在该视频中，背景在时间进程中呈现静态。 GMC可以从各种视觉问题中受益，如人类活动识别，背景重建和多目标跟踪。现有的GMC算法依靠顺序处理连续帧，通过估计映射两个帧的变换，并获得到全局运动补偿坐标的合成变换。由于错误积累或几帧运动估计的零星故障，顺序GMC遭受来自精确全局坐标的时间漂移​​。我们提出一种时间稳健的全局运动补偿（TRGMC）算法，该算法执行精确和稳定的GMC，尽管复杂和长期的相机运动。 TRGMC通过匹配每个帧的本地关键点密集地连接帧对。这些帧的联合对齐被表述为一种新颖的基于关键点的凝结问题，其中每个帧的变换被迭代地更新，使得匹配的关键点的起点和终点的空间坐标是相同的。实验结果表明，TRGMC在广泛的场景中具有优越的性能。

##### URL
[https://arxiv.org/abs/1603.03968](https://arxiv.org/abs/1603.03968)

##### PDF
[https://arxiv.org/pdf/1603.03968](https://arxiv.org/pdf/1603.03968)

